# National-Accessibility-Case-Study

This project seeks to ensure "two-thirds of venues predicted to be without a ramp should not have a ramp" such that ramps can be installed for events that do need them. Empirically, this project seeks to maximize the negative predictive value (npv) while not sacrificing too much accuracy. The conclusion is that we should take time prioritizing events without alcohol, WIFI, ticketing or promotion. At the same time, we want to search for super venue events and events with loud music.

## Steps:
- Prepared the dataset by data cleaning, standardization, and visualization.
- Applied stepwise logistic regression to fit the models with lowest AIC. Created two models: one with missing values replaced by sample mean, the other one with only true values.
- Evaluated the models based on NPV, Accuracy, and the ROC curve.

## Results of Model Evaluation:

| Models                  |  NPV        | Accuracy  |
|-------------------------| ----------  |-----------|
|Full Model               |  0.666      | 0.586     |
|Model with true values   |  0.703      | 0.7       |
