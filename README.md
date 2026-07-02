# Disease-Prediction-Using-Machine-Learning
This project predicts the likelihood of three diseases—Heart Disease, Diabetes, and Lung Cancer—using four machine learning models: Linear Regression, Support Vector Machine (SVM), K-Nearest Neighbors (KNN), and Decision Tree. The SVM model has shown the highest accuracy in our predictions.

Table of Contents
- [Project Overview](#project-overview)
- [Models Used](#models-used)
- [Datasets](#datasets)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Project Overview
This project applies machine learning techniques to predict the risk of common diseases. We trained and tested four models on healthcare datasets to predict the presence of heart disease, diabetes, and lung cancer. Among the models used, the SVM model yielded the highest accuracy across all disease predictions.

## Models Used
- **Logistic Regression**: Applied for prediction but not very effective for classification.
- **Support Vector Machine (SVM)**: Best-performing model with the highest accuracy.
- **K-Nearest Neighbors (KNN)**: A simple algorithm, generally effective but less accurate in our case.
- **Decision Tree**: Good for interpretability but prone to overfitting.

## Datasets
- **Heart Disease Dataset**: Contains features like age, cholesterol, blood pressure, etc.
- **Diabetes Dataset**: Includes features such as glucose level, BMI, age, etc.
- **Lung Cancer Dataset**: Features include smoking habits, age, family history, etc.

These datasets were sourced from publicly available healthcare data repositories such as Kaggle or UCI Machine Learning Repository.

## Installation
To run this project, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/disease-prediction.git
    cd disease-prediction
    ```

2. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Download the datasets and place them in the `data` directory.

## Usage
**Training the Models, Prediction, Evaluation **: 
    Run the `diabities_prediction.ipynb`, 'heart_disease_prediction.ipynb', 'lung_cancer_prediction.ipynb' script to train all four models on the datasets.
    ```bash
    python train.py
    ```

## Results
- **Best Model**: Support Vector Machine (SVM)
- **Accuracy**: 
  - Heart Disease: 83%
  - Diabetes: 75.32%
  - Lung Cancer: 97.84%

Other models such as Linear Regression, KNN, and Decision Tree showed lower accuracy but were still useful for comparison.

## Contributing
If you'd like to contribute to this project, feel free to submit a pull request or open an issue.

## License
This project is licensed under the MIT License.

## Research Paper
[https://ijisrt.com/unlocking-healthcare-insights-disease-prediction-with-machine-learning](https://ijisrt.com/unlocking-healthcare-insights-disease-prediction-with-machine-learning)
