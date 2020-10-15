# Credit Scoring with Convolutional Neural Network

The most important source of information about potential borrowers is credit history bureau. However, data about a customer is usually provided in a form of a table, where rows correspond to the records (previous and active loans) in credit history, and columns are attributes characterizing these records. 

Since each customer may have many records in their history, it requires complex aggregation and extensive feature engineering to produce meaningful indicators in order to build a model predicting creditworthiness of a particular customer. 

At the same time, convolutional neural networks are successfully applied for pattern recognition and automatic feature engineering on images. Therefore, if the data about a customer is represented as a 2-dimensional matrix, it can serve as input for a standard CNN. In this way sophisticated transformations are not required, and a model is trained almost directly on raw data.

This project demonstrates how credit bureau data can be adapted for the use with a CNN. Also, performance of the model is assessed against a simple naive model.
