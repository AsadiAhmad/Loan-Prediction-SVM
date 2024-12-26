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
### Download Dataset
you can use this Dataset with clicking this badges :

Train set : [![Static Badge](https://img.shields.io/badge/Trainset-red?style=for-the-badge&logo=databricks&labelColor=fcfbd4)](https://github.com/AsadiAhmad/Loan-Prediction-SVM/blob/main/Dataset/train.csv)

Test Set : [![Static Badge](https://img.shields.io/badge/Testset-red?style=for-the-badge&logo=databricks&labelColor=fcfbd4)](https://github.com/AsadiAhmad/Loan-Prediction-SVM/blob/main/Dataset/test.csv)

### Using Dataset on jupyter notebook
on the step 3 of the code file you can easily use the dataset like importing this code:
```sh
train_set_url = "https://raw.githubusercontent.com/AsadiAhmad/Loan-Prediction-SVM/refs/heads/main/Dataset/train.csv"
test_set_url = "https://raw.githubusercontent.com/AsadiAhmad/Loan-Prediction-SVM/refs/heads/main/Dataset/test.csv"

pd.set_option('display.max_rows', None)

train_set = pd.read_csv(train_set_url)
test_set = pd.read_csv(test_set_url)
```

### Dataset Structure

| Column | Description | Type |
| ----------- | ----------- | ----------- |
| Id | Unique Loan ID | Int |
| Income | The income person have | Int |
| Age | Age of person | Int |
| Experience | No. of years of experience | Int |
| Married/Single | Married/Single state : single/married | String |
| House_Ownership | House ownership : owned/rented/norent_noown | String |
| Car_Ownership | Car ownership : yes/no | String |
| Profession | The profession person have | String |
| CITY | The city person live | String |
| STATE | The state person live | String |
| CURRENT_JOB_YRS | How many years the person have the job | Int |
| CURRENT_HOUSE_YRS | How many years the person have the house | Int |
| Risk_Flag | Loan State: 0/1 | Int |

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
