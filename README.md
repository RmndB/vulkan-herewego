# vulkan-herewego

First project using Vukan, no proper goal except having fun with the API

Core based on https://vulkan-tutorial.com/Introduction
- no multisampling 
- no mipmaping

Global additional features :
- Swap chain recreation using oldSwapChain
- Dynamic states for the viewport and scissors => no need to recreate the Graphics Pipeline after SwapChain recreation

GLFW specific implementations :
- Look around
- Pause

