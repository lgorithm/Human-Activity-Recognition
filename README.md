# Human Activity Recognition Project

## Overview

This project aims to classify human activities using data from the UCI Human Activity Recognition (HAR) dataset. The project involves data preprocessing, machine learning model training, and deep learning model training to accurately recognize and predict human activities based on sensor data.

## Project Structure

The project is divided into three main parts:

1. **Data Preprocessing** (`EDA.ipynb`)
2. **Machine Learning Model Training** (`Machine_Learning_Training.ipynb`)
3. **Deep Learning Model Training** (`Deep_Learning_Training.ipynb`)

### Data Preprocessing

**Notebook**: `EDA.ipynb`

In this notebook, the UCI HAR Dataset is preprocessed to prepare it for machine learning and deep learning models. Key steps include:

- Loading the dataset
- Cleaning and transforming the data
- Exploratory data analysis (EDA) to understand the data distribution and feature relationships

### Machine Learning Model Training

**Notebook**: `Machine_Learning_Training.ipynb`

This notebook focuses on training machine learning models on the preprocessed data. Key steps include:

- Splitting the data into training and testing sets
- Training various machine learning models such as Decision Trees, Random Forest, and SVM
- Evaluating model performance using metrics like accuracy, precision, recall, and F1-score

### Deep Learning Model Training

**Notebook**: `Deep_Learning_Training.ipynb`

In this notebook, deep learning models are trained on the preprocessed data. Key steps include:

- Designing and building neural network architectures such as LSTM and GRU
- Training the neural networks on the dataset
- Evaluating model performance using metrics like accuracy and loss

## How to Run the Project

1. Clone the repository to your local machine.
    ```bash
    git clone https://github.com/your-username/Human-Activity-Recognition.git
    ```
2. Navigate to the project directory.
    ```bash
    cd Human-Activity-Recognition
    ```
3. Ensure you have the required Python packages installed. You can install them using:
    ```bash
    pip install -r requirements.txt
    ```
4. Open and run the Jupyter notebooks in the following order:
    - `EDA.ipynb` to preprocess the data
    - `Machine_Learning_Training.ipynb` to train and evaluate machine learning models
    - `Deep_Learning_Training.ipynb` to train and evaluate deep learning models

## Dataset

The UCI HAR Dataset used in this project can be found [here](https://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones).

## Results

The results of the project include trained models capable of accurately classifying human activities. The performance of these models is evaluated using appropriate metrics and visualized for comparison.

## Contributing

If you wish to contribute to this project, please fork the repository and submit a pull request. For major changes, please open an issue first to discuss what you would like to change.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

