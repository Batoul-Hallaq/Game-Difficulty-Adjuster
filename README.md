# Game-Difficulty-Adjuster
# Adaptive Difficulty Framework for Puzzle Games (ML-Driven)

An end-to-end Machine Learning pipeline designed to personalize gameplay experiences by dynamically adjusting difficulty levels based on player behavior and skill progression.

## Project Overview
Static difficulty in puzzle games often leads to frustration or boredom. This project addresses this by proposing a framework that:
* **Simulates Player Behavior:** Created a statistically realistic dataset of 30,000 gameplay records.
* **Player Modeling:** Groups players into 5 distinct skill tiers using **K-Means Clustering**.
* **Dynamic Adjustment:** Predicts the optimal difficulty (Easy, Medium, Hard) using a **Random Forest Classifier**.

## Key Features
* **Feature Engineering:** Extracts metrics like accuracy, solving time, hint usage, and learning slope (rate of improvement).
* **Interpretability:** Uses Random Forest to provide transparent difficulty decisions based on feature importance.
* **Performance Simulation:** Includes a "Before vs. After" module to demonstrate how DDA (Dynamic Difficulty Adjustment) increases success rates and player engagement.

## Tech Stack
* **Language:** Python
* **Machine Learning:** Scikit-learn (K-Means, Random Forest, StandardScaler).
* **Data Analysis:** Pandas, NumPy.
* **Visualization:** Matplotlib, Seaborn (Confusion Matrix, Feature Importance Plots).

## Key Results
* **High Accuracy:** The Random Forest model achieved a test accuracy of **98.5%**.
* **Improved Engagement:** Simulation showed a reduction in unnecessary retries and a more balanced success rate across all player segments.

## Repository Contents
* `ML_project.ipynb`: Full implementation from data generation to model evaluation.
* `ML project Report.pdf`: Complete technical documentation and literature review.

---
*This project contributes a scalable system for real-time difficulty updates in interactive environments.*
