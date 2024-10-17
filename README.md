
# Rocket Landing Prediction

## Project Overview

In the space launch industry, reducing costs is crucial for competitiveness. SpaceX offers rocket launches at a significantly lower price than traditional providers, largely due to its ability to reuse the first stage of its Falcon 9 rocket. Competing space companies can benefit greatly from predicting the likelihood of a successful first stage landing, as it directly impacts the cost of future launches.

This project aims to predict the success of the first stage rocket landing using data science techniques. Accurate predictions can enable better decision-making for pricing rocket launches and allow competitors to bid more strategically against SpaceX. 

## Problem Statement

Given the high cost of space launches, predicting the likelihood of successful first stage rocket landings can lead to more cost-effective strategies. SpaceX offers launches at $62 million, while other companies charge upwards of $165 million. This cost difference is largely due to the reusability of SpaceX's first stage rockets. By building predictive models, we aim to forecast the probability of successful landings, helping competitors to offer competitive bids.

## Project Scope

1. **Data Collection & Exploration**: Public datasets on SpaceX's past launches, including details of launch dates, rockets, and landing outcomes.
2. **Feature Engineering**: Relevant features such as rocket type, launch site, weather conditions, and prior landing success rates.
3. **Modeling**: Implementing machine learning models (logistic regression, random forests, and neural networks) to predict the likelihood of first stage landing success.
4. **Evaluation**: Assessing model performance using accuracy, precision, recall, and AUC-ROC metrics.
5. **Optimization**: Fine-tuning the model to achieve the highest predictive accuracy and reliability.

## Requirements 

- **Programming**: Python, Jupyter, SQL
- **Libraries**: Pandas, NumPy, Scikit-learn, TensorFlow, Matplotlib, Seaborn, Dash
- **Machine Learning Models**: Logistic Regression, Random Forest, K-Nearest Neghibors, Support Vector Machines 
  
## Results

The predictive models developed in this project achieved significant accuracy in determining the success of first stage landings, providing insights that can help companies make informed decisions and competitive bids in the space launch industry. In this table we present the overal resuls of tested models on SpaceX dataset:<br>
| Model                  | Accuracy  | Jaccard Index | F1 Score  |
|------------------------|-----------|---------------|-----------|
| Logistic Regression     | 0.833333  | 0.8           | 0.888889  |
| Support Vector Machine  | 0.833333  | 0.8           | 0.888889  |
| K-Nearest Neighbour     | 0.833333  | 0.8           | 0.888889  |
| Decision Tree           | 0.833333  | 0.8           | 0.888889  |


