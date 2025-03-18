# Road Safety Dynamics and Policy Impacts in Response to Population Growth in Rwanda

## Overview
This project explores how **population growth** correlates with **road traffic mortality** in Rwanda from 2000 to 2019. Using **Decision Tree Regression** and additional statistical methods, the analysis finds a **significant negative correlation**, indicating that an increasing population has coincided with decreased road traffic fatalities. It also highlights various **government initiatives** (speed governors, law enforcement, public education) that have contributed to enhanced road safety.

An **interactive GIS dashboard** further illustrates population and mortality trends across Rwanda’s districts, facilitating user-friendly data exploration.

## Repository Contents
1. **`project_codes`**  
   - A Python script (or multiple scripts) that perform:
     - Data cleaning and preprocessing.
     - Decision Tree model development and evaluation.
     - Exploratory Data Analysis (EDA), correlation, and hypothesis testing.

2. **`Mortality_Traff.csv`**  
   - Contains annual mortality rates due to road traffic injuries (per 100,000 population) from 2000 to 2019, filtered for Rwanda.

3. **`Population_G.csv`**  
   - Contains annual population growth data (percentage change) for Rwanda from 1960 to 2019, although the analysis focuses on 2000 to 2019.

4. **`combined_data.csv`**  
   - A merged dataset unifying the mortality and population growth information for convenient modeling and plotting.

## Key Findings
- **Inverse Relationship**: Population growth and traffic mortality demonstrate a negative correlation (\(r = -0.37\)).
- **Model Performance**: 
  - **Mortality Model**: \( R^2 = 0.972 \) and \( \text{MSE} \approx 0.345 \)  
  - **Population Growth Model**: \( R^2 = 0.641 \) and \( \text{MSE} \approx 0.112 \)  
- **Policy Impact**: Strict law enforcement, mandatory speed governors, public education (like *Gerayo Amahoro*), and other initiatives appear to reduce fatality rates despite rising population.

## How to Use
1. **Clone or Download** the repository (via the green “Code” button on GitHub).
2. **Open/Review the Code**:
   - Examine `project_codes` (e.g., `analysis.py` or `main.ipynb`, depending on your filename) in your local environment or online to see how data is preprocessed, models are built, and results are generated.
3. **Install Dependencies** (if using Python):
   - Typically:
     ```bash
     pip install pandas numpy scikit-learn matplotlib
     ```
     (Add or remove libraries as needed.)
4. **Run the Scripts**:
   - Execute the Python scripts in your preferred IDE or notebook environment to:
     - Load and clean data.
     - Fit Decision Tree models.
     - Generate figures and statistical outputs (MSE, R², correlation).
5. **Explore the Dashboard**:
   - **[GIS Dashboard Link](https://www.arcgis.com/apps/dashboards/e7f68152e62542589a1d73b6c6994fb7)**
   - Interact with maps showing district-level population changes and traffic mortality rates.

## Project Background
> *Abstract Highlights*  
> - Demonstrates a **negative correlation** between growing population and declining road fatalities.  
> - Emphasizes **effective road safety measures**: law enforcement, speed limits, and community education.  
> - Suggests that **policy interventions** can significantly influence public health outcomes, especially in rapidly urbanizing contexts.

> *Methodology*  
> - **Decision Tree Regression** to model population growth and mortality trends.  
> - **OLS Regression & Hypothesis Testing** to assess statistical significance.  
> - **GIS Dashboard** to visualize demographic changes and mortality in real time.

## How to Cite
If you use or build upon this work, please cite it as:
