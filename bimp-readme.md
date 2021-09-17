# Creating images from Salesforce Icons

## Square When Rounded Corners
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

The site https://encycolorpedia.com/ allows you to plug in the hex value and find the inverse of it, use this value in the colourify step.


## Circle Background
This cannot be done completely in BIMP but rather it's a three step process

Overview
1. invert the image 
2. Resize the image in image magic
3. colour the image, invert the image and round the shape

This will all make sense as you work through the steps.  I recomend making a copy of the images you're working on just in case you have an issue. 

Select SVG files you want to use, this works best with the SVG as the start image as you don't have the 60 and 120 images to deal with.

1. In BIMP invert the image, this provides you with the icon in black and save as a PNG
	1. Gimp Drawable Invert
	2. Change Format and Compression
2. Use Mogrify which is part of imagemagick
	1. mogrify -extent 56x56 -gravity Center -fill white *.png
3. Use BIMP to create the final image
	1. Gimp image convert RGB
	2. plug-in colorify
	3. Gimp Drawable Invert
	4. Scriptfu Rounded Corners edge radius 28, nothing else set
	
The second BIMP file is also provided 
