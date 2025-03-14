# Predicting Chopin Competition Results Using Statistical Models 🎹

## Overview
The **Chopin Competition** is one of the most prestigious piano competitions in the world, where jury deliberations take hours to determine which pianists advance to the next stage. But what if we could replace these long hours of discussions with **seconds of computation**? This project explores the predictability of competition outcomes using **statistical analysis and machine learning models**. By analyzing jury scores, we aim to determine whether the decision-making process can be streamlined and whether biases or patterns emerge in the jury’s evaluations.

## Motivation
Artistic competitions are inherently subjective, with multiple judges assigning scores based on their personal expertise. While points are awarded in each round, final decisions often remain opaque and involve lengthy deliberations. This project seeks to answer:
- Can the jury’s decisions be **statistically predicted** based on their scoring patterns?
- Are there **hidden biases** or inconsistencies in the evaluation process?
- Could machine learning **accelerate** the decision-making process without compromising artistic judgment?

## Data Sources 📊
The dataset used in this project consists of **jury scores from the 18th International Chopin Competition (2021)**, publicly released by the **National Chopin Institute**. The dataset includes:
- **Contestants' names** and **nationalities**
- **Scores assigned by each jury member** in each stage
- **Binary qualification indicator** (whether a contestant advanced to the next round)
- **Aggregate statistical measures**, such as average and median scores

## Methods & Analysis 🛠️
The project is structured into several analytical phases:

### **1. Data Preprocessing & Exploration**
- Cleaning and structuring the dataset (handling missing values, standardizing formats)
- Analyzing **score distributions**, **ranking stability**, and **jury consistency**
- Visualizing **contestant performance across stages**

### **2. Statistical Modeling & Machine Learning**
- **Decision Trees** – capturing non-linear patterns in jury decisions
- **Logistic Regression** – modeling the probability of a contestant advancing
- **Random Forests** – improving predictions through ensemble learning
- **Feature Engineering** – deriving meaningful variables (e.g., normalized scores, consistency metrics)

### **3. Key Findings & Insights**
- The **winner of the competition ranked first in every stage**, suggesting strong consistency in scoring
- **Decision Trees achieved near-perfect accuracy**, indicating a high level of predictability in jury decisions
- Logistic Regression performed well but struggled with edge cases, showing that **human decisions are often linear, but not always**
- **National bias** was **not strongly evident**, but certain patterns emerged in score distributions

## Project Structure 📂
```plaintext
📁 Chopin-Competition-Prediction
│-- 📜 data_preprocessing.py        # Cleaning and structuring raw competition data
│-- 📜 exploratory_analysis.py       # Visualizing jury scores and performance trends
│-- 📜 decision_tree_model.py        # Building a Decision Tree for prediction
│-- 📜 logistic_regression_model.py  # Implementing Logistic Regression
│-- 📜 random_forest_model.py        # Using Random Forests to refine predictions
│-- 📜 results_visualization.py      # Generating key insights and visualizations
│-- 📜 README.md                     # Project documentation
```

## Technologies Used 🖥️
This project utilizes:
- **SAS Viya** 


## Conclusion 🎶
This project demonstrates that machine learning models can **effectively predict jury decisions** in the Chopin Competition with high accuracy. While AI cannot replace human artistic judgment, it offers a powerful tool for analyzing patterns, identifying biases, and streamlining evaluations. The results raise thought-provoking questions about the role of **objectivity vs. subjectivity in artistic competitions**.

## Contributions 🤝
Contributions are welcome! If you have ideas for improving the models or expanding the analysis, feel free to submit a pull request.

## License 📄
This project is licensed under the **MIT License** – see the `LICENSE` file for details.

---
### 🎼 Can machine learning match the intuition of world-class jurors? Let's find out! 🚀

