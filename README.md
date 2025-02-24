# Project Name
> Melonoma detection 
Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
Melonoma detection using Convolution Neural networks is the goal of this assignement . We need to build a CNN architecture using custom model that can accurately detect the skin cancer from around 2400 images .The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.


## Conclusions
Initial CNN model that was built had clearly overfitting and it has a good gap between the training and validation accuracy , Validation loss was also not decreasing consisttnly with epochs . Then adding a droupput layer ade it little better and the accuracy levels were closer 
Then data augmentation was also tried. Finally we detected class imbalance in the dataset that did not allow the model to learn all kinds of images well enough
After the class imbalance was normalised , data augmentation and dropout yieleded better acuuracy ob both train and vlaidation dataset and the loss was also improving over epochs  




## Technologies Used
Tensorflow and Keras 
Google collab was used to run 
Numpy 


<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by Upgrad Executive PG Diplamo in AI/ML 
- References -- https://www.tensorflow.org/tutorials/images/classification
- This project was based on ISIC datasets 


## Contact
Created by [@rengsnbuc] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->