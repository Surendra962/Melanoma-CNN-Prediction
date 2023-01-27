# Project Name
> Outline a brief description of your project.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Project: To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths.
- Background: Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. Early detection of melanoma is critical to saving lives. However, it is difficult for dermatologists to detect melanoma because it can be difficult to distinguish from other benign skin lesions. In this project, we will build a CNN based model which can accurately detect melanoma.

The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant. The data set contains the following diseases:

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
The first model is a simple model with an accuracy of 0.9156 and a validation loss of 8.9194, with a validation accuracy of 0.2881. The second model has an accuracy of 0.8687, a validation loss of 5.8075 and a validation accuracy of 0.3644. The third model, however, has a high accuracy of 0.9583, a low validation loss of 0.6555 and a high validation accuracy of 0.8352.

It appears that the simple model performed poorly, with a low validation accuracy, indicating that the model is not able to generalize well from the training data. On the other hand, the second model, which used dropout, showed an improvement over the first model. But the third model which used dropout and class rebalancing performed significantly better in terms of accuracy, validation loss and validation accuracy.

It is important to note that the use of dropout is a regularization technique that aims to prevent overfitting by randomly dropping a percentage of neurons during training. And class rebalancing is a method used to mitigate the problem of class imbalance. These techniques can help to improve the generalization ability of the model and increase its performance on unseen data.

In conclusion, the third model, which used both dropout and class rebalancing, performed the best among the three models. It achieved a high accuracy, low validation loss, and high validation accuracy, indicating that the model has learned effectively from the training data and is able to generalize well to unseen data.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
1. tensorflow
2. keras
3. Augmentor
4. glob and other python library
<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
this project is inspired by Upgrad's ML course
