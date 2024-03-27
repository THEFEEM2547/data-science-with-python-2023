# Data Science with Python 2023
---
* Tool
    * Anaconda
    * Jupyter lab

* Installation
    * Python v.3
    * Python libraries:
        * Numpy as np.
        * Pandas.
        * Matplotlib.
        * Tensorflow.
        * Os.

* purpose
    * We can use an alarm system that can call the nearest police station in case of an accident and also alert them of the severity of the accident.

### 1.In general, this code segment is prepared for use in machine learning or deep learning, as it includes the necessary library imports for data manipulation, management, and model creation.
![Car Sales Report](https://github.com/THEFEEM2547/data-science-with-python-2023/blob/main/Image/Screenshot%202024-03-27%20174707.png)

### 2.The code that assigns values to these variables may be used in a Convolutional Neural Network (CNN) model for image classification.
![Car Sales Report](https://github.com/THEFEEM2547/data-science-with-python-2023/blob/main/Image/Screenshot%202024-03-27%20174728.png)

### 3. This code will load images from the directory 'data/train', randomly split the data according to the seed value of 42, resize the images to 250x250 pixels, and group the images into batches of 100 for use in training mode.
![Car Sales Report](https://github.com/THEFEEM2547/data-science-with-python-2023/blob/main/Image/Screenshot%202024-03-27%20174751.png)

### 4.loading validation dataset
![Car Sales Report](https://github.com/THEFEEM2547/data-science-with-python-2023/blob/main/Image/Screenshot%202024-03-27%20174814.png)

### 5.This code retrieves all class names from the training data set and stores them in the variable class_names.
![Car Sales Report](https://github.com/THEFEEM2547/data-science-with-python-2023/blob/main/Image/Screenshot%202024-03-27%20174909.png)

### 6.This code helps improve the performance of the dataset by using automatic caching and prefetching techniques, which result in reducing data loading time and accelerating training speed.
![Car Sales Report](https://github.com/THEFEEM2547/data-science-with-python-2023/blob/main/Image/Screenshot%202024-03-27%20174924.png)

### 7.This code builds a CNN model with multiple sets of convolutional and pooling layers. Its purpose is to extract features from images, then convert the data into vectors, and use fully-connected layers for classification to correctly classify images into classes.
![Car Sales Report](https://github.com/THEFEEM2547/data-science-with-python-2023/blob/main/Image/Screenshot%202024-03-27%20174953.png)

### 8.This code defines the shape of the input data and displays details of the model structure to aid understanding of how the model works, including the number of parameters and the shape of the data used in each layer.
![Car Sales Report](https://github.com/THEFEEM2547/data-science-with-python-2023/blob/main/Image/Screenshot%202024-03-27%20175012.png)

### 9.The plot_model function is a tool for inspecting and visualizing the architecture of artificial neural network models, particularly small to medium-sized models.
![Car Sales Report](https://github.com/THEFEEM2547/data-science-with-python-2023/blob/main/Image/Screenshot%202024-03-27%20175035.png)

### 10.This code uses the ModelCheckpoint callback to save the weights of the most efficient model on the validation dataset during training. This enables you to use those weights for further usage later on.
![Car Sales Report](https://github.com/THEFEEM2547/data-science-with-python-2023/blob/main/Image/Screenshot%202024-03-27%20175055.png)

### 11.This code helps save the CNN model created into a JSON file.
![Car Sales Report](https://github.com/THEFEEM2547/data-science-with-python-2023/blob/main/Image/Screenshot%202024-03-27%20175113.png)

### 12.This code is a technique for diagnosing the training results of a model by plotting loss and accuracy curves.
![Car Sales Report](https://github.com/THEFEEM2547/data-science-with-python-2023/blob/main/Image/Screenshot%202024-03-27%20175130.png)

### 13.Code Summary: Test the model on the testing dataset and display sample images.

* 1.Variables preparation: Create a list named AccuracyVector to store success data for each image.

* 2.Matplotlib figure preparation: Create a figure in Matplotlib with a size of 30x30 for visualization.

* 3.loop through a dataset:

   * Pull image sets and labels from the testing dataset using testing_data.take (1), which will retrieve the first set of data containing 40 images.
   * Use the model to predict results with this image group using model.predict(images)
   * Convert the prediction results from the model into the format of class name (predlabel) and class index (prdlbl).
   * Compare the results from the model (prdlbl) with the correct labels and store the results in the AccuracyVector list.
   * "Loop through 40 images with their prediction and correct labels: Create subplots for each image Display the images using plt.imshow Display the correct prediction and label in the title of 
     each image Turn off axis coordinates (plt.axis('off')) and show grid (plt.grid(True)

### purpose:
   * Testing the model on images from the testing dataset to see if the model can predict the results accurately or not.
   * Displaying sample images along with prediction data to illustrate the overall performance of the model and understand potential issues the model may encounter, such as inaccuracies in certain cases.

![Car Sales Report](https://github.com/THEFEEM2547/data-science-with-python-2023/blob/main/Image/Screenshot%202024-03-27%20175219.png)
