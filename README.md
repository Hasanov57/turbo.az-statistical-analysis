# Statistical Analysis of Azerbaijan Car Listings

This project analyzes an Azerbaijan car-listing dataset and applies statistical methods to answer practical business questions about vehicle prices and inventory composition.

## Project Tasks

- Calculate grouped descriptive statistics, including mean, median, standard deviation, and distribution shape
- Define null and alternative hypotheses for two business questions
- Check normality and equality of variance before parametric testing
- Perform Welch's t-test, Welch's ANOVA, and a chi-square test
- Interpret p-values, confidence intervals, and effect sizes
- Connect the statistical results to business decisions

## Files

- `statistical_analysis.ipynb` — complete analysis with explanations, code, outputs, and visualizations
- `cars.csv` — source dataset stored locally and excluded from GitHub because of its large size

## Tools Used

- Python
- Jupyter Notebook
- pandas
- NumPy
- SciPy
- statsmodels
- Matplotlib
- Seaborn

## How to View

Open `statistical_analysis.ipynb` directly on GitHub or run it in Jupyter Notebook, JupyterLab, VS Code, or Google Colab.

## Notes

Duplicate listings were removed, prices were limited to AZN, and log-price was used for statistical testing because the original price distribution was strongly right-skewed. The analysis uses confidence intervals and effect sizes together with p-values to evaluate both statistical and practical importance.
