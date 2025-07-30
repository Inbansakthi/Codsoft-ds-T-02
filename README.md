# 🎬 Movie Rating Prediction with Python

This project builds a machine learning model to predict the **rating of a movie** based on features such as **genre, director, and actors**.  
It explores data preprocessing, feature engineering, and regression modeling to understand which factors influence movie ratings.

---

## 📂 Dataset
The dataset typically includes details of movies, such as:
- Title / Name
- Year of release
- Duration
- Genre(s)
- Director
- Lead actors
- Number of votes
- IMDb rating (target variable)

*(Dataset used: `IMDb Movies India.csv` — replace with your dataset link if sharing.)*

---

## ✅ Objectives
- Analyze historical movie data to discover patterns affecting ratings.
- Preprocess and clean the dataset (handle missing data, format text columns).
- Engineer useful features (extract main genre, handle rare directors/actors).
- Build and evaluate regression models to estimate movie ratings.
- Identify which features most influence the predicted ratings.

---

## ⚙️ Steps
1. **Data Exploration & Visualization**
   - Understand data distributions, missing data, and correlations.
2. **Data Cleaning & Preprocessing**
   - Handle missing values.
   - Extract year, clean votes, and convert categorical data.
3. **Feature Engineering**
   - One-hot encode genres.
   - Group rare directors/actors as 'Other' to reduce noise.
4. **Modeling**
   - Train regression models: Linear Regression, Random Forest, etc.
   - Compare models based on RMSE and R² scores.
5. **Insights**
   - Analyze feature importance to see what drives ratings.

---

## 📦 Libraries Used
- Python 3
- pandas
- numpy
- matplotlib & seaborn
- scikit-learn

---

## 📊 Results
The final model predicts IMDb movie ratings with an RMSE of about **X.XX** (replace with actual result).  
Key factors found to influence ratings:
- Genre (e.g., Drama, Comedy)
- Director reputation
- Number of votes
- Year of release

---

## 📁 Project Structure
```text
movie-rating-prediction/
├── data/
│   └── IMDb Movies India.csv
├── notebooks/
│   └── movie_rating_model.ipynb
├── src/
│   └── preprocessing.py
│   └── modeling.py
├── README.md
└── requirements.txt
