# Exploratory-Data-Analysis-on-Mercedes-Benz--UK-Used-Car-Sales
This repository contains an analysis of used Mercedes-Benz sales in the UK. Features like year, mileage, and engine size are included. Basic data cleaning was performed and machine learning techniques were used to analyze and predict car prices. The analysis includes insights on factors that influence the price of used Mercedes-Benz cars.


Overview:

This report presents an exploratory data analysis of UK-used Mercedes-Benz listings. The data, collected from Kaggle (https://www.kaggle.com/datasets/adityadesai13/used-car-dataset-ford-and-mercedes), includes features such as the year, mileage, engine size, and fuel type of the car, as well as the price at which it was listed.

Exploratory data analysis was conducted through visualizations and statistical analysis to identify trends and patterns in the data. This included Fuel Type and Engine Size Comparison Plots, a scatter plot with fuel types mapped to numeric values, and plots to identify the top and least popular models being sold over the year, as well as comparisons of sales of high- and low-mileage cars and trends in sales by transmission.

Model selection and training were then performed, evaluating the performance of linear regression, decision trees, and random forest models through mean squared error. Predictions of car sales were made for 10 listings from 2021 to 2022.

The results of the analysis showed that the linear regression model had the lowest mean squared error, indicating that it was the most accurate in predicting car prices based on the given features. Based on this, it can be concluded that year, mileage, and engine size are important factors in determining the price of a used car.

Results:

The trends in sales over time showed that sales of Mercedes-Benz cars generally increased over the years, with a particularly significant increase in sales in the last decade. The top and least popular models based on the number of sales were also identified, with the C Class being the top model and the 230 being the least popular model. The distribution of sales by transmission type was also examined, with semi-automatic transmissions being the most popular, followed by automatic and manual.

The top 5 models with the highest tax value were also identified, with the C Class and G Class being among the top models in 2013 and 2014, respectively. The sales of high-mileage and low-mileage cars were compared, and it was found that low-mileage cars had higher sales. The top-selling cars by model and year were also identified, with the C Class being the top seller in 2019 and 2017, and the A-Class being the top seller in 2019 and 2017.

The relationship between fuel type and engine size was also analyzed through the creation of scatter plots. It was found that diesel fuel had the highest average MPG for most engine sizes, while hybrid fuel had the highest average MPG for larger engine sizes. Petrol fuel had the lowest average MPG for most engine sizes.

Linear regression, decision tree, and random forest models were trained and evaluated based on their mean squared error. The linear regression model had the lowest mean squared error, indicating that it was the most accurate in predicting car prices based on the given features. Predictions of car sales were made for 10 listings from 2021 to 2022.

Conclusion:

This report has provided insights into the factors that influence the price of used cars and demonstrated the usefulness of machine learning techniques in analyzing and predicting car prices. In terms of recommendations, it would be beneficial to continue collecting data on used car listings and adding additional features to the dataset. This could potentially improve the accuracy of the machine-learning model in predicting car prices. Additionally, it would be interesting to further analyze the effect of fuel type on car prices, as this was not included as a feature in the current analysis.


