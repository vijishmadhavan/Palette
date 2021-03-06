# Palette

### Try in Colab
[<img src="https://colab.research.google.com/assets/colab-badge.svg" align="center">](https://colab.research.google.com/github/vijishmadhavan/Palette/blob/master/Palette_10.ipynb)

- The code takes the object image as input.
<p align="center"><img src="https://github.com/vijishmadhavan/Palette/blob/master/Images/flying-peacock-fb1__700.jpeg"/></p>

- Using "canny" detects edges

<p align="center"><img src="https://github.com/vijishmadhavan/Palette/blob/master/Images/download%20(4).png"/></p>

- "Morphology close" method on the canny for closing small holes inside the foreground.

<p align="center"><img src="https://github.com/vijishmadhavan/Palette/blob/master/Images/download%20(5).png"/></p>

- Find contour of the Morphology image and detect the biggest contour.
- Fill the contour area to avoid unwant noise and create final mask. **Or use pretrained models to generate mask(DeepLabv3)**

<p align="center"><img src="https://github.com/vijishmadhavan/Palette/blob/master/Images/download%20(3)-side.png"/></p>


- Draw outline on the input image

<p align="center"><img src="https://github.com/vijishmadhavan/Palette/blob/master/Images/download%20(10).png"/></p>

# Colour Palette - KMEANS
- Remove background get the object and generate color palette using KMEANS, find the centroids and plot.

<p align="center"><img src="https://github.com/vijishmadhavan/Palette/blob/master/Images/aaaa.jpg"/></p>

# Colour Palette - Mosaic principle (Image Sampling)

- **Mosaic Principle** :Replace the pixel value of the selected area in the image with a pixel value in the selected area .

- Find all the dominant colours and plot the top-5 out of it.

<p align="center"><img src="https://github.com/vijishmadhavan/Palette/blob/master/Images/download.png"/></p>




## Acknowledgements

- [Image Color Extraction with Python](https://towardsdatascience.com/image-color-extraction-with-python-in-4-steps-8d9370d9216e)
- [DeepLabV3Plus](https://github.com/VainF/DeepLabV3Plus-Pytorch)
- https://chowdera.com/2020/11/20201127202251706v.html
