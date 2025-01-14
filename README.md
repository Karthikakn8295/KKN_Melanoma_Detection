# Melanoma Detection Assignment
CNN based model is built which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.
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

Technologies Used:
- Python
- Tensor flow
- Pandas
- Numpy
- Keras
- Image Generalization
- Augmentor

Conclusions:
- The accuracies were very low for both training and validation sets before using Augmenor function.
- The Augmentator function helped in rebalancing the classes.
- The training and validation accuracies have increased significantly showing the model has ebcome more robust in handling noise.
- The issue of overfitting has gone as seen by the slight difference in the training and validation accuracies.
- Augmentor allows targeted augmentation for underrepresented classes in training dataset. This helps balance the class distribution, improving the model's performance on minority classes.
- By incorporating Augmentor into the preprocessing pipeline, the diversity and quality of the training dataset has enhanced,thus leading to better performance and robustness of the neural network model.

  Project Done by: Karthika K Namboothiri

[ ]




