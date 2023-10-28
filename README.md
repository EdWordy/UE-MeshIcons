# UE-MeshIcons

### README

#### Part 1

1. Download and install the plugin
2. Enable the plugin; restart the editor as required.

#### Part 2

4. Open a blank level
5. Place BP_MeshIconMaker in the world
6. Under Default, set the settings to the desired settings; this includes dimension, source mesh, and name.
7. Click "Create Icon"; The icon should appear in the plugins Assets folder beside the render target.
8. If the image requires adjustment, adjust the spring arm as needed to centre the image.

#### Part 3 (OPTIONAL: if you need more than a texture 2d, read on!)

10. Create a new material instance from the M_MeshIconBase material by right click it and selecting the option in the context menu.
11. Set the parameters, including rotation (-0.25 for rotated, or .25 for the opposite perpendicular angle), and source image. Name the texture appropriately if you haven't done so already.
13. Use the material as needed!

### Notice
MIT License. 

Current plugin version is 1.0 for version 5.3 of Unreal Engine.
