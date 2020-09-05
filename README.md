# Divide to Glitter (D2G-Net)
Requirements
Python 
Tensorflow >= 1.10.0
numpy, PIL

Descriptions: This project is a TensorFlow implementation of a Divide and Glitter low light images. We aim to enhance the images with front-lit, backlit, low-lit, high-lit, dim or weak-lit and a combination of these conditions. We employ Retinex theory and utilize dark channel prior to upgrade the low light images for pleasing visual quality. The model implemented in this regard is compliled of simple and light weight Divide-Net (to divide image) and use an encoder-decoder (3x3 up-down sampling) unit as Glare-Net to repair llumination.

Dataset:

The dataset consist of 1300 images with ill-illumination conditions, arranged as under-exposes to well exposed.
Test and GT images: We presented evaluation on 37-test images from our data set, whereas the dataset contain many sample images with reference images and in each case a high exposure can act as a reference GT for the low exposure test image. We have presented the seperate files for test and training data, where every scene has a seperate folder with multiple exposures.

Dataset-Link: The dataset can be downloaded from the google grive link : https://drive.google.com/drive/u/1/folders/1uj8MGHWtRMbeuh8VZemmIv-wqUqVNdo6
