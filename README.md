\# Beauty Products Sales Analysis \& Forecasting

\## DATDRD05 - Data Science Tools and Techniques

\### Data Driven Decision Making in Business



\*\*Student:\*\* Olabisi Bayo-Ojeleke  

\*\*Student Number:\*\* 1679040  

\*\*Institution:\*\* HAN University of Applied Sciences  

\*\*Specialisation:\*\* International Business Management — Marketing \& Sales  

\*\*Supervisor:\*\* Oliver Ntenje  

\*\*Submission Date:\*\* June 2026  









\## Project Overview



This project analyses cosmetic product sales data to identify best selling 

beauty products and predict future sales using machine learning forecasting 

models. The project follows the CRISP-DM framework and was inspired by the 

YouTube video "Using Copilot with Jupyter Notebooks."



\*\*Business Problem:\*\*

Many beauty businesses make marketing and stock decisions based on gut feeling 

rather than data. This leads to wasted budgets and missed sales opportunities.



\*\*Business Question:\*\*

"Which beauty products sell best, and how can we use historical sales data 

to predict future sales and support smarter marketing decisions?"









\## Repository Structure



Data-science-tools-and-techniques/

│

├── Beauty\_Sales\_Analysis.ipynb    # Main Jupyter Notebook

├── Cosmetic\_products\_sales.csv    # Dataset

├── README.md                      # This file

└── requirements.txt               # Required Python libraries









\## Dataset



\*\*Source:\*\* Kaggle — Cosmetic Products Sales Dataset  

\*\*Link:\*\* https://www.kaggle.com/datasets/parvezkhan90/cosmetic-products-sales  

\*\*Records:\*\* 34,950 rows | 20 columns  

\*\*Time Period:\*\* April 2017 — February 2020  









\## How to Run the Project



\### Prerequisites

Make sure you have Python installed on your system.



\### Step 1 — Clone the repository

```bash

git clone https://github.com/nifemiisgoated/Data-science-tools-and-techniques.git

cd Data-science-tools-and-techniques

```



\### Step 2 — Install required libraries

```bash

pip install -r requirements.txt

```



\### Step 3 — Launch Jupyter Notebook

```bash

jupyter notebook

```



\### Step 4 — Open the notebook

Click on \*\*Beauty\_Sales\_Analysis.ipynb\*\* to open it.



\### Step 5 — Run all cells

Click \*\*Kernel → Restart \& Run All\*\* to run the complete analysis.









\## Project Structure (CRISP-DM)



| Phase | Description |

|---|---|

| 1. Business Understanding | Problem definition, business case, objectives |

| 2. Data Understanding | Exploratory analysis, 6 visualisation charts |

| 3. Data Preparation | Missing values, duplicates, data cleaning |

| 4. Modelling | Prophet forecasting model (full dataset) |

| 4b. Advanced Modelling | Train/test split, ARIMA, SARIMA, experiments |

| 5. Evaluation | Cross-validation, MAE, RMSE, MAPE metrics |

| 6. Deployment | Business recommendations and conclusions |









\## Models Compared



| Model | MAE | RMSE | Result |

|---|---|---|---|

| Prophet | 16,056,098 | 19,180,486 | Baseline |

| ARIMA | 13,219,590 | 18,081,935 | Best overall |

| SARIMA | 17,176,824 | 21,348,236 | Underperformed |

| Prophet + Holidays | 29,149,239 | 33,040,693 | Worse |

| Prophet + Features | 18,474,501 | 24,646,726 | Slight improvement |

| Category 11 ARIMA | 2,041,261 | 2,580,202 | Best result |









\## Key Findings



1\. \*\*Category 11 dominates\*\* — generates more revenue than all other categories

2\. \*\*ARIMA outperforms Prophet\*\* for monthly beauty sales data

3\. \*\*Category-specific forecasting\*\* is 6x more accurate than overall forecasting

4\. \*\*North zone and Delhi\*\* are the strongest beauty markets

5\. \*\*December and January\*\* are consistently the strongest sales months

6\. \*\*Adding holidays made Prophet worse\*\* — confirmed monthly data limitation









\## Tools \& Technologies



| Tool | Purpose |

|---|---|

| Python 3.14 | Programming language |

| Jupyter Notebook | Development environment |

| Pandas | Data manipulation |

| Matplotlib \& Seaborn | Data visualisation |

| Prophet | Time series forecasting |

| ARIMA/SARIMA (pmdarima) | Statistical forecasting |

| Scikit-learn | Model evaluation metrics |

| GitHub | Version control and sharing |

| GitHub Copilot | AI coding assistant |









\## Assessment Criteria Alignment



| Criteria | How this project addresses it |

|---|---|

| Originality \& Innovation | Unique beauty industry focus, category-specific forecasting discovery |

| Fun \& Engagement | Iterative experimentation, multiple models, unexpected findings |

| Exploration \& Experimentation | 6 different model experiments, holiday effects, feature engineering |

| Documentation \& Sharing | Detailed markdown throughout, GitHub repository, README |









\## Video Presentation



Link: \[To be added after recording]











\## References



Khan, P. (2023). \*Cosmetic Products Sales Dataset.\* Kaggle. 

https://www.kaggle.com/datasets/parvezkhan90/cosmetic-products-sales



Taylor, S. J., \& Letham, B. (2018). Forecasting at scale. 

\*The American Statistician, 72\*(1), 37-45. 

https://doi.org/10.1080/00031305.2017.1380080



Smith, T. G. (2017). \*pmdarima: ARIMA estimators for Python\* (Version 1.8). 

http://www.alkaline-ml.com/pmdarima



McKinney, W. (2010). Data structures for statistical computing in Python. 

\*Proceedings of the 9th Python in Science Conference,\* 51-56.

https://doi.org/10.25080/Majora-92bf1922-00a



Hunter, J. D. (2007). Matplotlib: A 2D graphics environment. 

\*Computing in Science \& Engineering, 9\*(3), 90-95. 

https://doi.org/10.1109/MCSE.2007.55



Waskom, M. (2021). Seaborn: Statistical data visualization. 

\*Journal of Open Source Software, 6\*(60), 3021. 

https://doi.org/10.21105/joss.03021



Pedregosa, F., Varoquaux, G., Gramfort, A., Michel, V., Thirion, B., 

Grisel, O., \& Duchesnay, E. (2011). Scikit-learn: Machine learning in Python. 

\*Journal of Machine Learning Research, 12,\* 2825-2830.

https://www.jmlr.org/papers/v12/pedregosa11a.html



Box, G. E. P., Jenkins, G. M., Reinsel, G. C., \& Ljung, G. M. (2015). 

\*Time series analysis: Forecasting and control\* (5th ed.). Wiley.



Grand View Research. (2023). \*Beauty and personal care market size \& 

share report, 2023-2030.\* 

https://www.grandviewresearch.com/industry-analysis/beauty-personal-care-market



GitHub. (2023). \*GitHub Copilot: Your AI pair programmer.\* 

https://github.com/features/copilot

