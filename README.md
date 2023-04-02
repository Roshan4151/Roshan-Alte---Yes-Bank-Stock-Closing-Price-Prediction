# Roshan-Alte---Yes-Bank-Stock-Closing-Price-Prediction
This is the Capstone project which is a part of my Data Science training at AlmaBetter.

# Introduction -
Yes Bank is a well-known bank in the Indian financial domain. Since 2018, it has been in the news because of the fraud case involving Rana Kapoor. Owing to this fact, it was interesting to see how that impacted the stock prices of the company and whether Time series models or any other predictive models can do justice to such situations. This dataset has monthly stock prices of the bank since its inception and includes closing, starting, highest, and lowest stock prices of every month. The main objective is to predict the stock's closing price of the month.

# Conclusion - 
1. From the dataset or Heatmap it is clear that, there is a **High-Correlationship** between **Independent Variables** and the **Dependent Variable**.
2. After plotting Histograms it is clear that our dataset was **Positively Skewed**.So we applied **Log Transformation** for the Transformation of the data.
2. After applying Linear Regression, Lasso, Lasso with Cross Validation, Ridge, Ridge with Cross Validation. We chooed the **Ridge with Cross Validation** ML model.Because it gives the Very High Accuracy among the all models mentioned above.
3. We choosed **Ridge CV** as a best model with the Accuracy of **99.32%**.
4. After that we visualise the performance of our **Ridge CV** model and the graph shows that we achieved the almost **Best Fit Model** for our dataset.
