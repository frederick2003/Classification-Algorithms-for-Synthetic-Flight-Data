# Flight Delay Prediction (UK & Ireland)

This project analyses and predicts **commercial flight departure delays** in the UK and Ireland using a synthetic aviation dataset. A flight is classified as *delayed* if it departs **15 minutes or more** after its scheduled time.

The work was completed as part of a data science in python assignment and is fully implemented in a **single, well-documented Jupyter Notebook**.

---

## Dataset

Two CSV files are used and merged for analysis:

- `flights_schedule.csv`  
  Flight schedules, routes, and identifiers  
- `flight_conditions_outcomes.csv`  
  Weather conditions at origin airports and delay outcomes  

Dataset source:  
http://mlg.ucd.ie/modules/python/delays.zip

---

## Project Objectives

1. **Data Preparation & Characterisation**
   - Merge schedule and weather datasets into a unified analytical table
   - Clean and preprocess data, including feature engineering
   - Explore trends using statistical summaries and visualisations

2. **Classification & Evaluation**
   - Train and evaluate **three different classification models**
   - Predict whether a flight will be delayed
   - Compare models using appropriate evaluation metrics

3. **Predictive Feature Analysis**
   - Analyse which features contribute most to delay prediction
   - Assess feature importance and predictive strength

---

## Methods & Tools

- **Language:** Python  
- **Environment:** Jupyter Notebook  
- **Libraries:**  
  - pandas, numpy  
  - matplotlib, seaborn  
  - scikit-learn  

**Techniques applied:**
- Feature engineering
- Exploratory Data Analysis (EDA)
- Supervised classification
- Model comparison and evaluation
- Feature importance analysis

---

## Key Outcomes

- Identified clear patterns linking **weather conditions, routes, and scheduling factors** to flight delays  
- Demonstrated comparative strengths and weaknesses of multiple classifiers  
- Highlighted the most predictive features influencing departure delays  

---

## Notes

- The dataset is **synthetic** and intended for educational use  
- The project focuses on **methodology, evaluation, and interpretation**, rather than deployment  
- Generative AI tools were used responsibly for guidance and structuring

---

## Author

*Computer Science graduate with interests in data analytics, machine learning and software engineering*
