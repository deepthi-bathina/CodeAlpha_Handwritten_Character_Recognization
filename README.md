# Handwritten Character Recognization System

A handwritten character recognition system involves developing a system that can accurately identify and classify handwritten characters from images. In this project i have used Random classifier model. A handwritten character recognition project combines aspects of data science, machine learning, and computer vision to create a system capable of interpreting and understanding human handwriting.Here are the steps i have used to develop a handwritten character recognition system -

Step-1: Import necessary libraries for data handling, visualization, image processing, and machine learning.

Step-2: Mount Google Drive to access the dataset stored there.

Step-3: Read the dataset from the CSV file into a Pandas DataFrame.

Step-4: Display basic information, statistical summary, and first few rows of the dataset.

Step-5: Plot sample images from the dataset for each class using a subplot grid.

Step-6: Define a function to detect identical borders in the images to facilitate cropping.

Step-7: Apply the border detection function across the dataset and calculate mean borders.

Step-8: Reshape data into 3D matrices, crop images using the detected borders, and smooth the images.

Step-9: Flatten the cropped images back into vectors and combine them with their labels.

Step-10: Convert the processed data back into a DataFrame format.

Step-11: Display the shape, information, statistical summary, and first few rows of the processed dataset.

Step-12: Plot sample images from the processed dataset for each class using a subplot grid.

Step-13: Split the dataset into training and testing sets.

Step-14: Apply standard scaling to the training and testing datasets.

Step-15: Initialize and train a RandomForestClassifier using the training data.

Step-16: Calculate and print the accuracy of the classifier on the test data.

Step-17: Predict test labels, generate a confusion matrix, and visualize it using a heatmap.

Step-18: Extract feature importances from the classifier, sort them, and plot the sorted feature importances.
