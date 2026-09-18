🇺🇸 USA Economy Analysis

An exploratory and economic analysis of key U.S. macroeconomic indicators using Python.

This project examines the behavior and relationships between real GDP, GDP growth, inflation, unemployment, and other macroeconomic indicators over time, with a focus on business cycles, major economic turning points, and the interaction between key economic variables.

---

📌 Project Overview

The U.S. economy has experienced several major expansions, recessions, inflationary periods, and economic shocks over the past decades.

The goal of this project is to use economic data and Python-based analysis to explore these patterns and answer several questions about the U.S. economy:

- What were the major expansion and recession periods?
- Which economic events were associated with major turning points?
- How are GDP growth, unemployment, and inflation related?
- How did the COVID-19 period differ from normal economic conditions?
- What patterns can be observed across different phases of the U.S. business cycle?

The project combines data analysis, visualization, and economic interpretation rather than relying only on statistical outputs.

---

🎯 Research Questions

1. Business Cycles

What are the major expansion and recession periods in the U.S. economy, and what historical or economic events were associated with major turning points?

The analysis identifies major changes in economic activity and examines their relationship with historical events and economic conditions.

2. GDP Growth, Unemployment, and Inflation

What are the relationships between GDP growth, unemployment, and CPI growth in the U.S. economy?

The analysis examines descriptive statistics, correlations, and time-series patterns between these variables.

3. COVID-19 Economic Shock

How did the COVID-19 period differ from normal economic conditions?

The project identifies the COVID-19 period and compares its economic behavior with broader historical patterns.

4. Economic Growth and Business Conditions

The final stage of the project combines the engineered indicators and exploratory results to provide a broader economic interpretation of U.S. macroeconomic conditions.

---

📊 Dataset

The project uses quarterly U.S. macroeconomic data covering approximately 1974–2024.

The final analytical dataset contains:

- 201 quarterly observations
- 25 variables

Key indicators include:

- Real GDP
- GDP growth
- CPI / inflation
- Unemployment
- Changes in unemployment
- Other engineered macroeconomic indicators

The dataset was prepared and transformed specifically for the analysis conducted in this project.

---

🔧 Methodology

The project follows a structured data-analysis workflow:

Raw Data
   ↓
Data Audit
   ↓
Data Preparation
   ↓
Feature Engineering
   ↓
Exploratory Data Analysis
   ↓
Economic Analysis
   ↓
Economic Interpretation

Data Audit

The initial dataset was examined for:

- Data types
- Missing values
- Duplicates
- Time coverage
- Variable structure
- Basic statistical properties

Data Preparation

The data preparation stage included:

- Date and period handling
- Cleaning and restructuring variables
- Handling missing observations
- Preparing the dataset for time-series analysis

Feature Engineering

Additional indicators were created to make the dataset more suitable for economic analysis, including:

- GDP growth
- CPI growth
- Changes in unemployment
- Recession-related indicators
- High-growth indicators
- COVID-19 period flags

Exploratory Analysis

The exploratory analysis focuses on:

- Descriptive statistics
- Time-series behavior
- Correlations
- Distribution of economic indicators
- Relationships between macroeconomic variables
- Identification of unusual economic periods

Economic Analysis

The final analysis interprets the statistical and visual results in an economic context, with particular attention to:

- Business cycles
- Recessions
- Economic expansions
- Inflation
- Unemployment
- GDP growth
- Major economic shocks

---

🔎 Selected Findings

Some notable relationships identified during the analysis include:

GDP Growth & Unemployment

GDP growth and changes in unemployment show a strong negative correlation:

Correlation ≈ -0.73

This is consistent with the general cyclical pattern in which periods of stronger economic growth tend to coincide with improving labor-market conditions, while economic contractions are often associated with rising unemployment.

GDP Growth & Inflation

GDP growth and CPI growth show a moderate positive correlation:

Correlation ≈ 0.51

This relationship should not be interpreted as evidence of causality. It reflects the relationship observed in the analyzed sample and may be influenced by different economic conditions across time.

Inflation & Changes in Unemployment

The correlation between CPI growth and changes in unemployment is relatively weak:

Correlation ≈ -0.11

This suggests that the relationship between inflation and changes in unemployment is considerably less direct in this dataset than the relationship between GDP growth and unemployment.

«Correlation measures association, not causation. The results should therefore be interpreted within the broader economic and historical context.»

---

🦠 COVID-19 Period

The analysis explicitly identifies the COVID-19 period as an unusual economic episode.

A dedicated indicator was created for approximately:

2020 Q1 – 2021 Q1

This period is treated separately because the magnitude and speed of economic changes during the pandemic make direct comparison with ordinary business-cycle fluctuations more difficult.

---

📁 Project Structure

USA-Economy-Analysis/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── notebooks/
│   ├── 01-data-audit.ipynb
│   ├── 02-data-preparation.ipynb
│   ├── 03-feature-engineering.ipynb
│   ├── 04-exploratory-analysis.ipynb
│   └── 05-economic-analysis.ipynb
│
├── .gitignore
├── README.md
└── requirments.txt

---

🧰 Tools & Technologies

The project was developed using:

- Python
- Pandas — data manipulation and analysis
- NumPy — numerical operations
- Matplotlib — data visualization
- Seaborn — statistical visualization
- Statsmodels — statistical and econometric analysis
- Jupyter Notebook — analysis environment
- Git & GitHub — version control and project documentation

---

▶️ How to Run

Clone the repository:

git clone https://github.com/parya-B/USA-Economy-Analysis.git

Navigate to the project directory:

cd USA-Economy-Analysis

Install the required packages:

pip install -r requirments.txt

Open the notebooks using Jupyter Notebook or JupyterLab:

jupyter notebook

Run the notebooks in numerical order, starting with:

01-data-audit.ipynb

and continuing through:

05-economic-analysis.ipynb

---

⚠️ Limitations

This project is primarily an exploratory economic analysis.

Therefore:

- Correlation results do not establish causality.
- Historical relationships may change under different economic conditions.
- Some indicators are simplified representations of broader economic concepts.
- The analysis does not attempt to build a structural macroeconomic model.
- Historical events are used as economic context rather than as formal causal explanations.

The results should therefore be interpreted as evidence from the analyzed data rather than definitive causal conclusions.

---

📚 Project Purpose

This project was developed as a practical portfolio project to combine:

Python + Data Analysis + Economics + Economic Interpretation

The main objective was to practice taking an economic question from raw data through cleaning, feature engineering, exploratory analysis, visualization, and final interpretation.

---

👩🏻‍💻 Author

Parya Babaimehr

B.Sc. Economics
Aspiring Economic / Data Analyst

GitHub: "parya-B" (https://github.com/parya-B)
