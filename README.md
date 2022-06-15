
# Melanoma Detection Assignment


## Table of Contents
* [General Info](#general-information)
* [Scope](#Scope)
* [Conclusions](#conclusions)
* [Contact](#Contact)

## General Information
Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis. 

## Scope
The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.
The data set contains the following diseases:

Actinic keratosis
Basal cell carcinoma
Dermatofibroma
Melanoma
Nevus
Pigmented benign keratosis
Seborrheic keratosis
Squamous cell carcinoma
Vascular lesion

## Conclusions
Following CNN Models were created. Considering the model performance(including loss), Model 3 looks like a reasonably consistent model and can be used for detection.

Model 1 Base Model -- Accuracy: Train = 76% and Validation = 51%

Model 2 With Dropouts and Data Augmentation -- Accuracy: Train = 54% and Validation = 51%

Model 3 With Augementated data and aclass imbalance rectification -- Accuracy: Train = 89% and Validation = 81%

## Contact
Created by Nilit Tinna - feel free to contact me!
