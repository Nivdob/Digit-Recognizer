# Digit Recognizer
By: Niv Dobzinski (PhD)

This repository contains a complete solution for the Kaggle competition "Digit Recognizer" using Convolutional Neural Networks (CNNs) with TensorFlow and Keras. The solution includes data preprocessing, data augmentation, hyperparameter tuning, model training, evaluation, and submission preparation.

## Key Steps in the Process:
### Data Preprocessing:
- Handling missing values.
- Normalizing pixel values.
- Reshaping data for model input.
- One-hot encoding labels.

### Model Training:
- Splitting the data into training and validation sets.
- Hyperparameter tuning using Keras Tuner.
- Training the CNN model with the best hyperparametersl.

### Model Evaluation:
- Evaluating the model.
- Generating a confusion matrix and visualizing training/validation accuracy and loss.

### Prediction and Submission:
- Making predictions on the test dataset.
- Preparing and saving the submission file for Kaggle.

## Files in the Repository:
- `train.csv`: Training dataset.
- `test.csv`: Test dataset.
- `digit_recognizer_notebook.ipynb`: Jupyter notebook containing the full solution.

## How to Use:
1. Clone the repository.
2. Ensure all dependencies are installed (numpy, pandas, tensorflow, keras, keras_tuner, matplotlib, seaborn).
3. Adjust file paths.
4. Run the Jupyter notebook to reproduce the solution and generate predictions for the Digit Recognizer dataset.


- **Kaggle Competition Accuracy Score:** 0.99046

- **Public Leaderboard Score:** Top 24%

![Kaggle Score](Kaggle_compatition_score.png)