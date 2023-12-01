# CryptoClustering
Module 19 challenge

In this challenge, use knowledge of Python and unsupervised learning to predict if cryptocurrencies are affected by 24-hour or 7-day price changes.

## Prepare The Data
   To preparation of the data, use the `StandardScaler()` module from `scikit-learn` to normalize the data from the CSV file. This is the outcome.
   ![image](https://github.com/lakigit/CryptoClustering/assets/138610916/895c7ced-ba17-4b93-90b0-31b6d259054f)

## Find The Best k Value
   After normalizing the data, the next step is to determine the optimal k value using the scaled DataFrame. This can be achieved by utilizing the Elbow method to identify the best value of k.
   ![image](https://github.com/lakigit/CryptoClustering/assets/138610916/65391b73-5bc2-42a4-bff1-faf181c0e49e)
   According to this Elbow Curve, it is clear that the best k value is 4. 
