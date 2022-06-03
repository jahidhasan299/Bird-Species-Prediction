# Bird-Species-Prediction:
In this project we will create a Convolutional Neural Network which will be able to predict species of the bird. We will use different layers and other hyperparameters for building, training and testing this multiclass classifictaion model. We will be using keras for this project.
# Step to run application: 
1. Step: Create the copy of the project. 
2. Step: Open command prompt and change your current path to folder where you can find 'app.py' file. 
3. Step: Create environment by command given below- conda create -name 
4. Step: Activate environment by command as follows- conda activate 
5. Step: Use command below to install required dependencies- python -m pip install -r requirements.txt 
6. Step: Run application by command; python app.py You will get url copy it and paste in browser. 
7. Step: You have sample_data folder where you can get images to test.

# THE STEPS ARE TAKEN TO COMPLETE THIS PROBLEM
1. Mounting google drive on colab notebook
2. Visualizing the image that we will be working on
3. Analyzing the dimensions to verify if all images have same dimensions.
4. Converting the images into a numpy array and normilize them.
5. Checking class imbalance
6. Spliting the data and performing one-hot encoding
7. Creating the model architecture, compliling the mode and fit it.
8. Plotting the accuracy and loss against each epoch.
9. Preprocessing the test data and make predicting onit.
10. Visualizing the orginal and predicted labels for the test images

# Usefull of this Project
This project can be used for educational purposes to get a better understanding of how create network architectute for a CNN model. You can further hyperparameter tune this model to reach higher accuracy. It can be used by bird sanctuaries to indetify differnt types of birds.

# Conclusion:
We started with loading the dataset into google colab using google drive and visualizing the images. Normalizing is an important step when working with any type of dataset. After that we created a CNN Model which is further used for predicting the bird species using the image supplied to model.

# Scope:
This project can be used for educational purposes to get a better understanding of how to create network architecture for a CNN model. You can further hyper parameter tune this model to reach a higher accuracy. It can be used by bird sanctuaries to identify different types of birds.

# Result
![Screen Shot 2022-06-03 at 3 30 22 PM](https://user-images.githubusercontent.com/49092540/171808526-d84f1878-b74b-4dab-a526-db6431bc24fc.png)
