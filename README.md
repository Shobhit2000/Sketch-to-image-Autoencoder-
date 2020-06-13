[![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/)

[![Python 3.6](https://img.shields.io/badge/python-3.6-green.svg)](https://www.python.org/downloads/release/python-360/) 

# Sketch to Image(Autoencoder)
  We all must have drawn sketches sometime or the other and must have wondered how would it look like if it was an image. This progam does this for you, all you need to do is feed in the sketch as the input and get back the image from the program.
  
  This is an autoencoder based project which takes in the balck and white image as the input and returns the coloured image. The main advantage of using autoencoders is that one can get only the important features of a particular image which is called the "Latent Vector" which means that it eliminates the noise from the image and if we have only the Latent Vector can reconstruct the entire image from it with almost no loss as compared to the original image. Moreover the size of the latent vector is very small compared to the original image.
  
## Dependencies
```bash
numpy
matplotlib
cv2
keras
```

We use the cifar10 dataset for this program. Since I could not find any dataset which has sketches as the input data and the corresponding  image as the output data, so I manually created the input dataset by converting the images to sketches which is done the preprocessing function and the corresponding original images as output images. The sketch created in the program is very similar to the actual pencil sketch which people generally create.

## Author
[![LinkedIn-profile](https://img.shields.io/badge/LinkedIn-Profile-teal.svg)](https://www.linkedin.com/in/shobhit-tulshain-a7562916b/)

* [**Shobhit Tulshain**](https://github.com/Shobhit2000)
