# Creating images from Salesforce Icons

## Steps
These were carried out against the SVG files, but this should work for the PNG ones.

1. Gimp Drawable Invert 
2. Gimp Image Flatten
3. plugin colorify  
4. Gimp Drawable Invert
5. Scriptfu Rounded Corners edge radius of 10, nothing else set
6. Change Format & Compression


The above steps carry out the following;
1. turns white to black
2. removes the background transparency and turns it white, this is why we had to do the invert
3. turns all white areas to a specific colour
4. turns the black back to white, and also inverts the color in the previous step
5. Rounds the corners and leaves the gaps as a transparency
6. needed for the SVG, save as PNG to preseve transparency.

When you chose your target background colour you then need to find the inverse colour and use that in the colourify step.  Otherwise you won't get the colour your expecting.

