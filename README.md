# vulkan-herewego

First project using Vukan, no proper goal except having fun with the API

Core based on https://vulkan-tutorial.com/Introduction
- no multisampling 
- no mipmaping

Global additional features :
- Swap chain recreation using oldSwapChain
- Dynamic states for the viewport and scissors => no need to recreate the Graphics Pipeline after SwapChain recreation
- Dynamic UBO for individual object transformation
- Unique Vertex Buffer storing all the vertices from every objects

GLFW specific implementations :
- Look around when dragging with left mouse button
- Pause when hitting escape
- Moving forward/backward when scrolling

