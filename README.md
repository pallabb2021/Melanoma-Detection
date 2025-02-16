# Melanoma Detection
> Multiclass classification model using a custom convolutional neural network in TensorFlow. 

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Provide general information about your project here.
- This is multi class classification of Melanoma. It is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A    solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in        diagnosis.
- What is the background of your project?
- The project aims to develop a robust model for the early detection and classification of skin cancer using image data. Skin cancer is one of the most common types of cancer worldwide, and early detection is crucial for effective treatment and improved survival rates. The dataset used for this project is sourced from the ISIC (International Skin Imaging Collaboration) archive, which is a comprehensive collection of dermoscopic images of various skin cancer types, including melanoma.
- What is the business probem that your project is trying to solve?
- To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of   skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual      effort needed in diagnosis.
- What is the dataset that is being used?
- The dataset utilized in this project originates from the ISIC (International Skin Imaging Collaboration) archive, comprising 2357 images of different skin cancer types, including melanoma. It is categorized into nine groups:

Actinic keratosis
Basal cell carcinoma
Dermatofibroma
Melanoma
Nevus
Pigmented benign keratosis
Seborrheic keratosis
Squamous cell carcinoma
Vascular lesion
The images were divided into training and testing directories, with data augmentation techniques applied to enhance the model’s performance and mitigate overfitting

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Conclusion 1 from the analysis \
-- Training accuracy is steadily increasing using training data \
-- Validation accuracy is not showing similar results, it increases in the begining and settles around 10 epoch and does not rise up again, showing overfitting signs \
-- The training loss shows a steady decline \
-- The validation loss shows decline initially but it shoots up again around epoch 10 & 11 which indicates overfitting case \
  
- Conclusion 2 from the analysis \
-- Training accuracy is steadily increasing using training data \
-- Validation accuracy is fully not following the training set, but it is better than the previous model \
-- The training loss shows a steady decline \
-- The validation loss shows decline initially but it shoots up a bit before epoch 10. The loss is much closer to training loss, which shows the overfitting is bit handled with the approach
- Conclusion 3 from the analysis \
-- The overfitting and underfitting problem is handled much better now and the above graph shows the accuracy almost similar in both cases. Also the loss the going down.This was done using Augmentor which created multiple images.



<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- tensorflow - version 2.18.0
- Augmentor - version 0.2.12
- keras - version 3.8.0
- numpy - version 1.26.4
- pandas - version 2.2.2
- python -version 3.11.11
- matplotlib - verison 3.10.0
- PIL - verison 11.1.0

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by Upgrad IIIT Bangalore PG program on ML and AI.
- This project was based on Convolutional Neural Networks Tutorial of this course.


## Contact
Created by [pallabb2021] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
