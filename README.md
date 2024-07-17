# Melanoma Detection Assignment
In the realm of cancer, there exist over 200 distinct forms, with melanoma standing out as the most lethal type of skin cancer among them. The diagnostic protocol for melanoma typically initiates with clinical screening, followed by dermoscopic analysis and histopathological examination. Early detection of melanoma skin cancer is pivotal, as it significantly enhances the chances of successful treatment. The initial step in diagnosing melanoma skin cancer involves visually inspecting the affected area of the skin. Dermatologists capture dermatoscopic images of the skin lesions using high-speed cameras, which yield diagnostic accuracies ranging from 65% to 80% for melanoma without supplementary technical assistance. Through further visual assessment by oncologists and dermatoscopic image analysis, the overall predictive accuracy of melanoma diagnosis can be elevated to 75% to 84%. The objective of the project is to construct an automated classification system leveraging image processing techniques to classify skin cancer based on images of skin lesions

Problem Statement:
To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution which can evaluate images and alert the dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
The dataset comprises 2357 images depicting malignant and benign oncological conditions, sourced from the International Skin Imaging Collaboration (ISIC). These images were categorized based on the classification provided by ISIC, with each subset containing an equal number of images.
In order to address the challenge of class imbalance, the Augmentor Python package (https://augmentor.readthedocs.io/en/master/) was employed to augment the dataset. This involved generating additional samples for all classes, ensuring that none of the classes had insufficient representation.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
The model is trained using the fit method with the specified number of epochs (epochs=30). The ModelCheckpoint and EarlyStopping callbacks are employed to monitor the validation accuracy during training. The ModelCheckpoint callback saves the model with the best validation accuracy, while the EarlyStopping callback stops training if the validation accuracy does not improve for a specified number of epochs (patience=5 in this case). These callbacks help prevent overfitting and ensure that the model converges to the best possible solution.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
Python
Matplotlib
Numpy
Pandas
Seaborn
Tensorflow

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
This project is a case study and the details for the case study is given by UpGrad.
references are taken from the study material of UpGrad.


## Contact
Created by [@githubusername] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
