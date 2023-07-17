# Fire-Detection

Our aim is to detect the presence of fire in any position of a given frame using a classification model. The model should determine whether each input frame contains fire or is normal. We will use a combined dataset from multiple sources on GitHub and Kaggle, consisting of two classes: fire and normal. We will prepare the data by combining the datasets, ensuring the two classes are present, and splitting the data into training and validation sets. Next, we will train the model on the training set and evaluate it on the validation set. 

The ConvNetX model achieved an impressive performance on this problem, with an accuracy of about 99.6%, compared to Densenet, which achieved an accuracy of 95.6%.

I want to know if the model can distinguish between the fire class and normal class and whether it is overfitting on the normal images. To test this, I passed both normal images and images of normal scenes with added fire effects through the model, and the model was able to predict them accurately

![Alt text](https://github.com/TmohamedashrafT/Fire-Detection/blob/main/normal.jpg)
![Alt text](https://github.com/TmohamedashrafT/Fire-Detection/blob/main/Fire.jpg)
