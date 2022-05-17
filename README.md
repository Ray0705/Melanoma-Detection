# Melanoma Detection
Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.

Our objective is to build a CNN based model which can accurately detect melanoma.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Initially we build a simple CNN model, we got an training accuracy of around 89% and validation accuracy of around 51%. It is a clear sign of overfitting.
- We have seen that, with the help of **data augmented method** and **dropout regularization method, overfitting of the data can be reduced.** In our case it reduced the overfitting, but decreased our training accuracy(approx. 63%) and validation accuracy(approx. 57%).
- To increase the accuracy of both training and validation with overfitting in check, we used augmented sampling technique with dropout regularization.
- We can see that training accuracy increased from around 63% to 94% approx. and validation accuracy from around 57% to 85% approx. with removal of overfitting.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Pandas - version 1.1.5
- Numpy - version 1.18.5
- Matplotlib - version 3.1.3
- TensorFlow - version 2.8.1
- TensorFlow-gpu - version 2.8.1

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements

- This project was inspired by Upgrad.


## Contact
Created by [@Ray0705](https://github.com/Ray0705) - feel free to contact me!


