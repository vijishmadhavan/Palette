# Palette

- The code takes the object image as input.
<p align="center"><img src="https://github.com/vijishmadhavan/Palette/blob/master/Images/flying-peacock-fb1__700.jpeg"/></p>

- Using canny detects edges

<p align="center"><img src="https://github.com/vijishmadhavan/Palette/blob/master/Images/flying-peacock-fb1__700.jpeg"/></p>

- Morphology close method on the canny for closing small holes inside the foreground.
- Find contour of the Morphology image and fill it with white colour.
- Find the biggest contour.
- Fill the contour area to avoid unwant noise and create final mask. 
- Draw outline on the input image
