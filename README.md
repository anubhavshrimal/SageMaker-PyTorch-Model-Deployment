## Project Overview

This project is done as a part of the Udacity's [Deep Learning Nanodegree](https://eu.udacity.com/course/deep-learning-nanodegree--nd101). Amazon's SageMaker is an AWS Machine Learning service that allows us to deploy ML models and get inferences from the model using the provided endpoint.

- Used SageMaker to train and deploy Sentiment Analysis model over IMDB movie reviews dataset.
- Created Lambda function to receive input review, preprocess and get inferences from the deployed model.
- Created API to allow access of the endpoint using a webapp.
- Created a simple Webapp to input review and get inference by the model whether the review is POSITIVE/NEGATIVE.
