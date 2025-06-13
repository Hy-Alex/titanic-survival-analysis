# Titanic Survival Analysis - Data Science Portfolio Project

This project demonstrates a full data analysis and machine learning pipeline on the Titanic dataset. It covers data cleaning, feature engineering, exploratory data analysis (EDA), model training, and evaluation.

## Project Structure

- titanic_survival_analysis.ipynb — Main notebook with analysis
- /images — Saved plots and visualizations
- README.md — Project documentation

## Key Features

- Data cleaning (Age, Cabin, Embarked, Fare)
- Feature engineering (Deck, Cabin_Known, etc.)
- Visual EDA (bar plots, survival rates, etc.)
- Logistic Regression modeling
- Evaluation (accuracy, confusion matrix, ROC curve)

## Exploratory Data Analysis (EDA)

The following visualizations provide insights into survival distribution and feature correlations.

### 1. Survival Count

This plot shows the number of passengers who survived versus those who did not.

![Survival Count](images/survival_count.png)

### 2. Survival Rate by Sex

This visualization clearly shows the survival advantage of female passengers over male passengers. While around 74% of women survived, only about 19% of men did, which strongly supports the notion of "women and children first" during evacuation.

![Survival Rate by Sex](images/survival_by_sex.png)


### 3. Survival Rate by Passenger Class

This chart demonstrates that higher-class passengers had higher survival rates.

![Survival Rate by Passenger Class](images/survival_by_pclass.png)

### 4. Age Distribution of Passengers

The histogram shows that the majority of Titanic passengers were between 20 and 40 years old, with a noticeable peak in the early 20s. This suggests that many young adults were on board, possibly traveling for work or immigration. Children and older adults were fewer in number.

![Age Distribution of Passengers](images/age_distribution.png)

### 5. Survival Rate by Passenger Class and Sex

This grouped bar chart shows the survival rate broken down by both passenger class and gender. The data reveals two clear patterns:

- Females had significantly higher survival rates than males across all classes.
- First-class passengers had the highest survival rates overall, especially among women (nearly 100%).

This plot highlights how both gender and socio-economic status affected survival outcomes.

![Survival Rate by Passenger Class and Sex](images/survival_by_class_and_sex.png)

### 6. Survival Rate by Age Group

This bar chart displays survival rates across different age groups:

- **Children (age < 12)** had the highest survival rate, showing prioritization in rescue.
- **Seniors (age > 60)** had the lowest survival rate, possibly due to physical limitations or being overlooked.
- Adults, teens, and middle-aged groups had similar survival probabilities.

This plot helps visualize how age influenced the likelihood of survival.

![Survival Rate by Age Group](images/survival_by_age_group.png)

### 7. Survival Rate by Embarkation Port

This bar chart shows the survival rates based on passengers' port of embarkation:

- Passengers who boarded at port **C (Cherbourg)** had the highest survival rate.
- **S (Southampton)** had the lowest, possibly due to larger numbers of lower-class passengers.
- **Q (Queenstown)** fell in the middle but with a wider error range, indicating fewer samples.

This feature may reflect socioeconomic or ticket-class patterns tied to embarkation location.

![Survival Rate by Embarkation Port](images/survival_by_embarked_port.png)

### 8. Survival Rate by Cabin Known

This visualization shows a strong contrast between passengers with known and unknown cabin information:

- Passengers with **known cabin numbers** had a significantly higher survival rate (~67%).
- Those with **missing cabin data** had a lower survival rate (~30%).

This feature may reflect passenger class and location — wealthier passengers likely had cabins and better access to lifeboats.

![Survival Rate by Cabin Known](images/survival_by_cabin_known.png)


## How to Run

```bash
pip install -r requirements.txt
jupyter notebook titanic_survival_analysis.ipynb


Contact
Email: yong.75@hotmail.com
GitHub: https://github.com/Hy-Alex
