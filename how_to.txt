# How to edit the website

## Make a new tile
Add a new .md file with the corresponding name. Add a permalink and then .hmtl file.



Add it to the menu in the menu.html

## Change the colors of the website
The main colors are defined in the _varr.scss file in the color palette
$palette: (
		bg:					#242943, //background color for the site
		bg-alt:				#2a2f4a, // alternative background color
		fg:					#ffffff, // font color
		fg-bold:			#ffffff, // font color
		fg-light:			rgba(244,244,255,0.2), //font color
		border:				rgba(212,212,255,0.1), // border color for boxes
		border-bg:			rgba(212,212,255,0.035), // border color
		highlight:			#9bf1ff, // highlight color
		accent1:			#6fc3df, // accent colors used in the website
		accent2:			#8d82c4,
		accent3:			#ec8d81,
		accent4:			#e7b788,
		accent5:			#8ea9e8,
		accent6:			#87c5a4
	);

Colors for the tiles can be changed in the _tiles.scss file


## Change images to greyscale

Add the follwing to the scss files where images are defined

  -webkit-filter: grayscale(100%); /* Safari 6.0 - 9.0 */
  filter: grayscale(100%);
