# Steam Game Popularity Prediction using Machine Learning

## 📌 Project Overview
This project explores the use of machine learning to predict the popularity of video games published on the Steam platform. Using game metadata and user-related information, the goal is to analyze which features contribute most to a game’s popularity and to build a predictive model based on those features.

This project was developed as part of a university machine learning course and focuses on applying the full data science workflow to a real-world dataset.

---

## 🎯 Problem Statement
Steam hosts tens of thousands of games with varying levels of success.  
The objective of this project is to answer the following question:

**Can we predict whether a Steam game will be popular based on its available metadata and user interaction data?**

---

## 📊 Dataset Description
The project uses publicly available Steam datasets, including:

- **Games dataset**  
  Contains metadata such as:
  - Game genres
  - Release information
  - Pricing and other attributes

- **User interaction dataset**  
  Contains user-related data such as:
  - Ownership and engagement signals
  - Aggregated interaction metrics

Due to dataset size limitations, preprocessing and feature selection were applied before model training.

---

## 🧠 Approach & Methodology

### 1. Data Exploration
- Inspected dataset structure and feature distributions
- Identified missing values and inconsistencies
- Analyzed relationships between features and popularity indicators

### 2. Data Preprocessing
- Cleaned and formatted raw data
- Handled missing or irrelevant values
- Encoded categorical variables
- Normalized numerical features where necessary

### 3. Feature Engineering
- Selected relevant features contributing to popularity
- Created derived features to improve model performance

### 4. Model Training
- Split data into training and test sets
- Trained machine learning models using scikit-learn
- Evaluated performance using standard classification metrics

### 5. Evaluation
- Assessed model accuracy and performance
- Analyzed strengths and limitations of the approach

---

## ⚙️ Technologies Used
- **Python**
- **Pandas & NumPy** – data manipulation
- **Scikit-learn** – machine learning models
- **Matplotlib / Seaborn** – data visualization
- **Jupyter Notebook** – experimentation and analysis

---

## 📈 Results
The trained model demonstrated the ability to identify patterns related to game popularity using available features. While results are not intended for production use, they show that machine learning can provide useful insights into factors influencing a game’s success on Steam.

---

## 🚀 Future Improvements
Potential enhancements to this project include:
- Trying more advanced models (e.g. XGBoost, LightGBM)
- Hyperparameter tuning
- Improved feature selection
- Handling class imbalance
- Deploying the model as a simple web application

---

## 📁 Repository Contents
- `steam_project.ipynb` – main notebook containing data analysis, preprocessing, model training, and evaluation
- `README.md` – project documentation
- (Optional future additions: datasets, saved models, results)

---

## 👤 Author
**Hidayet Durandurdu**  
University Machine Learning Project

---

## 📄 Disclaimer
This project was created for educational purposes and is not affiliated with or endorsed by Valve or Steam.
