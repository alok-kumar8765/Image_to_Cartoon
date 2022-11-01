# Image to Cartoon Python OpenCV Machine Learning Free Source Code
## Required modules in this Projects
    * CV2: Imported to use OpenCV for image processing
    * easygui: Imported to open a file box. It allows us to select any file from our system.
    * Numpy: Images are stored and processed as numbers. These are taken as arrays. We use NumPy to deal with arrays.
    * Imageio: Used to read the file which is chosen by file box using a path.
    * Matplotlib: This library is used for visualization and plotting. Thus, it is imported to form the plot of images.
    * OS: For OS interaction. Here, to read the path and save images to that path.
    * Flask: Flask is a micro web framework written in Python.

## Steps to develop Image to cartoon 
    - Importing the required modules
    - Building a File Box to choose a particular file
    - How is an image stored?
    - Transforming an image to grayscale
    - Smoothening a grayscale image
    - Retrieving the edges of an image
    - Preparing a Mask Image
    - Giving a Cartoon Effect
    - Plotting all the transitions together
    - Functionally of save or download  button

## Installation

### Application tested on:

- python 3.7
- tensorflow 2.1.0 
- tf_slim 1.1.0
- ffmpeg 3.4.8
- Cuda version 10.1
- OS: Linux (Ubuntu 18.04)


### Using `virtualenv`

1. Make a virtual environment using `virutalenv` and activate it
```
virtualenv -p python3 cartoonize
source cartoonize/bin/activate
```
2. Install python dependencies
```
pip install -r requirements.txt
```
3. Run the webapp. Be sure to set the appropriate values in `config.yaml` file before running the application.
```
python app.py
```
# Algorithmia For Video Convert 
    We used the Serveless AI Layer product of <a href="https://algorithmia.com/product">Algorithmia</a> for inference on videos. To learn more on how to deploy your model in Algorithmia, check here - https://algorithmia.com/developers

