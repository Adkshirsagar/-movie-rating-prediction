# -movie-rating-prediction
A project to predict movie ratings using a machine learning model.
# 🎬 Movie Rating Prediction

This project focuses on building a machine learning model to predict IMDb-style movie ratings using a dataset of Indian movies. It explores various features such as genre, actors, directors, and other metadata to train and evaluate predictive models.

---

## 📌 Project Objectives

- Analyze the factors influencing movie ratings.
- Preprocess and clean the movie dataset.
- Perform exploratory data analysis (EDA).
- Build regression models to predict movie ratings.
- Evaluate and compare model performance using metrics like RMSE, MAE, and R² Score.

---

## 🧠 Technologies Used

- **Python**
- **Google Colab**
- **Pandas**
- **NumPy**
- **Matplotlib & Seaborn** (for visualization)
- **Scikit-learn** (for ML models)
- **Linear Regression, Decision Tree Regressor, Random Forest Regressor**

---
## 📊 Dataset

- **Source**: Indian IMDb-style movies dataset
- **Features Used**:
  - Movie title
  - Genre
  - Director
  - Actors
  - Year
  - Duration
  - Rating (Target)
 
![Dataset](https://github.com/user-attachments/assets/4fba19db-0b9a-4b9a-8f8a-73565246b2f4)


> Note: Dataset may be loaded within the Colab notebook or linked externally depending on the environment.

---

## 🚀 How to Run

1. Clone this repository or download the `.ipynb` file.
2. Open it using [Google Colab](https://colab.research.google.com/).
3. Upload the dataset if prompted.
4. Run the notebook cells sequentially.

---

## 📉 Model Evaluation

| Model                  | RMSE    | R² Score |
|-----------------------|----------|----------|
| Linear Regression     | 0.3023   | 0.6891   | 
| Decision Tree         | 0.4809   | 0.5054   | 
| Random Forest         | 0.2458   | 0.7472   | 
| K nearest neighbours  | 1.0878   | -0.1187  |

---

## 📌 Outcome

- Built an end-to-end movie rating prediction pipeline.
- Compared multiple ML models and selected the best one.
- Understood the impact of categorical and numerical features in movie success.

---
## 📌 Screenshots

![Rating Distribution](https://github.com/user-attachments/assets/82f575d1-27c3-43b3-9a79-21cf5443318c)

![Ratings VS Genre](https://github.com/user-attachments/assets/1982bf73-e9ae-404e-88b8-6153254c1652)

![Ratings Vs top 10 directors](https://github.com/user-attachments/assets/7d7e3022-84c6-4668-8c0d-b5d45cd8d158)

![Correlation matrix](https://github.com/user-attachments/assets/f20df1b9-082f-4f49-a907-e668176ee06e)

![Actual vs predicted ratings](https://github.com/user-attachments/assets/4ed5181e-f080-4846-94f8-30279c85eeb5)

![Feature importance](https://github.com/user-attachments/assets/1a3d9052-bbaa-4cde-a8f4-28237b2e8626)








