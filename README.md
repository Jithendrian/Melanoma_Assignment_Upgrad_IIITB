#  Melanoma Detection Assignment


  

##  To build a multiclass classification model using a custom convolutional neural network in TensorFlow.

  

##  Table of Contents

* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)
* [Miscellaneous](#miscellaneous)

##  General Information

### Problem statement: 

To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

### Dataset

The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.

The data set contains the following diseases:

- Actinic keratosis
- Basal cell carcinoma
- Dermatofibroma
- Melanoma
- Nevus
- Pigmented benign keratosis
- Seborrheic keratosis
- Squamous cell carcinoma
- Vascular lesion


## Steps for solving the problem

- Data Reading/Data Understanding
- Dataset creation
- Dataset visualisation
- Model Building & training
- Data augmentation
- Again Model Building & training for augmented data
- Class distribution
- Handling class imbalances
- Again Model Building & training on the corrected balanced data
- Analysis on test data  

## Technologies Used

- Tensorflow
- Python
- Numpy
- Pandas
- Matplotlib  
  

##  Conclusion
- Accuracy on training data has increased by using Augmentor library
- Model is still overfitting
- The problem of overfitting can be solved by add more layer,neurons or adding dropout layers.
- The Model can be further improved by tuning the hyperparameter

- Augmentation process helps to increase the accuracy of the training data
- Model can be improved further using various hyper parameters
- Overfitting can be solved by adding more layers and dropouts


##  Contact

  
- Created by [@jithendrian] (https://github.com/Jithendrian/AdvancedRegression) 

- jithendrian@gmail.com 
- Assignment
    - Main folder : https://github.com/Jithendrian/AdvancedRegression
    - Python/ ipynb : https://github.com/Jithendrian/AdvancedRegression/blob/main/AdvancedRegression.ipynb
