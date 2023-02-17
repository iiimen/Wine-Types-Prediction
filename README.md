# Wine Type Detection with Deep Learning
This project uses deep learning to classify white and red wines based on their physicochemical characteristics.


## <b>Table of Contents</b>
1. Dataset<br>
2. Methods<br>
3. Usage <br>
4. Concluion



## <b>1. Dataset</b>

The data set used for this project is sourced from the UCI Machine Learning Repository, which can be found at the following links:

<h3>&#x2022; http://archive.ics.uci.edu/ml/machine-learning-databases/wine-quality/winequality-white.csv
<h3>&#x2022; http://archive.ics.uci.edu/ml/machine-learning-databases/wine-quality/winequality-red.cs<h3>&#x2022;

The data set contains physicochemical measurements of two types of wines - white and red. There are 11 input variables that describe the properties of the wines and 1 output variable that classifies the wines as either "white" or "red". There are 4,898 white wine samples and 1,599 red wine samples in the data set.


## <b>2. Methods</b>
For this project, we used a deep neural network to classify the wines based on their physicochemical characteristics. The neural network architecture consists of the following layers:

1. Input layer with 12 nodes
2. Two hidden layers with 9 and 7 nodes respectively
3. Output layer with 1 node and sigmoid activation function


## <b>3. Usage</b>
To reproduce the results of this project, you can follow the steps below:

Download the winequality-white.csv and winequality-red.csv files from the UCI Machine Learning Repository links provided above.
Run the wine_type_detection.ipynb notebook using Jupyter or any other suitable environment.
Follow the instructions in the notebook to preprocess the data and train the deep neural network.
Once trained, the notebook will output the accuracy of the model on the test set and provide sample predictions.

## <b>4. Conclution</b>
In this project, we used a deep neural network to classify white and red wines based on their physicochemical characteristics. The model achieved an accuracy of 0.98 on the test set, demonstrating the effectiveness of deep learning in classifying complex data.
