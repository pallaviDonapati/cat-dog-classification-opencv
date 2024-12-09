# cat-dog-classification-opencv-

Project Description:
The Cat vs. Dog Image Classification project focuses on building a machine learning model to classify images of cats and dogs using a dataset containing labeled images of both animals. The project involves data preprocessing, feature extraction, and training classifiers such as SVM, Decision Trees, and Random Forest to accurately categorize the images.

Data Preprocessing:
Loading the Dataset: The dataset is divided into two categories, cat and dog, and consists of image files stored in respective subfolders. The images are loaded and preprocessed to ensure consistency.
Data Inspection and Visualization:
The number of cat and dog images are counted and visualized using bar plots and pie charts.
Sample images from both categories are displayed to inspect the data visually.
Image Resizing: Images are resized to a fixed dimension (256x256) to standardize input size for the classifiers.
Model Development:
Feature Extraction:
Images are flattened into 1D arrays and normalized by scaling pixel values to the range [0, 1].
The dataset is split into training and testing sets, with an 80/20 ratio.
Classifier Training:
SVM (Support Vector Machine), Decision Trees, and Random Forest classifiers are trained on the preprocessed image data.
Each model is evaluated based on accuracy, F1 score, precision, recall, and confusion matrix.
Model Evaluation:
The accuracy of each classifier is calculated, and detailed metrics (precision, recall, F1 score) are provided to compare the performance of different models.
