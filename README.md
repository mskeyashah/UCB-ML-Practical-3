# UCB-ML-Practical-3

Jupyter Notebook: https://github.com/mskeyashah/UCB-ML-Practical-3/blob/main/prompt_III.ipynb


## 🎯 Business Objective
To increase term deposit subscriptions by identifying and targeting customers most likely to respond positively to marketing campaigns, using predictive modeling.

## 📈 Model Performance Insights

All tuned models outperformed the baseline accuracy of 88.87%, indicating they’re capturing meaningful patterns rather than random noise.

Tuned Logistic Regression emerged as the top performer, achieving a test accuracy of 89.82% — proving that a simple, interpretable model can still be highly effective.

Tuned KNN and Tuned Decision Trees closely followed, each reaching around 89.7% test accuracy, showing significant gains from hyperparameter tuning.

Support Vector Machines (SVM), while accurate, required the longest training time (~44 seconds) and didn’t deliver a clear advantage over the faster, simpler models.

## 🔍 Feature Influence

Key features that strongly influenced term deposit subscription include:

Job, education, and contact method — indicating socioeconomic and communication factors matter.

Month and euribor3m (interest rate) — suggesting timing and macroeconomic conditions are crucial campaign levers.

The models performed consistently well across data from 17 distinct marketing campaigns, reinforcing their robustness when tuned properly.

## ✅ Recommended Actions

Deploy Tuned Logistic Regression into live marketing workflows for efficient and interpretable lead scoring.

Use model coefficients to guide customer segmentation strategies — especially around job roles, education level, and contact preferences.

Schedule campaigns in months associated with higher response rates, as revealed by the model.

Continue tuning models as new campaign data becomes available to maintain peak performance.

## 🎯 Business Impact

By leveraging tuned classification models — especially Logistic Regression — the bank can:

✅ Improve campaign ROI through data-driven targeting

✅ Prioritize high-potential leads, maximizing conversion rates

✅ Minimize customer fatigue by avoiding low-likelihood contacts

✅ Strategically time outreach based on interest rates and historical performance

This predictive framework empowers smarter marketing decisions, turning insights into tangible business value.
