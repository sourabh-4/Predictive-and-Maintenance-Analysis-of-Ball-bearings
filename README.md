
# Rolling Element Bearing Fault Detection

## Overview
This project focuses on the fault detection of rolling element bearings using machine learning models trained on vibration signal data. The notebook outlines the steps from data preprocessing, feature extraction, model training, to final evaluation.

## Data Description
The dataset used in this project consists of vibration signals measured from bearings. These signals are processed to extract relevant features that are critical for fault detection.

## Feature Extraction
The feature extraction process involves:
1. Reading vibration data.
2. Applying signal processing techniques to extract bearing frequencies.
3. Combining these frequencies with labels indicating the bearing's health status.

## Model Training and Evaluation
We utilize a RandomForestClassifier for model training. The process includes:
1. Splitting the data into training and test sets.
2. Training the classifier on the training set.
3. Evaluating the model on the test set using metrics such as accuracy and a confusion matrix.

## Results
The trained model demonstrates satisfactory performance, distinguishing between different health states of the bearings (e.g., early, normal, suspect, failure). The overall accuracy on the prediction set is approximately 90%.

## Usage
To run the project:
1. Ensure all Python dependencies are installed.
2. Execute the cells in the notebook in sequence, starting from data loading to the final evaluation.

## Dependencies
- Python 3.8+
- Pandas
- Numpy
- Scikit-learn
- Matplotlib

## Authors
- [Your Name]
- [Team Member's Name]

## License
This project is licensed under the MIT License - see the LICENSE.md file for details.
