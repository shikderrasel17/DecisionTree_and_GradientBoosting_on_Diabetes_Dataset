# Decision Tree and Gradient Boosting on Diabetes Dataset

## Model Details
This repository contains implementations of Decision Tree and Gradient Boosting classifiers applied to the diabetes dataset. The models are trained to predict whether a patient is diabetic based on several health indicators.

## Intended Use
The primary purpose of this project is to demonstrate the use of Decision Tree and Gradient Boosting classifiers in a medical dataset for educational and research purposes.

## Data Source
The dataset used in this project is the Diabetes dataset, which consists of various medical predictor variables and one target variable, `Outcome`.

## Dataset Sample
| Pregnancies | Glucose | BloodPressure | SkinThickness | Insulin | BMI  | DiabetesPedigreeFunction | Age | Outcome |
|-------------|---------|---------------|---------------|---------|------|--------------------------|-----|---------|
| 6           | 148     | 72            | 35            | 0       | 33.6 | 0.627                    | 50  | 1       |
| 1           | 85      | 66            | 29            | 0       | 26.6 | 0.351                    | 31  | 0       |
| 8           | 183     | 64            | 0             | 0       | 23.3 | 0.672                    | 32  | 1       |
| 1           | 89      | 66            | 23            | 94      | 28.1 | 0.167                    | 21  | 0       |

## Training Data
- **Split**: 80% training, 20% testing
- **Features**: `Pregnancies`, `Glucose`, `BloodPressure`, `SkinThickness`, `Insulin`, `BMI`, `DiabetesPedigreeFunction`, `Age`
- **Target**: `Outcome`

## Test Data
- 20% of the dataset reserved for testing the models.

## Parameters
- **Decision Tree**: `random_state=42`
- **Gradient Boosting**: `random_state=42`

## Feature Importance
The importance of each feature in making predictions was analyzed, which can be visualized using tree plots and feature importance graphs.

## Metrics
- **Decision Tree Accuracy**: 0.7467
- **Gradient Boosting Accuracy**: 0.7467
- **Classification Report**:
  - Precision, recall, F1-score for each class
  - Macro and weighted averages

## How to Run
1. Load the dataset.
2. Split the data into training and testing sets.
3. Train the models using the provided code.
4. Evaluate and visualize the model performance.

## Additional Information
- Libraries used: `pandas`, `numpy`, `matplotlib`, `sklearn`
- Visualization includes decision trees and confusion matrices.

