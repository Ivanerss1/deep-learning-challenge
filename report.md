# deep-learning-challenge

1. Overview of the Analysis

The goal of this analysis was to create a binary classifier to predict whether applicants for Alphabet Soup funding would succeed. Historical data from 34,000 organizations was used to train the model, with IS_SUCCESSFUL as the target variable.

2. Results

Data Preprocessing

    •    Target Variable: IS_SUCCESSFUL
    •    Feature Variables: APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, and ASK_AMT.
    •    Removed Variables: EIN and NAME (non-predictive identification columns).

Model Performance

    •    Architecture:
    •    Two hidden layers (100 and 50 neurons, ReLU activation) and one output layer (Sigmoid activation).
    •    Accuracy: ~72.5%
    •    Loss: ~0.536

Steps to Improve Performance:

    •    Grouped rare categories under "Other".
    •    Normalized numerical features using StandardScaler.
    •    Adjusted neurons and layers for optimization.

3. Summary

    •    The model achieved ~72.2% accuracy but did not meet the 75% target. I tried adding another layer adding more neaurond and incleasing my epochs but still wasn't able to make a diffencen in my accuracy.
    •    Recommendations: Experiment with more layers, neurons.
































Citation: (OpenAI. ChatGBT. Personal Communication. November, 2024)