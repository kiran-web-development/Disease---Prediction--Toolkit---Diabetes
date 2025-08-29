# Disease Prediction Toolkit: Building and Evaluating ML Models

**Author:** M. Kiran Kumar

**Company:** devtown

## Description

This project is a toolkit for building and evaluating various machine learning models for disease prediction. It uses a Jupyter Notebook to go through the complete pipeline of data loading, preprocessing, model training, evaluation, and result visualization.

This project was completed as part of the 'Disease Predictor : Save lives With AI Bootcamp in 5 Days FREE Bootcamp'.

## Dataset

The project uses the `diabetes.csv` dataset. This dataset is used to predict whether or not a patient has diabetes based on certain diagnostic measurements.

## Models

The following machine learning models are implemented and evaluated:

*   **Logistic Regression**
*   **Decision Tree**
*   **Random Forest**

## How to Run

1.  **Prerequisites:**
    *   Python 3.x
    *   Jupyter Notebook or JupyterLab

2.  **Clone the repository:**
    ```bash
    git clone <repository-url>
    cd <repository-folder>
    ```

3.  **Install dependencies:**
    The notebook includes a cell to install the required Python libraries:
    ```python
    !pip install pandas scikit-learn matplotlib seaborn
    ```

4.  **Run the Jupyter Notebook:**
    Open and run the `Disease_Prediction.ipynb` notebook. The notebook will:
    *   Load and preprocess the data.
    *   Train the models.
    *   Evaluate the models and generate visualizations.
    *   Print the final results.

## Results

The evaluation results, including confusion matrices and ROC curves, are saved in the `results/` directory.

*   `results/Decision Tree_confusion_matrix.png`
*   `results/Logistic Regression_confusion_matrix.png`
*   `results/Random Forest_confusion_matrix.png`
*   `results/roc_curve.png`

The notebook also prints a summary of the performance metrics (Accuracy, Precision, Recall, F1-score, ROC-AUC) for each model.


## Visualizations

### Confusion Matrices

**Decision Tree**
![Decision Tree Confusion Matrix](results/Decision%20Tree_confusion_matrix.png)

**Logistic Regression**
![Logistic Regression Confusion Matrix](results/Logistic%20Regression_confusion_matrix.png)

**Random Forest**
![Random Forest Confusion Matrix](results/Random%20Forest_confusion_matrix.png)

### ROC Curve

![ROC Curve](results/roc_curve.png)


## Dependencies

*   pandas
*   scikit-learn
*   matplotlib
*   seaborn


