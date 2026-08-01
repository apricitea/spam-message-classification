# Spam Message Classification 

## Setup

```bash
pip install -r requirements.txt
```

## Data Source

The dataset consists of 1.143 text obtained from SMS (Short Message Service) in Indonesian language. The dataset has 574(50.22%) normal messages and 569 (49.78%) spam messages.

[The dataset can be accessed here!](https://gist.github.com/agtbaskara/a1a7017027cc1df9d35cf06e1e5575b7)

## Text Preprocessing 

- Convert to lowercases
- Remove punctuations and numbers
- Remove stopwords
- Text normalization (replacing slang words)
- Stemming (reducing inflected words to their word stem, base or root form
- Remove whitespace

## Classification Model

The classification models compared are Support Vector Machine (SVM), Logistic Regression, and Extreme Gradient Boosting (XGB). Hyperparameter tuning is performed via Grid Search with 10-fold cross-validation. Models are validated on a held-out test set using Confusion Matrix, Classification Report, and AUC/ROC Score & Curve.

## Result

<img src="https://i.imgur.com/CIrxWnP.png"/>

<img src="https://i.imgur.com/Y2rKw8T.png"/>

- Comparison between the model prior to hyperparameter tuning shown that the Logistic Regression model has the best performance with accuracy of 97.38%, F1 Score of 97.6%, and AUC Score of 97.44% with only 0.02 seconds model training time.
- Hyperparameter tuning using Grid Search resulted in high boost of the SVM model performance while little to no improvement for the Logit and XGB model (note that their model prior to tuned already have a really good performance). 
- The tuned XGB model has the highest model training time reaching 172.84 seconds.
- The tuned Logistic Regression model has the best performance compared to all the other models and took considerably low training time. Therefore, the model that will be used for the deployment is going to be the tuned Logistic Regression.
