io_mesh_pz
=
###Blender Import/Export script for Project Zomboid models###

Please note that this document and the source code is constantly work in progress.

##What is it ?

This is a [Blender](http://www.blender.org) plugin for importing and exporting 3D models for the game [Project Zomboid](http://projectzomboid.com/) by IndieStone.

The scripts are written in Python and tested with Blender v2.7

##Licensing

This plugin is released under the terms of the GPL License. For more information, please read carefully the License.md file attached to this git repository.

##Installation

Copy the folder io_mesh_pz/ into the addons folder within your Blender folder:

    \Blender Foundation\Blender\2.xxx\scripts\addons\

You must restart Blender to load the plugin.

In Blender, the plugin must be activated in 

 - File > User Preferences... 
 - Select the 'Addons' tab
 - Select the 'Import/Export' category
 - Check the 'Project Zomboid mesh format (.txt)' plugin

You should see new choices in 'File > Import...' and 'File > Export...' menus

##Usage Pre-requisites

You must have installed ProjectZomboid from a legitimate source (= own your copy), generally from Steam.

The model files (*.txt) are located in 
\ProjectZomboid\media\models

Texture image files are located in 
\ProjectZomboid\media\textures

##Importing a Project Zomboid 3D model into Blender
		 
###Importing the mesh
    
 - In Blender, go to File > Import... > Project Zomboid model (*.txt)
 - Navigate to the models folder and select one file
 - Click Import button on top right corner
 
###Importing and applying texture images

The plugin automatically imports per-vertex UV map. However applying the image texture from the game must be done manually.

 - Split the main view as follows : 3D View on the left, UV/Image Editor on the right
 - In the left view, change to Object Mode and select the mesh, then change to Edit Mode
 - In the right view, click Open Image and browse to the image texture file
 - 

[WIP]
		
##Exporting a blender mesh for Project Zomboid
    
[WIP]
    
    



