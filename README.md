# Project Name
> Melanoma Detection Assignment - Case Study.


## Table of Contents
* Problem Statement: To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis
* Technologies Used: Convolutional Neural Network using TensorFlow to build multi-class classification model 
* Conclusions: Jupyter notebook (bappi_banik_nn.ipynb runtime Google Collab) contains following steps to build  multi-class classification model using custom Convolutional Neural Network (CNN) using TensorFlow
    1. Reading Train & Test dataset (Google Drive location) and displaying number of images 
    2. Preparing Dataset using batch size 32
    3. Visualizing data
    4. Create and compile model
    5. Train the Model (After few iterations google collab taking ages to train the model)
    6. Visualizing Training Results 
    7. Finding distribution of classes for class imbalaces 
    8. Handling Class Imbalace using Augmentor 
    9. Model building and training on rectified class imbalance data
        -  Create a CNN model, which can accurately detect 9 classes present in the dataset
        -  Choose an appropriate optimiser and loss function for model training
        -  Train the model for ~50 epochs
        


<!-- You can include any other section that is pertinent to your problem -->

## General Information
- General Information about Project: Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis
- Project Background: 
- Business Probem Statement: To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early.
- Dataset used: Dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC.
    Dataset contains below diseases
    Actinic keratosis
    Basal cell carcinoma
    Dermatofibroma
    Melanoma
    Nevus
    Pigmented benign keratosis
    Seborrheic keratosis
    Squamous cell carcinoma
    Vascular lesion

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Conclusion 1 from the analysis
Vaildation Accuracy: ~ 50-60% due to engough features to remember the pattern. Neural Network is based on 20 epochs so learning is just started
Initial Findings: Model is overfitting compare to loss function. Loss Function between training and validation around 19-20th epoch
- Conclusion 2 from the analysis
Overfitting issue has been addressed due to data augmentation
However model is trained on 20 epochs, which don't infer proper conclusion
- Conclusion 3 from the analysis
    - seborrheic keratosis class has the least number of samples
    - pigmented benign keratosis classes having the highest proportionate in terms number of samples
- Conclusion 4 from the analysis



<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- library - version 1.0
- library - version 2.0
- library - version 3.0

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by...
- References if any...
- This project was based on [this tutorial](https://www.example.com).


## Contact
Created by @bappib - feel free to contact me

## Notes 
Google Collab notebook times-out and takes ages to build & train model. Could not get output of Model Training and subsequent execution of code output like Visualising Model Training results, Class Imbalance distribution SNS barplot etc. due to running out of GPU in google Collab

<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->