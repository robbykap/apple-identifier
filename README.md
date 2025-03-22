# Apple Identification
BYU CS 474 Final Project - Model to identify different apple species 


## Objective 
The objective of this project is to develop a deep neural network (DNN) capable of accurately classifying different types of apples. This project aims to contribute to agricultural technology by providing a model that can assist in fruit sorting and quality assessment. If time permits, the project will be extended to detect the ripeness of apples based on their visual characteristics. Ripeness detection could further improve the efficiency of apple sorting and ensure better quality control.


## Dataset
For my data set I will be using the kaggle data set Fruits-360 which can be found [here](https://www.kaggle.com/datasets/moltean/fruits). It contains over 90000 images of 141 different fruits, vegetables, and nuts. For my project I will be focusing on a subset of the data which would be the different types of apples which they have as, Crimson Snow, Golden, Golden-Red, Granny Smith, Pink Lady, Red, and Red Delicious. I will need to clean up the dataset to make sure I am correctly training on the different types of apples, and not other fruits, veggies, or nuts. It looks like the training and test datasets are already split but I will also keep in mind that additional pictures of apples may be required which I can get from pictures online or from personal pictures I can take at the store, and so on. From my research I discovered there are also datasets of varying quality of apples I can use once I have a model that can detect different types of apples then detect varying quality of apples if time permits. 

## Model
The model itself will be developed using a convolutional neural network (CNN) to extract features and classify apples. Supervised learning techniques will be used to train the network, and hyperparameter tuning will be performed to optimize accuracy. Regularization methods will also be applied to prevent overfitting and improve model generalization. Once training is complete, the model will be evaluated using accuracy, precision, recall, and F1-score. A validation set will be used to fine-tune performance before testing the model on unseen data.

## Measure of Success
The primary measure of success will be achieving an accuracy of at least 85% in apple classification. The model should successfully differentiate between multiple apple types with minimal misclassification. If time allows, I will extend the project to include ripeness detection by analyzing color, texture, and other visual cues. This extension will involve additional data collection and model modifications to detect subtle differences in apple ripeness levels.

## Future Work
If time permits, I will explore the following areas for future work:
1. Ripeness detection: Extend the model to classify apples based on ripeness levels.
2. Quality assessment: Develop a model to evaluate the quality of apples based on visual characteristics.
3. Why: Show what characteristics are important for the model to classify apples. Such as color, shape, and texture.

## Time Log
Log of time spent on this project and descriptions of completed tasks can be found [here](time_log.md).