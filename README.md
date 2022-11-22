# intel-image-classification
In this project, I worked on classification of intel images, i.e images of buildings, forest, street, etc. 

To solve this problem, I built a convolutional neural network and train it on these images. This is a multi-class classification problem and we will use keras. 

## Steps
1. Mounting google drive on collab notebook. 
2. Visualizing the images we will be working on.
3. Analyzing the dimensions to verify if all images have same dimensions. 
4. Converting the images into a numpy array and normalize them. 
5. Checking class imbalance. 
6. Splitting the data and performing one hot encoding.
7. Creating the model architecture, compiling the model and then fitting it. 
8. Plotting the accuracy and loss aginst each epoch. 
9. Preprocessing the test data and make predictions on it.
10. Visualize the original and predicted labels for the test images. 

## Scope
This project can be used for educational purposes to get a better understanding of how to create a network architecture for a CNN model. We can further tune the hyperparameters of this model to reach higher accuracy. 

This project has a vast scope, it can be used to classify satellite images, drone images, google images into different classes like sea, mountain, etc.

## Model Accuracy
![image](https://user-images.githubusercontent.com/50231750/203336275-b3b8dac4-3018-403d-9e0d-3ef899d1308e.png)

## Model Loss
![image](https://user-images.githubusercontent.com/50231750/203336321-fbe1b24b-4a5e-4615-89b5-c940bcc6137e.png)

## Prediction
![image](https://user-images.githubusercontent.com/50231750/203336446-f46b9a4e-383e-46c9-888e-093fddd83ceb.png)

## Interface
![Screenshot from 2022-11-22 17-17-29](https://user-images.githubusercontent.com/50231750/203338799-32f6b609-b261-46a7-a79c-cb64106d567a.png)

## Upload Image
![Screenshot from 2022-11-22 17-17-43](https://user-images.githubusercontent.com/50231750/203339114-57b583dc-652a-413a-b3f9-20481cbe0a2e.png)

## Output
![Screenshot from 2022-11-22 17-17-53](https://user-images.githubusercontent.com/50231750/203339179-f910bef9-b552-4ec0-bed8-2cfb4b5504dd.png)

![Screenshot from 2022-11-22 17-18-47](https://user-images.githubusercontent.com/50231750/203339253-a9a9aa67-9ea3-480f-8a15-5f9a7c2ed013.png)



## Conclusion
In this project we saw how we can create a CNN using different layers. Normalizing is an important step when working with any type of dataset. We will use this model to predict the class of the image supplied to the model.
