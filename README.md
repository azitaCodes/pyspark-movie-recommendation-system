# Movie Recommendation System with PySpark

## Project Overview

This project builds a movie recommendation system using Apache Spark MLlib and the MovieLens 25M dataset.

The system analyzes user ratings, learns user preferences using the ALS (Alternating Least Squares) collaborative filtering algorithm, and generates personalized movie recommendations.

---

## Dataset

### MovieLens 25M Dataset

Dataset Statistics:

* Movies: 62,423
* Ratings: 25,000,095
* Users: 162,541

Files Used:

* movies.csv
* ratings.csv

Dataset Source:

https://grouplens.org/datasets/movielens/

---

## Technologies

* Python
* Apache Spark
* PySpark
* Spark MLlib
* ALS Collaborative Filtering
* Jupyter Notebook

---

## Project Structure

```text
DPySpark
│
├── data
│   ├── movies.csv
│   └── ratings.csv
│
├── notebooks
│   ├── 01_Load_Data.ipynb
│   ├── 02_User_Behavior_Analytics.ipynb
│   ├── 03_Recommendation_System.ipynb
│   └── 04_Model_Evaluation.ipynb
│
└── README.md
```

---

## Workflow

```text
MovieLens Dataset
        │
        ▼
Data Loading with PySpark
        │
        ▼
Data Exploration
        │
        ▼
User Behavior Analytics
        │
        ▼
ALS Recommendation Model
        │
        ▼
Movie Recommendations
        │
        ▼
Model Evaluation
```

---

## System Design

```text
MovieLens Dataset
       |
       v
+----------------+
| Data Loading   |
| PySpark CSV    |
+----------------+
       |
       v
+----------------+
| Data Analytics |
| User Behavior  |
+----------------+
       |
       v
+----------------+
| ALS Training   |
| Collaborative  |
| Filtering      |
+----------------+
       |
       v
+----------------+
| Predictions    |
| Recommendations|
+----------------+
       |
       v
+----------------+
| Evaluation     |
| RMSE / MAE     |
+----------------+
```

---

## Notebook Descriptions

### 01_Load_Data.ipynb

Tasks:

* Create Spark Session
* Load MovieLens Dataset
* Inspect Schema
* Explore Dataset Size
* Validate Data Loading

---

### 02_User_Behavior_Analytics.ipynb

Tasks:

* Most Active Users
* Most Rated Movies
* Highest Rated Movies
* Movie Popularity Analysis
* Join Movie Metadata with Ratings

---

### 03_Recommendation_System.ipynb

Tasks:

* Build ALS Recommendation Model
* Train Collaborative Filtering System
* Generate Movie Recommendations
* Predict User Ratings
* Display Recommended Movies

---

### 04_Model_Evaluation.ipynb

Tasks:

* Train/Test Split
* Generate Predictions
* Calculate RMSE
* Calculate MAE
* Compare ALS Ranks
* Select Best Model Configuration

---

## Evaluation Results

| Metric         | Value  |
| -------------- | ------ |
| RMSE           | 0.8406 |
| MAE            | 0.6559 |
| Best Rank      | 20     |
| Max Iterations | 5      |
| Regularization | 0.1    |

---

## Sample Recommendations

| User ID | Movie Title                     | Predicted Rating |
| ------- | ------------------------------- | ---------------- |
| 1       | Heights (2004)                  | 5.67             |
| 1       | Phish: Bittersweet Motel (2000) | 5.52             |
| 1       | Cozy Dens (1999)                | 5.33             |

---

## Skills Demonstrated

* Big Data Processing
* Apache Spark
* PySpark DataFrames
* Spark SQL
* Machine Learning
* Recommendation Systems
* Collaborative Filtering
* Model Evaluation
* Data Analytics
* Data Engineering

---

## How to Run

### 1. Clone Repository

```bash
git clone https://github.com/azitaCodes/pyspark-movie-recommendation-system.git
```

### 2. Install Dependencies

```bash
pip install pyspark
```

### 3. Start Jupyter Notebook

```bash
jupyter notebook
```

### 4. Run Notebooks in Order

1. 01_Load_Data.ipynb
2. 02_User_Behavior_Analytics.ipynb
3. 03_Recommendation_System.ipynb
4. 04_Model_Evaluation.ipynb

---

## Keywords

PySpark, Apache Spark, Spark SQL, Machine Learning, ALS, Collaborative Filtering, Recommendation Systems, Big Data Analytics, Data Engineering, Python, Jupyter Notebook, MovieLens

---

## Future Improvements

* Hyperparameter Tuning
* Cross-Validation
* Content-Based Recommendations
* Hybrid Recommendation Systems
* Real-Time Recommendation Pipeline
* Spark Streaming Integration
* Model Deployment with APIs

---

## Author

**Azita Ramezani**

PhD Student in Applied Data Science

GitHub:
https://github.com/azitaCodes

```
```
