# UAV MT-DNN Implementation

## Project Title
Multi-Task Deep Neural Network for Emergency Message Priority
and Semantic-Loss Tolerance Prediction in UAV Networks

## Objective
To simultaneously predict message priority and semantic-loss
tolerance using UAV communication features.

## Dataset
FANET Dataset: UAV Communication Scenarios in NS-3.40

Dataset Size: 12,339 records and 25 columns.

Dataset Source:
https://zenodo.org/records/19373220

## Technologies Used
- Python
- Google Colab
- TensorFlow / Keras
- Pandas and NumPy
- Scikit-learn
- XGBoost
- Matplotlib and Seaborn

## Implementation
1. Load the FANET dataset.
2. Perform data preprocessing.
3. Derive project-specific target labels.
4. Split the dataset into training and testing sets.
5. Build and train the MT-DNN model.
6. Predict message priority and semantic-loss tolerance.
7. Evaluate the model using classification metrics.
8. Compare priority classification with baseline models.

## Output
- Message Priority: Low, Medium, High
- Semantic-Loss Tolerance: Low, High
- Accuracy, Precision, Recall, F1-score
- Confusion Matrices
- Model Comparison

## How to Run
1. Open the implementation notebook in Google Colab.
2. Download the FANET dataset from the source above.
3. Upload the Scenario 1 ML-ready CSV to Colab.
4. Update the dataset path if necessary.
5. Run all cells.

## Important Note
The target labels are project-defined proxies derived from
link lifetime and SNR measurements in the FANET dataset.
