\# 🔋 Germany Energy Consumption Forecasting



This project focuses on \*\*forecasting daily energy consumption\*\* in Germany using historical renewable energy production data from the \[Open Power System Data (OPSD)](https://data.open-power-system-data.org/time\_series/) project.



---



\## 📁 Dataset Used



\- \*\*Dataset\*\*: `opsd\_germany\_daily.csv`

\- \*\*Source\*\*: Open Power System Data (OPSD) – Germany daily time-series

\- \*\*Features\*\*:

&nbsp; - `Date`

&nbsp; - `Consumption`

&nbsp; - `Wind`

&nbsp; - `Solar`

&nbsp; - `Wind+Solar`



---



\## ⚙️ Objective



To predict future \*\*daily electricity consumption\*\* using regressors trained on time-based and renewable energy variables.



---



\## 🧠 Techniques \& Tools



\- \*\*Exploratory Data Analysis (EDA)\*\*

\- \*\*Time-Series Resampling\*\* (daily → monthly)

\- \*\*Handling Missing Values\*\*

\- \*\*Train/Test Split\*\*

\- \*\*Feature Engineering\*\*

\- \*\*Modeling with:\*\*

&nbsp; - Linear Regression (baseline)

&nbsp; - Random Forest Regressor (optimized)

\- \*\*Evaluation Metrics:\*\*

&nbsp; - MAE (Mean Absolute Error)

&nbsp; - MSE (Mean Squared Error)

&nbsp; - R² Score

\- \*\*Feature Importance Plot\*\*



---



\## 🧪 Results



| Model               | MAE     | MSE       | R² Score |

|--------------------|---------|-----------|----------|

| Linear Regression  | 87.93   | 13,743.00 | 0.4763   |

| Random Forest      | \*\*47.73\*\* | \*\*6,224.97\*\* | \*\*0.7628\*\*   |



✅ The \*\*Random Forest\*\* model showed significantly better performance than the baseline, explaining over \*\*76%\*\* of the variance in energy consumption.



---



\## 📊 Visuals



\- Energy consumption trend (daily \& monthly)

\- Correlation heatmap of features

\- Actual vs predicted consumption plots

\- Feature importance chart from Random Forest



---



\## 📂 Folder Structure

```

Germany\_Energy\_Forecasting/

├── data/

│   ├── processed/

│   │   └── processed\_data.pkl

│   └── opsd\_germany\_daily.csv

├── notebooks/

│   ├── EDA\_preprocessing.ipynb

│   └── Modeling\_and\_evaluation.ipynb

├── README.md

└── requirements.txt

```

---



\## ✅ How to Run



1\. Clone the repo  

2\. Install dependencies  

&nbsp;  ```bash

&nbsp;  pip install -r requirements.txt



