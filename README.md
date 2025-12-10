# 📊 Statistics and Probability Projects

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange)](https://jupyter.org/)
[![Status](https://img.shields.io/badge/Status-Completed-success)]()

> **A collection of data analysis projects aimed at applying statistical theories and probability concepts.**
> This repository documents my coursework for the Statistics and Probability module, featuring Exploratory Data Analysis (EDA) and comprehensive statistical testing.

---

## Table of Contents
- [About the Repository](#-about-the-repository)
- [Repository Structure](#-repository-structure)
- [Project Details](#-project-details)
    - [1. EDA Project: Titanic Survival Analysis](#1-eda-project-titanic-survival-analysis)
    - [2. Final Project: Google Play Store Analytics](#2-final-project-google-play-store-analytics)
- [Tech Stack](#-tech-stack)
- [How to Run](#-how-to-run)
- [Author](#-author)

---

## 🧐 About the Repository

This repository serves as a portfolio of my work in **Statistics and Probability**. The primary goal is to demonstrate proficiency in:
* **Data Wrangling:** Cleaning and preparing real-world datasets (Kaggle).
* **Statistical Inference:** Applying hypothesis testing and probability theory to draw conclusions.
* **Data Visualization:** Communicating insights through effective plotting.

---

## 📂 Repository Structure

```bash
statprob-statistics-and-probability/
├── EDA_Titanic/               # Exploratory Data Analysis Project
│   ├── titanic_data.csv       # Source dataset
│   └── titanic_eda.ipynb      # Analysis notebook
├── Final_GooglePlay/          # Final Project (Capstone)
│   ├── googleplaystore.csv    # Source dataset
│   └── analysis_report.ipynb  # Comprehensive statistical analysis
└── README.md                  # Project Documentation

🚀 Project Details
1. EDA Project: Titanic Survival Analysis

Dataset: Titanic - Machine Learning from Disaster (Kaggle)

In this module, I performed an in-depth Exploratory Data Analysis (EDA) to understand the demographics and factors influencing passenger survival.

    Key Activities:

        Handling missing values (Imputation for Age and Cabin).

        Analyzing survival rates based on Pclass, Sex, and Embarked.

        Visualizing age distribution among survivors vs. non-survivors.

    Key Insight: Examples include how female passengers and those in 1st Class had a significantly higher probability of survival.

2. Final Project: Google Play Store Analytics

Dataset: Google Play Store Apps

This is the capstone project where I applied advanced statistical concepts to analyze the app market.

    Scope of Analysis:

        Exploratory Data Analysis (EDA): Cleaning data (removing duplicates, fixing data types) and analyzing Category and Rating trends.

        Distribution Identification: Checking if the app ratings follow a Normal Distribution or Skewed Distribution using visual inspection (Histograms) and statistical tests (Shapiro-Wilk/KS Test).

        Probability Calculation: Calculating the conditional probability of an app being "Paid" given it belongs to a specific Category.

        Sampling Distribution: Demonstrating the Central Limit Theorem (CLT) by taking random samples of app ratings.

        Hypothesis Testing:

            Example: Testing if there is a significant difference in average ratings between "Paid" apps and "Free" apps (T-Test / Mann-Whitney U).

🛠 Tech Stack

The analysis was performed using the Python ecosystem:

    Python: Core programming language.

    Pandas: Data manipulation and cleaning.

    NumPy: Numerical calculations.

    Matplotlib & Seaborn: Static and statistical data visualization.

    SciPy: For probability distributions and hypothesis testing.

💻 How to Run

To run these notebooks locally on your machine:

    Clone the repository:
```
git clone [https://github.com/catursetyo/statprob-statistics-and-probability.git](https://github.com/catursetyo/statprob-statistics-and-probability.git)
    ```
    Navigate to the directory:
    ```
cd statprob-statistics-and-probability
    ```
    Install dependencies:
    ```
pip install pandas numpy matplotlib seaborn scipy jupyter
    ```
    Launch Jupyter Notebook:
    ```
jupyter notebook
```
👤 Author

Catur Setyo
GitHub: @catursetyo
