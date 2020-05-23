# slidez

## Slideshow generator for linux mint mate desktop background.

This PHP script generates an XML file that can be used as a background slideshow in the linux mint mate desktop. It __recursively__ collects the names of all image files that are present in the directory from where the script is invoked. 

The XML file is named slideshow.xml and it is placed in that same directory.
The script randomizes the order of the images. Every image is showed 57 second and there is a transition interval between the images of 3 seconds. You can change it in the coding if needed.

### Installation:
- Rename the script if you do not like the name (I am using 'slidez' without .php in this example).
- Copy the script to /usr/local/bin (sudo cp slidez /usr/local/bin/slidez).
- Make the file executable if necessary (sudo chmod +x slidez).

### Usage:
- In a terminal, go to your image folder (with cd) and type slidez.
- Right-click the desktop background and click 'change desktop background'.
- Click 'Add...'.
- Select 'All files' on the pulldown button that says 'Images' (above the open button).
- Navigate to your images folder _or_ enter your images folder in the location field.
- Select the file slideshow.xml and click open.
- Done.

### Notes:
- If you add, remove or change images in the image folder, you will have to run slidez again to see the result in the slideshow.
- The random image order is estabished at the moment slidez runs. To get a new random order, you will have to run slidez again.
- Comments and suggestions are always appreciated :)

