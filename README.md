# chembl-compound-analysis
A Data Analysis coursework (IMU)

# Project Objective
To perform exploratory data analysis (EDA) and compound prioritization using bioactivity data from ChEMBL, focusing on IC50 standardization and structure–activity trend exploration.

# Dataset Overview
- 500 selected compounds retrieved from ChEMBL.
- Additional dataset of ~8000 compounds containing IC50 bioactivity data.

# Data Processing Workflow
1. Data Merging
   - Matched 500 selected compounds against larger dataset (~8000 entries)
   - Integrated physicochemical properties with bioactivity values

2. Unit Standardization
   - Standardized IC50 units across dataset
   - Convert IC50 values into pIC50

3. Data Cleaning
  - Removed compounds with missing names
  - Filtered inconsistent or incomplete bioactivity records

4. Feature Analysis
   - Identified most active and least active compounds based on pIC50

    Calculated:
   - Mean
   - Median
   - Standard deviation
   - Quantiles
   - Range
   - Value counts
   - Determined median Polar Surface Area (PSA)

5. Exploratory Data Analysis
   - Distribution plots (pIC50, MW, PSA)
   - Correlation observations between lipophilicity (AlogP) and activity
   - Activity spread visualization using matplotlib and seaborn

# Tools & Environment
Python (pandas, numpy, matplotlib, seaborn)
Google Colab

# Why This Project Matters
- This project simulates an early-stage compound prioritization workflow in drug discovery, demonstrating:
- Data cleaning and standardization capability
- Bioactivity transformation and normalization
- Statistical reasoning
- Visualization for decision support

# Future Improvements (prob?
- Apply regression modeling to predict pIC50
- Perform more feature importance analysis
- Deploy interactive dashboard (power bi?)
