# Palette

- The code takes the object image as input.
- Using canny detect edges
- Morphology close method on the canny for closing small holes inside the foreground.
- Find contour of the Morphology image and fill it with white colour.
- Find the biggest contour.
- Fill the contour area to avoid unwant noise and create final mask. 
- Draw outline on the input image
