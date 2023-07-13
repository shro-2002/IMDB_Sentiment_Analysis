# IMDB Dataset - Sentiment Analysis

This is a README file generated for the IMDB dataset, which contains 50,000 movie reviews suitable for natural language processing (NLP) or text analytics tasks. The dataset is used for binary sentiment classification, aiming to predict the sentiment (positive or negative) associated with each movie review. It is important to note that this dataset provides substantially more data than previous benchmark datasets.

## Dataset Details

- Total number of reviews: 50,000
- Training set size: 40,000 reviews
- Testing set size: 10,000 reviews

## Dataset Columns

The dataset consists of the following columns:

1. `review`: The movie review text (object)
2. `sentiment`: The sentiment associated with the review (object)

## Approach and Model Used

In this project, we employed a logistic regression model for sentiment classification. The logistic regression algorithm was implemented using scikit-learn.

## Model Performance

The model achieved the following performance metrics:

- Accuracy: 89.41%
- Confusion Matrix:

|          |   Predicted Negative   |   Predicted Positive   |
|----------|-----------------------|-----------------------|
| Negative |         4365          |          596          |
| Positive |          463          |         4576          |

- Classification Report:

```
              precision    recall  f1-score   support

    negative       0.90      0.88      0.89      4961
    positive       0.88      0.91      0.90      5039

    accuracy                           0.89     10000
   macro avg       0.89      0.89      0.89     10000
weighted avg       0.89      0.89      0.89     10000
```

## Execution Time

The execution time for the logistic regression model was approximately 4.92 seconds.

## Conclusion

In this project, we utilized the IMDB dataset to perform sentiment analysis on movie reviews. We trained a logistic regression model and achieved an accuracy of 89.41%. The model showed balanced performance for both positive and negative sentiments, as evident from the precision, recall, and F1-score values.

For further details, refer to the code provided in the Jupyter Notebook
