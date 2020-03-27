# connect-images-dir
Automatically Create the 'images' dir required in connect packages based on property.conf. The complete dir strucutre with the
correct filenames are created.

## What is connect-images-dir
This script will take your connect App property.conf and create the complete 'Images' dir strucutre. 

## Installation
Ensure you have python 3
## Usage
1) Installed the pre-req library and version of Python
2) Run 'python3 connect_images_dir_create property.conf' (Valid property.conf)
3) Ensure you don't have stale 'images' dir in the present working directory
4) Successful run will result in the 'images' directory with the following directories as well as the exact icon names, simply replace with correct images
* action_groups
* actions
* field_groups
* templatedirs
  
