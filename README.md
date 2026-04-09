# Student Performance Prediction

## Project Overview
This project uses machine learning methods to predict student academic performance based on the UCI Student Performance dataset. The main goal is to examine which factors are associated with final student grades and to compare the predictive performance of different regression models.

This project focuses on predicting the final grade (`G3`) of students using demographic, family, social, and school-related variables.

## Dataset
The dataset used in this project is the **Student Performance Dataset** from the **UCI Machine Learning Repository**.

It contains student achievement data collected from two Portuguese secondary schools. The dataset includes features related to:
- student background
- family background
- study habits
- school support
- social activities
- previous academic records

For this project, the file `student-mat.csv` is used.

## Project Objectives
The objectives of this project are:
1. To explore the relationships between student characteristics and final grades.
2. To build regression models that predict students' final grades (`G3`).
3. To compare the performance of different machine learning models.
4. To identify the most important factors related to academic performance.

## Research Questions
1. Which factors are most strongly associated with students' final grades?
2. Can student final grades be predicted using demographic, family, and study-related variables?
3. Which regression model performs best for this prediction task?

## Project Structure
```text
student-performance-prediction/
│── data/
│   ├── raw/
│   │   └── student-mat.csv
│   └── processed/
│       └── cleaned_student_mat.csv
│
│── notebooks/
│   ├── 01_data_loading_and_cleaning.ipynb
│   ├── 02_exploratory_data_analysis.ipynb
│   └── 03_modeling_and_evaluation.ipynb
│
│── src/
│   ├── preprocessing.py
│   ├── feature_engineering.py
│   └── train_model.py
│
│── results/
│   ├── figures/
│   └── metrics/
│
│── README.md
│── requirements.txt
│── .gitignore
│── final_report.md
