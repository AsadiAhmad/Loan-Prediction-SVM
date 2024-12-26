# Loan-Prediction-SVM
Predicting Loan State with SVM method, preprocessing and feature selction

## Tech :hammer_and_wrench: Languages and Tools :

<div>
  <img src="https://github.com/devicons/devicon/blob/master/icons/python/python-original.svg" title="Python" alt="Python" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/jupyter/jupyter-original.svg" title="Jupyter Notebook" alt="Jupyter Notebook" width="40" height="40"/>&nbsp;
  <img src="https://assets.st-note.com/img/1670632589167-x9aAV8lmnH.png" title="Google Colab" alt="Google Colab" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/numpy/numpy-original.svg" title="Numpy" alt="Numpy" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/pandas/pandas-original.svg"  title="Pandas" alt="Pandas" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/matplotlib/matplotlib-original.svg"  title="MatPlotLib" alt="MatPlotLib" width="40" height="40"/>&nbsp;
  <img src="https://cdn.worldvectorlogo.com/logos/seaborn-1.svg"  title="seaborn" alt="seaborn" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/scikitlearn/scikitlearn-original.svg"  title="Sci-kit Learn" alt="Sci-kit Learn" width="40" height="40"/>&nbsp;
</div>

## Run the Notebook on Google Colab

You can easily run this code on google colab by just clicking this badge [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/AsadiAhmad/Loan-Prediction-SVM/blob/main/Code/Loan_Prediction_SVM.ipynb)

## About the Dataset
Train set : [![Static Badge](https://img.shields.io/badge/Trainset-red?style=for-the-badge&logo=databricks&labelColor=fcfbd4)](https://github.com/AsadiAhmad/Loan-Prediction-SVM/blob/main/Dataset/train.csv)

Test Set : [![Static Badge](https://img.shields.io/badge/Testset-red?style=for-the-badge&logo=databricks&labelColor=fcfbd4)](https://github.com/AsadiAhmad/Loan-Prediction-SVM/blob/main/Dataset/test.csv)

### Dataset Structure

| Column | Description |
| ----------- | ----------- |
| Loan_ID | Unique Loan ID |
| Gender | Male/Female |
| Married | Whether Married: Yes/No |
| Dependents | No. of people depending on the Applicant |
| Education | Graduate/Undergraduate |
| Self_Employment | Whether Self_Employment : Yes/No |
| ApplicantIncome | Applicant Income |
| CoapplicantIncome | Co-Applicant Income |
| LoanAmount | Loan Amount (in thousands) |
| Loan_Amount_Term | Loan Duration |
| Credit_History | Credit History of the Applicant |
| Property_Area | Urban/Semiurban/Rural |
| Loan_Status | Whether Loan Approved: Yes/No |

## Execution time

For running all sell on hosted runtime it costs about 132 minutes **(around 2 hours)** but there is tips to run it **around 5 minutes**.

But you can just using one kernel for the SVM so here are more details:

- Linear Kernel : **5 min**
- Poly Kernel : **16 min**
- RBF Kernel : **8 min**
- Sigmoid Kernel : **37 min**

and for the finding the optimized hyperparameter you need to run again this kernels but you can optimize the hyperparameters **(Step 10)** and **skip** first training model **(Step 9)**.

the kernels are not having different accuracy so you can just select one in the** Step 10** (finding hyperparameter) like the **linear kernel** and your all time to spend running jupyter notbook is just **around 5 min**.

## License

This project is licensed under the MIT License.
