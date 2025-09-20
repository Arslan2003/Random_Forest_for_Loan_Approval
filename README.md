# Random Forest for Loan Approval

A machine learning project that applies the Random Forest Classifier to predict loan approval decisions. The project demonstrates how AI can support financial institutions in automating risk assessment and improving lending accuracy.

<br>

## Overview

This repository contains a stand-alone implementation of a Random Forest model for loan approval classification. The main workflow is:
1. Data Preprocessing – Cleaning and preparing the dataset (handling categorical features, missing values, etc.).
2. Model Training – Building and tuning a Random Forest Classifier.
3. Evaluation – Comparing accuracy, precision, recall, and F1-score.
4. Bias & Fairness Considerations – Exploring how datasets can affect outcomes.
5. Optimisation – Testing different hyperparameters to improve results.

<br>

## Results

> Baseline accuracy: ~80%

> Improved accuracy after tuning: up to 83%

**Advantages**: Handles categorical & numerical data well, resists overfitting, no need for normalisation.  
This makes Random Forest a robust choice for loan approval prediction compared to single decision trees.

<br>

## Installation & Usage

1. Clone the repository:
```
git clone https://github.com/Arslan2003/Random_Forest_for_Loan-Approval.git
cd Random_Forest_for_Loan-Approval
```
2. Install dependencies:
```
pip install -r requirements.txt
```
3. Run the notebook or script to train and evaluate the model:
```
python random_forest_for_loan-approval.py
```

<br>

## Contributing
Contributions are welcome! Here are a few ideas for future improvements:
- Combine Random Forest with other classifiers (Ensemble Methods).
- Experiment with feature engineering to improve model interpretability.
- Expand dataset coverage for fairness and bias analysis.
- Deploy as a simple API for real-time predictions.  

If you’d like to contribute, please fork the repo and submit a pull request after making your changes.

<br>

## Author
[Arslonbek Ishanov](https://github.com/Arslan2003) - First-Class Data Scientist & AI/ML Enthusiast

<br>

## License
This project is licensed under the MIT License – see the [LICENSE](LICENSE) file for details.

<br>

## Learn More
For an in-depth explanation of the methodology, experiments, and analysis, please refer to the full report included in this repository.

<br>

## References
[Original Dataset on Kaggle](https://www.kaggle.com/datasets/ninzaami/loan-predication)

<br>

## Tags
`Machine Learning` `Random Forest` `Classification` `Loan Approval` `AI in Finance` `Python` `Scikit-Learn`
