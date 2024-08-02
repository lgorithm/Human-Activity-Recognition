## Human Activity Recognition Project

This project aims to classify human activities using the UCI Human Activity Recognition (HAR) dataset. The project involves data analysis and preprocessing, machine learning model training using expert-generated 561 features, and deep learning model training using raw time series data to recognize and predict human activities based on sensor data accurately.


## Exploratory data analysis

Here, the UCI HAR Dataset is preprocessed and analyzed to understand the data distribution and feature relationships among 561 expert-generated features using different data visualization techniques including t-SNE to prepare it for machine learning and deep learning models.


## Machine Learning Model Training

This focuses on training classical machine learning models on the preprocessed data. Key steps include:

- Splitting the data into training and testing sets
- Training various machine learning models such as Logistic Regression, Decision Trees, Random Forest, and SVM
- Evaluating model performance using metrics like accuracy, loss, Confusion Matrix, etc.

## Deep Learning Model Training

Here deep learning models are trained on the preprocessed raw time series data. Key steps include:

- Designing and building neural network architectures such as LSTM and GRU
- Training the neural networks on the dataset
- Evaluating model performance using metrics like accuracy, loss, Confusion Matrix, etc.

## How to Run the Project

1. Clone the repository to your local machine.
    ```bash
    git clone https://github.com/lgorithm/Human-Activity-Recognition.git
    ```
2. Navigate to the project directory.
    ```bash
    cd Human-Activity-Recognition
    ```
3. Open and run the Jupyter notebooks in the following order:
    - `EDA.ipynb` to preprocess and analysis the data
    - `Machine_Learning_Training.ipynb` to train and evaluate machine learning models
    - `Deep_Learning_Training.ipynb` to train and evaluate deep learning models

## Dataset

### Description

The UCI HAR Dataset was created by Jorge L. Reyes-Ortiz, Davide Anguita, Alessandro Ghio, Luca Oneto, and Xavier Parra. The experiments have been carried out with a group of 30 volunteers within an age bracket of 19-48 years. Each person performed six activities (WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, LAYING) wearing a smartphone (Samsung Galaxy S II) on the waist. Using its embedded accelerometer and gyroscope, 3-axial linear acceleration and 3-axial angular velocity were captured at a constant rate of 50Hz.

The sensor signals (accelerometer and gyroscope) were pre-processed by applying noise filters and then sampled in fixed-width sliding windows of 2.56 sec and 50% overlap (128 readings/window). From each window, a vector of features was obtained by calculating variables from the time and frequency domain.

### More Information

For more details about this dataset, please refer to the original authors' publication:

Davide Anguita, Alessandro Ghio, Luca Oneto, Xavier Parra, and Jorge L. Reyes-Ortiz. A Public Domain Dataset for Human Activity Recognition Using Smartphones. 21th European Symposium on Artificial Neural Networks, Computational Intelligence and Machine Learning, ESANN 2013. Bruges, Belgium 24-26 April 2013.

## Results

The results of the project include trained models capable of accurately classifying human activities. The performance of these models is evaluated using appropriate metrics and visualized for comparison.

