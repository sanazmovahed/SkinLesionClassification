# SkinLesionClassification
Classification of Skin Lesions using Dermoscopy Images

In this repository, a model is made up from DenseNet201 as the pre-trained network. Here we freezed all layers of the model except last 200 layers. 
The used Dataset is task 3 of ISIC2018.

Used method to balancing this highly imbalanced dataset is hybrid method of oversampling and undersampling. 

All you need to run this code is to download the data from: https://challenge.isic-archive.com/data/#2018
