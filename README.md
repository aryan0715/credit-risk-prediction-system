# Mini Project 2: Credit Risk Prediction

A Python notebook that explores a credit risk dataset and compares four classifiers:

- Logistic Regression
- Decision Tree
- Random Forest
- XGBoost

The workflow includes missing-value handling, categorical encoding, scaling, a stratified training/test split, and model evaluation using accuracy, precision, recall, F1, ROC-AUC, and confusion matrices. It also plots feature importance and demonstrates a prediction for an example applicant. The final example explicitly uses the Random Forest model.

## Open the notebook

[View mini_project_2.ipynb](mini_project_2.ipynb)

The notebook was written for Google Colab. For this private repository, download the notebook from GitHub and open [Google Colab](https://colab.research.google.com/), then choose **File > Upload notebook**.

## Run it

1. Open the notebook in Colab.
2. Run the cells in order.
3. When the upload cell prompts you, select a ZIP containing `credit_risk_dataset.csv` at its top level.
4. Continue running the remaining cells to train the models and display their results.

The CSV must include the `loan_status` target and the feature columns referenced by the notebook. The dataset is not included in this repository.

`requirements.txt` lists the Python libraries used. Colab provides most of these, and the notebook includes an XGBoost installation cell. The upload cell uses `google.colab.files`, so it needs adaptation to run in a local Jupyter environment.

## Saved results

The uploaded notebook includes its original saved outputs and plots. Its JSON structure and Python cell syntax were checked before upload; the notebook was not rerun during repository preparation.
