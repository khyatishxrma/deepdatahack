Crop Recommendation using Machine Learning
TEAM= HACKSTACK
This project predicts the most suitable **crop** for a given **State** and **District** using historical agricultural data. It's built for hackathon deployment and designed to be simple, fast, and extendable.
Overview
In this project, we used machine learning to build a crop recommendation system based only on **location-based inputs**: `State` and `District`. Using a Decision Tree classifier, our model can predict which crop is most likely to grow in a particular region with **over 80% accuracy**.

---

## Exploratory Data Analysis (EDA)

We began with detailed EDA to understand the structure and trends in the dataset:
- Visualized crop frequency by state/district
- Checked for missing values and duplicates
- Identified distribution of crops
- Removed noisy/unnecessary columns
- Cleaned dataset for modeling

---

## Machine Learning Approach

- **Model Used:** Decision Tree Classifier  
- **Features Used:** State, District (Label Encoded)  
- **Target Variable:** Crop  
- **Model Accuracy:** ~85% (varies slightly per run)  
- **Why Decision Tree?** Fast training, interpretable, works well with categorical data

