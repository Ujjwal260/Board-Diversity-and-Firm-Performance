# Board-Diversity-and-Firm-Performance
Empirical panel-data analysis examining the relationship between board diversity (gender, nationality, and educational diversity) and firm financial performance and innovation outcomes using secondary data and econometric modelling.

# Board-Diversity-and-Firm-Performance

Empirical panel-data analysis examining the relationship between board diversity (gender, nationality, and educational diversity) and firm financial performance and innovation outcomes using secondary data and econometric modelling.

---

## Project Overview

This repository contains the analytical code and documentation supporting the MSc dissertation titled **“The Relationship Between Board Diversity and Firm Performance”**.

The project investigates how different dimensions of board diversity—gender diversity, nationality diversity, and educational diversity—relate to firm financial performance and innovation outcomes. Using a longitudinal panel dataset of publicly listed firms, the study applies panel regression techniques to examine whether board diversity contributes to short-term financial performance or innovation output.

The analysis is conducted entirely using secondary data and focuses on firm-level observations across multiple years. All data preparation, variable construction, statistical modelling, and visualisation are implemented within a single Jupyter Notebook.

---

## Research Objectives

The project addresses the following research question:

**What is the relationship between board diversity and firm performance?**

Specifically, the study aims to:
- Examine the relationship between board gender diversity and accounting-based firm performance.
- Assess whether nationality diversity on corporate boards influences market-based performance.
- Analyse the association between educational diversity and firm-level innovation outcomes.
- Evaluate the robustness of findings using alternative model specifications.

---

## Data Description

The analysis relies on a consolidated panel dataset comprising:
- **503 publicly listed firms**
- **2,238 firm-year observations**

The dataset integrates information from:
- Corporate board composition databases  
- Financial statement databases  
- Market valuation data  
- Patent-based innovation datasets  

Only firms with complete information on board diversity, financial performance, innovation measures, and control variables are included in the final sample.

---

## Methodology

The empirical strategy follows a structured quantitative approach.

### Data Preparation
- Merging firm-level datasets across multiple sources  
- Handling missing values  
- Winsorising financial variables to mitigate the influence of outliers  

### Variable Construction
- Gender diversity measured as the percentage of female directors  
- Nationality diversity measured using a diversity index  
- Educational diversity measured using an index of academic background heterogeneity  
- Financial performance measured using Return on Assets (ROA) and Tobin’s Q  
- Innovation measured using the logarithm of firm-level patent or publication counts  

### Statistical Analysis
- Descriptive statistics and correlation analysis  
- Panel regression models  
- Random-effects models used as the primary estimation approach due to the largely time-invariant nature of board diversity  
- Fixed-effects models employed as robustness checks  
- Firm-clustered robust standard errors applied throughout  

### Visualisation
- Correlation heatmaps  
- Coefficient plots  
- Innovation-related charts  

---

## Repository Structure
├── Dessertation analysis.ipynb # Main Jupyter Notebook containing the full analysis
├── README.md # Project documentation


All analytical steps—from raw data preparation to final regression outputs—are contained within the notebook.

---

## Libraries and Tools Used

The analysis is implemented in **Python** using the following key libraries:
- pandas – data manipulation and cleaning  
- numpy – numerical operations  
- matplotlib – data visualisation  
- seaborn – statistical plotting  
- statsmodels – econometric and panel regression modelling  
- linearmodels – fixed-effects and random-effects panel estimators  
- scipy – statistical functions  

The project is executed within a **Jupyter Notebook** environment.

---

## Reproducibility

All analysis steps are fully documented within the notebook to ensure transparency and reproducibility. The notebook can be executed sequentially to replicate the results reported in the dissertation, subject to access to the underlying datasets.

Due to data licensing restrictions, raw datasets are not publicly shared in this repository. However, variable definitions, model specifications, and outputs are fully documented.

---

## Academic Context

This repository supports an MSc dissertation submitted to the **University of Greenwich** as part of the **Business Analytics** programme. The repository is provided for academic transparency and does not represent a commercial or policy advisory product.

---

## Disclaimer

The findings presented in this repository are for academic purposes only. They reflect empirical associations observed in the dataset and should not be interpreted as causal evidence or investment advice.

---

## Author

MSc Business Analytics Student  
University of Greenwich  

---

## Contact

For academic queries regarding this project, please contact the repository owner via GitHub.
