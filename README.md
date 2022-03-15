![image](https://user-images.githubusercontent.com/83262692/158303245-763b00c9-0b11-4423-9681-1c7123ecdf45.png)
# PERCLEAN - v2.5
## What is Perclean?
Hello and say hello to Perclean!

Perclean is a simple performance module that has multiple functions that can help you optimize your game, and make your game compatible for low-end PCs and phones. The current version is v2.5!

This module contains two main functions:
* EnableLowQuality
* DisableLowQuality

You can select over 4 total effects, each one changing and optimizing a specific thing. Here are all of them:
* CastShadow
* Lighting
* PartRendering
* RenderDistance

## How can I use it?
You can start by inserting the module inside ReplicatedStorage, make a script and require it, then do perclean.EnableLowQuality(). Here's an example:
```lua
local p = require(workspace.PercleanModule)

while true do
	p.EnableLowQuality("lighting")
	task.wait(2)
	p.DisableLowQuality("lighting")
	task.wait(2)
end
```
This is what it looks like with the example:
### Low Quality Disabled:
![RobloxStudioBeta_MKK7seEXHb](https://user-images.githubusercontent.com/83262692/158304299-3d9fd8ff-a82f-492a-bd23-99a167397f29.png)

### Low Quality Enabled:
![RobloxStudioBeta_eWitGqXcO9](https://user-images.githubusercontent.com/83262692/158304321-1dee9b2a-a5cd-43b2-8340-2aca49abdb3c.png)

## What are the practical uses for this module?
Here are examples of where you could use this module:
* Implementing a render distance option
* Implementing a low-quality button for low-end devices
* Optimizing your game's performance
