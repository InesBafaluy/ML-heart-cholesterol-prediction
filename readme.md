# Predicting Cholesterol and Heart Risk

Team project in statistical learning, 4th year of Applied Mathematics at INSA Toulouse (2025–2026).

## Goal

Using a synthetic healthcare dataset, we build models to predict:

- **cholesterol level** (regression)
- **heart risk** (classification)

## Methods

- Penalized linear models (**Ridge**, **Lasso**) and variable selection
- **Support Vector Machines** and other models
- Hyperparameter tuning with cross-validation, keeping the test set untouched until the final evaluation
- Metrics: RMSE and R² for regression; accuracy, sensitivity, specificity and AUC for classification

The whole study is done twice, in **Python** and in **R**.

## Files

| File | Content |
|---|---|
| `notebook_en_python_2.ipynb` | Python version of the study |
| `notebook_en_r.ipynb` | R version of the study |
| `healthcare_synthetic_data.csv` | Dataset |
| `ML-Project-4MA-2526-EN.pdf` | Project brief |
| `requirements.txt` | Python dependencies |
| `renv.lock` | R dependencies |

## Run

```bash
pip install -r requirements.txt
```

In R:

```r
renv::restore()
```
