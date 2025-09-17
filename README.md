# STOCK MARKET FORECASTING USING MACHINE LEARNING 
## Problem Statement
As financial markets grow increasingly complex, there is a need for efficient machine learning methods capable of producing reliable stock price predictions. However, implementing machine learning models can be challenging as it requires significant domain expertise and computational resources. 
## Objective
This study aims to contribute to overcoming these challenges by exploring the effectiveness of tree-based ensemble techniques and the PyCaret automated machine learning framework for forecasting S&P 500 index price movements. 
## Methodology
Using a historical dataset spanning from 2015 to 2024, the research focuses on an univariate approach with one-step ahead and multi-step ahead forecasting for the Close index feature. Five tree-based ensemble models—Random Forest, Extreme Gradient Boosting, Light Gradient Boosting Machine, Categorical Boosting, and Adaptive Boosting—are evaluated using walk-forward cross-validation with a sliding window splitter technique. 
## The results
Highlighting the superior performance of Light Gradient Boosting Machine and Categorical Boosting, with Categorical Boosting emerging as the best-performing model, achieving the lowest Root Mean Squared Error (181.5) and Mean Absolute Error (152.9). Interestingly, combining these top models into a hybrid approach resulted in diminished performance compared to Categorical Boosting’s performance. Recognizing the challenges of financial time series data, the study leverages PyCaret to streamline model development, cross-validation, and hyperparameter tuning, demonstrating its ability to simplify processes and conserve computational resources. The findings contribute to financial forecasting by providing a scalable and efficient framework for investment strategies, catering to both machine learning experts and non-experts.

