# Dogs-vs-Cats-DL-training

Cat and Dog Image Classification
This project implements a Convolutional Neural Network (CNN) to classify images of cats and dogs.

# Dataset
```The dataset used in this project is the "Cats vs. Dogs" dataset from Kaggle, which can be downloaded from the following link: https://download.microsoft.com/download/3/e/1/3e1c3f21-ecdb-4869-8368-6deba77b919f/kagglecatsanddogs_5340.zip```

The dataset contains images of cats and dogs organized into two folders: "Cat" and "Dog".


Project Structure
The project consists of the following steps:

Import necessary libraries: Import libraries for data manipulation, visualization, and building the CNN model.
Download and Unzip Dataset: Download and extract the dataset from the provided URL.
Create Dataframe: Create a pandas DataFrame with image paths and corresponding labels (0 for Cat, 1 for Dog).
Data Cleaning: Remove corrupted or invalid image files from the dataset.
Exploratory Data Analysis (EDA): Visualize sample images from both classes and check the class distribution.
Data Preprocessing: Split the data into training and testing sets and perform data augmentation on the training set using ImageDataGenerator.
Model Creation: Build a Sequential CNN model with Conv2D, MaxPooling2D, Flatten, and Dense layers.
Model Compilation: Compile the model with the Adam optimizer, binary crossentropy loss, and accuracy metric.
Model Training: Train the CNN model on the prepared training data and validate it on the validation data.
Visualization of Results: Plot the training and validation accuracy and loss over epochs to evaluate the model's performance.
# Requirements
- Python 3.x
- TensorFlow
- Keras
- Pandas
- Numpy
- Matplotlib
- Seaborn
- Pillow
How to Run
Clone the repository (if applicable) or download the notebook.
Ensure you have the required libraries installed. You can install them using pip:
