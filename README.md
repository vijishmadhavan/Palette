# Palette

### Try in Colab
[<img src="https://colab.research.google.com/assets/colab-badge.svg" align="center">](https://colab.research.google.com/github/vijishmadhavan/Palette/blob/master/Palette_1.ipynb)

- The code takes the object image as input.
<p align="center"><img src="https://github.com/vijishmadhavan/Palette/blob/master/Images/flying-peacock-fb1__700.jpeg"/></p>

- Using "canny" detects edges

<p align="center"><img src="https://github.com/vijishmadhavan/Palette/blob/master/Images/download%20(4).png"/></p>

- "Morphology close" method on the canny for closing small holes inside the foreground.

<p align="center"><img src="https://github.com/vijishmadhavan/Palette/blob/master/Images/download%20(5).png"/></p>

- Find contour of the Morphology image and fill it with white colour(if in case any noise remains).
- Find the biggest contour.
- Fill the contour area to avoid unwant noise and create final mask. **Or use pretrained models to generate mask(DeepLabv3)**

<p align="center"><img src="https://github.com/vijishmadhavan/Palette/blob/master/Images/download%20(3)-side.png"/></p>


- Draw outline on the input image

<p align="center"><img src="https://github.com/vijishmadhavan/Palette/blob/master/Images/download%20(10).png"/></p>


- Remove background get the object and generate color palette using extcolors package.

<p align="center"><img src="https://github.com/vijishmadhavan/Palette/blob/master/Images/aaaa.jpg"/></p>
