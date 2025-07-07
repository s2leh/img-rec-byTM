# Hotdog vs Banana Image Classifier
This project uses a custom-trained AI model for image recognition, built using Teachable Machine to classify images as either Hotdog or Banana. The trained model is exported and used in a Python script with TensorFlow/Keras.

# Project Overview
Goal: Train a simple AI model to recognize whether an image is a hotdog or a banana.

# Tools Used:

Teachable Machine, TensorFlow, Keras, Python

# Model Training

The model was trained using Google's Teachable Machine with Two classes Hotdog and Banana, Images were uploaded manually for both classesExported the trained model as a TensorFlow (Keras) .h5 file

# Step 1:
Train the Model using Teachable Machine,Go to Teachable Machine Then Click on Image Project > Standard Image Model, Then Create two classes Hotdog and Banana or anything you want (i did't with Hotdog and Banana), Then Upload sample images for each class, Then Click on Train Model and wait for training to complete, after train finished, click Export Model, Then Choose TensorFlow > Keras (.h5) and download the model file (model.h5)

# Step 2:
Set Up Python Environment

i did't in anaconda

# Step 3:
Copy The Python Code From Teachable Machine, Then Create a Python script and paste the code

# Step 4:
Test the Model

Put ("keras_Model.h5") and ("labels.txt") and Pyhton script in the same folder, Place a sample image in the same folder

Run the script


