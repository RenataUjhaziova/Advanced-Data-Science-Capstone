# IBM Advanced Data Science Capstone Project

In this Capstone project I decided to solve image classification task by using Watson Machine Learning. 
The task is to classify images with grape leaves diseases using different types of models. The given dataset contains 272 images which are labeled into 4 classes – dry, esca, healthy and mite classes.
I used Watson Studio environment for model creation, training and testing the models. Watson machine learning repository was used for deployment of these models.
The model_deployment_endpoint_url of the deployed model then can be used as REST API for scoring new images.

## Dataset

For this project I used dataset from the following link:
https://github.com/RenataUjhaziova/datasetWS_DvsEvsHvsM_512-512_git

This dataset contains images with healthy grape leaves and with three different kind of diseases: “Dry grape leaves diseases”, Esca, Grape erineum mite disease. 

The images were captured in one Vineyard in the South East of Slovakia and the dataset was prepared from these images. 
The dataset contains images for training set, test set and validation set. The number of images is equal for each class that’s why there was no need to solve issue with imbalanced dataset.

In this repository you can find:
- notebook with data exploratory phase
- notebooks for each model creation and deployment
- Lightweight_IBM Cloud_Garage_Method_for_DS_ADD_Ujhaziova.pdf
- AdvanceDataScienceCapstoneProject_Ujhaziova_final.pptx
