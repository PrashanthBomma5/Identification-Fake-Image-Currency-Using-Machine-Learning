Currency Recognition using CNN
This repository contains code for building and fine-tuning a convolutional neural network (CNN) model for recognizing different currencies using the FastAI library.

Dataset
The dataset used for training and testing the model is located in the /currency dataset directory. It consists of images of various currencies categorized into training and test sets.

Usage
Mount Google Drive: Make sure to mount your Google Drive containing the dataset using the provided code snippet in Google Colab.
python
Copy code
from google.colab import drive
drive.mount('/content/drive')
Install Dependencies: Install the necessary dependencies including FastAI library.
Data Loading: Load the dataset using FastAI's ImageDataLoaders class, specifying the path to the dataset directory and other parameters like batch size and transformation methods.
Model Training: Train a CNN model using the loaded dataset. In this repository, we utilize a pre-trained ResNet34 architecture.
Fine-tuning: Fine-tune the pre-trained model to improve its performance on the specific task of currency recognition. This involves training for a few epochs with a lower learning rate.
Interpretation: Interpret the results of the trained model using tools provided by FastAI, such as confusion matrix and visualization of top losses.
Results
The trained model achieves a certain level of accuracy and error rate on the test set, as visualized in the confusion matrix and top losses plots.

Contributions
Contributions to this repository are welcome! If you have any suggestions for improvements or would like to add new features, feel free to open an issue or submit a pull request.
