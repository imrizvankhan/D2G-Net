# Divide to Glitter (D2G-Net)
Requirements
Python 
Tensorflow >= 1.10.0
numpy, PIL

Descriptions: This project is the implementation of the Divide to Glitter (D2G-Net) low light images. We aim to enhance the images captured in the dim or weak-illumination conditions.  We propose a deep hybrid D2G-Net and an enhancement strategy to upgrade the low light images for pleasing visual quality. We propose to learn through the correlation consistency of the decomposed data itself. The model implemented in this regard comprises a simple and lightweight image Division-Net (to divide the image into reflection and illumination) and use an encoder-decoder (3x3 up-down sampling) unit as Glitter-Net to repair ill-illumination. It is the first method capable of working with and without paired training data supervision.

Dataset:

The dataset consists of almost 1300 images with ill-illumination conditions, arranged as under-exposes to well exposed.
Test and GT images: We presented evaluation on test images from our data set, whereas the dataset contains many sample images with reference images, and in each case, high exposure can act as a reference GT for the low exposure test image. We have presented the separate files for test and training data, where every scene has a separate folder with multiple exposures.

Dataset-Link: The whole  training dataset, along with test images, is available at the following google drives link: https://drive.google.com/drive/u/1/folders/1uj8MGHWtRMbeuh8VZemmIv-wqUqVNdo6



<image src= "FinalDatasetsample.png" width= 800>
 
  <image src= "onlymodellow.png" width= 800>
  
   
  <image src= "DepthofresidueMap.png" width= 500>
