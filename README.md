# vulkan-herewego

First project using Vukan, no proper goal except having fun with the API

Core based on https://vulkan-tutorial.com/Introduction

Global additional features :
- Swap chain recreation using oldSwapChain
- Dynamic states for viewports and scissors => no need to recreate the Graphics Pipeline after SwapChain recreation
- Dynamic UBO for individual object transformation
- Multiple meshes drawing using an unique Vertex Buffer storing all the vertices from every objects
- Per object texture: two descriptor sets binded (one with the DUBO and one with the texture)
- Global mesh holding structure for further scene rendering
- Skybox (second graphics pipeline etc..)

GLFW specific implementations :
- Look around when dragging with left mouse button
- Pause when hitting escape
- Moving forward/backward when scrolling

External ressources:
- DUBO: https://github.com/SaschaWillems/Vulkan/blob/master/examples/dynamicuniformbuffer/README.md
- Camera control with glfw: https://learnopengl.com/Getting-started/Camera

External libraries:
- glfw: https://www.glfw.org/
- glm: https://glm.g-truc.net/0.9.9/index.html
- stb: https://github.com/nothings/stb
- tiny_obj_loader: https://github.com/tinyobjloader/tinyobjloader
