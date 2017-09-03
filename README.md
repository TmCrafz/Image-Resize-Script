# Image-Resize-Script
A script which resize images in a given directory to a specified min length and keep aspect ratio. The script dont work recursive, so sub folders so the script ignores them. Also the script dont check if the files are valid images, so if there are other files then supported image files in the direcory the result can be complete garbage.
The script uses ImageMagick.

Example:
```
./resize.sh sourceDir destDir 500 log.txt 
```
Resizes all files in sourceDir which width or height is under 500px to a min site length of 500px and stores the converted files to destDir. The name of resized files are logged in log.txt.

The log file parameter is optional.
