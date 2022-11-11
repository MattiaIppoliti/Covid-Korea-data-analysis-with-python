# CovidKorea

Utilized python for data analysis, starting from the dataset present at the link: https://www.kaggle.com/datasets/kimjihoo/coronavirusdataset/code?datasetId=527325. The final report is present in the .pdf file: Covid_Korea_Python_Data_Science.pdf.

### Pandas
Through the pandas library, histogram charts were used to represent which provinces within Seoul were most affected by the pandemic, with divisions by age and gender distribution. Furthermore, analyzes were produced with respect to the reasons for contagion and heat maps on distribution throughout Korea and the curves of confirmed cases with respect to the measures launched by the government. 
A very interesting analysis shows a distribution graph where the time band of contagion is shown on the abscissas while the age group is shown on the ordinates, where we can see a strong increase in infections in the working time bands compared to the age groups with greater number of workers. 

### SKLearn
Furthermore, through the SkLearn library, the dataset was divided into clusters using the K Means and PCA method, as well as performing a classification of searches on the online engines of the word coronavirus with words that refer to other types of disease, going to compare different algorithms such as Random Forest, Linear Regression, Gradient Boots, etc. through cross validation scores.

### StatsModel
Furthermore, a time series analysis was performed through the statsmodel library, in particular through the use of univariate autoregressive moving average (ARIMA) and seasonal SARIMAX models. The number of test cases carried out in the following months was predicted, starting from the partial autocorrelation graph and the autocorrelation graph, excellent results were obtained given by residual errors contained to an average close to zero and a uniform variance.

Finally, the last analysis carried out through the ARIMA model was through the forecast of movements within the province of seoul with double seasonality, i.e. a daily one with a decrease in movements at night and a weekly one with a decrease during the weekend. Going again to divide the model into training set and test set, this time too, low errors are obtained.
