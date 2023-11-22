# Sea_SurfaceStudy

.Results

4.1 Sarima
  
Several important criteria were used to evaluate the SARIMAX model's predicting performance for sea surface temperature. The main metric used to assess how accurate the predictions were in comparison to the observed values in the test set was the Root Mean Squared Error, or RMSE. The average extent of the discrepancies between projected and actual sea surface temperatures is shown by the root mean square error (RMSE), which is estimated to be around 0.2519. A model that fits the data better is shown by a lower RMSE.
Moreover, the model's performance is contextualised by comparing the RMSE to the original sea surface temperature series mean, which is roughly 27.9919. The comparatively low root mean square error (RMSE) compared to the mean suggests that the SARIMAX model has good accuracy and captures the underlying patterns and variations in the sea surface temperature time series.

The Ljung-Box and Jarque-Bera statistics, among other diagnostic tests, were also taken into account. A p-value of 0.59 from the Ljung-Box test for residual autocorrelation showed no significant autocorrelation. The residuals appear to have a normal distribution, as indicated by the p-value of 0.56 obtained from the Jarque-Bera test for residual normality. The general level of trust in the model's dependability is increased by these findings.






4.2 Arima
 
 
Using ARIMA modelling to analyse data on sea surface temperatures has produced some interesting findings. An ARIMA model with an order of (1, 1, 1) was trained on historical sea surface temperature data after data preparation and visualisation. The model's Mean Squared Error (MSE) of roughly 0.4632 indicates that it was able to produce accurate predictions on a test set.

The patterns and trends included in the dataset were brought to light using temporal visualisations of sea surface temperature and a comparison between air and sea surface temperature. Further information about the temporal dependencies in the sea surface temperature time series was obtained using autocorrelation and partial autocorrelation studies.


4.3 Regression
 
The Mean Squared Error (MSE) for the linear regression model is approximately 0.3156. The MSE is a measure of the average squared differences between the actual and predicted values. In this context, a lower MSE indicates a better fit of the model to the data.
The scatter plot visualizes the relationship between the actual sea surface temperatures (y_test) and the predicted sea surface temperatures (y_pred). Each point on the plot represents a data point from the test set, with the x-axis denoting the actual values and the y-axis denoting the predicted values


4.4 Classification
 




Results showing great promise have been obtained when a Random Forest Classifier is applied to forecast sea surface temperatures over a given threshold of 26.5 degrees Celsius. The classifier's accuracy, or the percentage of correctly categorised instances in the test set, was 97%. The thorough classification report offers a thorough rundown of the model's functionality:

Precision:

Class 0 (Below Threshold): 93%
Class 1 (Above Threshold): 98%
Recall:

Class 0: 92%
Class 1: 98%
F1-score:

F1-score for class 0: 92%
F1-score for class 1: 98%


LSTM

 

Model 1 demonstrates superior performance compared to Model 2 based on multiple evaluation metrics. It showcases lower error rates across MSE (0.23 vs. 0.577), RMSE (0.48 vs. 0.75), and MAE (0.37 vs. 0.61), indicating higher predictive accuracy and precision. Moreover, Model 1 exhibits lower MSLE (0.00028 vs. 0.00071) and Max Error (7.48 vs. 6.0181), emphasizing its capability in minimizing prediction discrepancies. Although Model 2 slightly edges in Explained Variance Score (0.836 vs. 0.9), Model 1 surpasses with a significantly higher R-squared score (0.9 vs. 0.75), indicating a better fit and higher variance explained by the model. Overall, Model 1 consistently outperforms Model 2 across a spectrum of metrics, portraying its robustness and accuracy in predictive modeling tasks.





















                                             The mean squared error for LSTM model is 0.26, which is significantly better than the rest of the methods we have followed





 



