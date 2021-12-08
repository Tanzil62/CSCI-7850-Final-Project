# CSCI-7850-Final-Project
In this project, my goal was to develop a deep learning based computer vision model that can classify images from Large-scale CelebFaces Attributes (CelebA) Dataset based on the facial features of an image. I have used an advanced Convolutional Neural Network (CNN) model which is known as AlexNet. AlexNet architecture was able to successfully classify all the 40 facial attributes such as gender, young, smiling, eye glasses, bald, big lips, big nose, big hair, and so on from different images. I have also compared the performance of my proposed model with other classification models and my proposed classification model has outperformed those models to classify most of the facial attributes.

In this experiment, I have tested the AlexNet implementation on the CelebA dataset of images.  To train and test the AlexNet, I have used 20,000 of the 202,599 images available in the CelebA dataset with 16,000 for training and 4,000 for testing. I have used a batch size of 64 and trained the model for 100 epochs. My goal was to test the 40 face attribute labels on our AlexNet implementation and record the results.  I have used Keras to implement the model and Pandas to store the data in a data frame format.  I have tested the AlexNet model on each of the 40 face attribute labels in which I have used the images as input and the face attribute labels as output targets.  

I have shown a demo using jupyter notebook. I have data folder where I have stored images and the csv file. I have used jupyter notebook and checked my model with 800 images. I got around 91% accuracy to check whether a person is male or female.   

Here is the link of the Github repository: https://github.com/Tanzil62/CSCI-7850-Final-Project
