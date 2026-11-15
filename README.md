# Machine Learning Practice — Feature Engineering to Regression from Scratch

A hands-on collection of notebooks covering the practical side of classical machine learning: cleaning messy data, engineering features, building scikit-learn pipelines, and implementing core algorithms such as **gradient descent and ridge/lasso regression from scratch**.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)

---

## Contents

### 1. Exploratory data analysis
- [EDA practice](EDA/EDA-Practice.ipynb) — univariate and bivariate analysis
- [Automated profiling](EDA/Pandas_profiling.ipynb) — generating a full data report

### 2. Handling missing data
| Technique | Notebook |
|---|---|
| Complete case analysis | [CCA](Handle_Dataset/CCA/Complete_Case_Analysis_(CCA).ipynb) |
| Mean / median imputation | [mean_median_imputation](Handle_Dataset/mean_median_imputation/mean_median_imputation.ipynb) |
| Missing-category imputation | [missing_category_imputation](Handle_Dataset/missing_category_imputation/missing_category_imputation.ipynb) |
| Random-sample imputation | [random_sample_imputation](Handle_Dataset/missing_indicator/random_sample_imputation.ipynb) |
| Missing indicator | [Missing indicator](Handle_Dataset/missing_indicator/Misiing_Indicator.ipynb) |
| KNN imputation | [KNN_imputation](Handle_Dataset/KNN_imputer/KNN_imputation.ipynb) |
| Tuning imputer parameters with grid search | [automatically-select-imputer-parameters](Handle_Dataset/missing_indicator/automatically-select-imputer-parameters.ipynb) |
| Mixed numeric/text values | [handling_mixed_values](Handle_Dataset/handling_mixed_values.ipynb) |

### 3. Outlier detection and removal
- [Z-score method](outliers/outlier_removal_using_zscore/outlier_removal_using_zscore.ipynb)
- [IQR method](outliers/outlier_removal_using_iqr/outlier_removal_using_iqr.ipynb)
- [Percentile / winsorization](outliers/outlier_removal_using_percentile/outlier_removal_using_percentile.ipynb)

### 4. Feature engineering and transformation
- [Encoding categorical data](Encoding/Encoding_Categorical_Data.ipynb) — ordinal, label and one-hot encoding
- [Feature scaling](Feature%20Scaling/standard_scaler_practice.ipynb) — standardisation
- [Function transformer](Function_transformer/Function_Transfromer.ipynb) — log, reciprocal and custom transforms
- [Power transformer](power_transform/Power_Transfromer.ipynb) — Box-Cox and Yeo-Johnson
- [Binning](Binning_and_Binarization/Binning.ipynb) and [binarization](Binning_and_Binarization/Binarization.ipynb)
- [Column transformer](column_transformer/Column_tranformer.ipynb) — different preprocessing per column
- [End-to-end pipeline](pipeline/pipeline.ipynb) — preprocessing + model in one scikit-learn `Pipeline` on the Titanic dataset

### 5. Dimensionality reduction
- [PCA on MNIST](pca-on-mnist.ipynb)

### 6. Regression and optimisation
- [Simple linear regression](LinearRegression/simple_lr/LinearRegression.ipynb)
- [Multiple linear regression](LinearRegression/simple_lr/Multiple_LR/MultipleLinearRegression.ipynb)
- [Polynomial regression](Polynomial%20Regression/polynomial_regression.ipynb)
- [Gradient descent and SGD from scratch](Gradient%20Descent/gradient_descent_sgd_from_scratch.ipynb)
- [Ridge and lasso from scratch](Ridge_and_lasso/ridge_lasso_from_scratch.ipynb)

## Running the notebooks

```bash
git clone https://github.com/muhammadahsan3/Machine-Learning-Practice.git
cd Machine-Learning-Practice
pip install numpy pandas scikit-learn matplotlib seaborn jupyter
jupyter notebook
```

The datasets each notebook uses are stored next to it.

---

**Muhammad Ahsan** — AI Engineer · [Portfolio](https://muhammad-ahsan-ai-portfolio.vercel.app) · [GitHub](https://github.com/muhammadahsan3)
