# credit-risk-classification

## Overview of the Analysis

The goal of the Credit Risk analysis is to assess the creditworthiness of potential borrowers. The data used in this analysis was gathered from a vast historical lending dataset obtained from a peer-to-peer lending service. I constructed a Logistic Regression model and divided our dataset into Test and Train sets for algorithm training. The model examined the original dataset, identifying patterns to make predictions on the borrowers creditworthiness.

I limited the model to 100 iterations, as it proved to be the most efficient number for reducing processing time while maintaining accurate results. Additional iterations didn't affect the prediction performance of the model in any significant way.

## Results


* Machine Learning Model (0), Healthy Loans:
    * Accuracy: 99%
    * Precision: 100%
    * Recall: 99%

* Machine Learning Model (1): High-Risk Loans:
    * Accuracy: 99%
    * Precision: 85%
    * Recall: 91%

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:

* Which one seems to perform best? How do you know it performs best?
  
In summary, this model demonstrates a high level of reliability in predicting both healthy and high-risk loans. While I have greater confidence in its accuracy when predicting healthy loans, the effectiveness of both models is notable. I would recommend prioritizing the use of the healthy loan predictor over the high-risk model. By doing so, borrowers stand a better chance of loan approval. Rather than solely relying on patterns of high-risk borrowers to filter out applicants, lenders can establish parameters based on trends in healthy loans. If a potential borrower aligns with the criteria of a healthy loan, it is likely safe to extend credit to them. This approach minimizes potential errors and theoretically ensures that deserving individuals are not unfairly rejected due to any margin of error inherent in our model.
