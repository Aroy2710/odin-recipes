# File Pathing
- If your file is a folder lets call it parent and you want to access a subfolder of the parent just ./subfolder_name/... the ... refers to extra paths in case the subfolder has extra folders. If the file is directly inside the subfolder then just use the filename
- If you want to access a sibling of the parent use .. before the first / , for example ../ 
- Same idea if you want to access the grand parent ../../...
- The .. in general allows you to go up to the level your parent at if you imagine the file structure as a tree.