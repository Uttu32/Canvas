# Canvas


#Deployment Link :- https://canvas-eta-lemon.vercel.app/


The canvas element is created with a width of 16 pixels and a height of 34 pixels.

The character 'T' is drawn at the center of the canvas using a bold 20px Arial font with the specified font color (Yellow) on a black background.

The download Link element is used to create a download link for the generated pixel data file. When the "Download" link is clicked, the script extracts the pixel data from the canvas, converts the RGB values to hexadecimal format, and creates a text file with the data.

The text file is created as a Blob (binary large object) using the Blob constructor.

The URL.createObjectURL() method is used to generate a URL for the Blob, which is then assigned to the href attribute of the "Download" link. This allows the user to download the file when clicking the link.
