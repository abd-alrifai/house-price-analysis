#  House Price Regression Analysis

##  Project Overview
This project is a **training project** provided by a company to practice **real-world statistical analysis and regression modeling** using Python.  
The main objective is to analyze housing price data, test for statistical significance between categorical variables, and build a **multiple linear regression model** to predict `SalePrice`.

---

##  Objectives
1. Test whether there is a statistically significant difference in `SalePrice` among different `GarageFinish` categories using **ANOVA**.
2. Perform **post-hoc (pairwise)** analysis using **Tukey’s HSD test** to find which pairs differ.
3. Build a **Multiple Linear Regression (MLR)** model to predict house prices.
4. Validate model assumptions: normality, homoscedasticity, and multicollinearity.
5. Evaluate the model using **MAE**, **RMSE**, **MAPE**, and **R²** metrics.

---

##  Technologies Used
- **Python 3.11**
- **Pandas**, **NumPy**
- **SciPy**, **Statsmodels**
- **Scikit-learn**
- **Matplotlib**, **Seaborn**
- **Jupyter Notebook**

---

## Project Files
| File | Description |
|------|--------------|
| `Copy of project_2_data.csv` | Dataset used for the analysis |
| `Statistics_Analysis_and_Regression.ipynb` | Jupyter Notebook containing full analysis |
| `analysis_model.py` | Python script version (training & evaluation) |
| `README.md` | Project documentation |

---

##  Statistical Tests
### Hypotheses:
- **H₀:** No difference in mean `SalePrice` between `GarageFinish` categories.  
- **H₁:** At least one `GarageFinish` category differs in mean `SalePrice`.

### Tests used:
- **One-way ANOVA (parametric, two-tailed)**
- **Tukey’s HSD post-hoc test**

---

##  Regression Model
**Target variable:** `SalePrice`  
**Predictors:**  
- `OverallQual`  
- `GrLivArea`  
- `GarageCars`  
- `TotalBsmtSF`

### Model equation:
\[
SalePrice = b_0 + b_1*OverallQual + b_2*GrLivArea + b_3*GarageCars + b_4*TotalBsmtSF + \epsilon
\]

---

##  Model Evaluation
| Metric | Description | Example Result |
|---------|--------------|----------------|
| **MAE** | Mean Absolute Error | 21000 |
| **RMSE** | Root Mean Squared Error | 32000 |
| **MAPE** | Mean Absolute Percentage Error | 7.8% |
| **R²** | Coefficient of Determination | 0.82 |

---

##  Visualization Examples
- Residual distribution plot  
- Actual vs Predicted `SalePrice` scatter plot  
- Feature importance bar chart

---

##  Key Insights
- `OverallQual` and `GrLivArea` are the strongest predictors of `SalePrice`.
- ANOVA confirmed a significant difference in `SalePrice` among `GarageFinish` categories.
- The regression model explains a large portion of the variance in housing prices.

---
##  Dataset
You can download the dataset used in this project from the following link:

 [Download Dataset (Google Drive)](https://drive.google.com/file/d/1qxaNXt_Vcg_CDjqr2R1qkVXM_evpruxm/view?usp=sharing)

##  Credits
Developed by **Abdulrhman Alrifai** as part of a **training project** in collaboration with a company program to strengthen skills in:
- Statistical data analysis
- Hypothesis testing
- Machine learning regression modeling

---

##  Contact
For inquiries or collaboration:
- GitHub: [@abd-alrifai](https://github.com/abd-alrifai/)
- Email: abd.alrifai963@gmail.com
