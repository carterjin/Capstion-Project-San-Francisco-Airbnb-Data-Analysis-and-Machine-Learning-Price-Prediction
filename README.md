# San Francisco Airbnb Data Analysis

### Table of Contents
- [Library used](#lib)
- [Files in this repo](#files)
- [Motivations](#motivations)

<a id='lib'></a>
### Library used
- numpy
- pandas
- urllib
- matplotlib
- seaborn
- folium
- scikit-learn
- xgboost
- keras

<a id='files'></a>
### Files in this repo

- [San_Francisco_Airbnb_Data_Cleaning.ipynb](https://github.com/carterjin/Capstion-Project-San-Francisco-Airbnb-Data-Analysis-and-Machine-Learning-Price-Prediction/blob/master/San_Francisco_Airbnb_Data_Cleaning.ipynb)

    Programmatically loaded data, changed incorrect data types, dropped empty/repeating/missing columns and save data to a pickle file.

- [San_Francisco_Airbnb_Exploratory_Analysis.ipynb](https://github.com/carterjin/Capstion-Project-San-Francisco-Airbnb-Data-Analysis-and-Machine-Learning-Price-Prediction/blob/master/San_Francisco_Airbnb_Exploratory_Analysis.ipynb)

    Explored the data, showed the code and detail in processing the data and producing visuals to answer business questions. Applied machine learning algorithm to predict price. 

- [San Francisco Airbnb Data Analysis Report.ipynb](https://github.com/carterjin/Capstion-Project-San-Francisco-Airbnb-Data-Analysis-and-Machine-Learning-Price-Prediction/blob/master/San%20Francisco%20Airbnb%20Data%20Analysis%20Report.ipynb)

    A report to a more general audience, only showing the most relevant visuals and analysis.
    
### Motivations

The object of this project is to help airbnb company and the hosts in San Francisco better understand location and price patterns and also suggest a pricing based on their housings. Some of the questions that I have analyzed are:

1. What are the locations that people rent airbnb?
2. How does neighborhood affect pricing?
3. Do superhosts provide a better renting experience?
4. Can we provide a prediction on pricing given the information we are provided, if so which method does that best?

### Conclusions

Our findings are:
1. Most airbnb rentals in San Francisco are in the north-east coastal areas.
2. Prices in most neighbors are skewed to the right. The Downtown/Civic area while having the lowest average price, shows a bimodal distribution. This suggests a gap between the rich and poor.
3. Superhosts in general provide better renting experience, their rating in all aspects were 0.2 - 0.4 higher in rating than regular hosts.
4. We have used multiple machine learning algorithms to successfully make an estimation for airbnb rent price. In which Neural Network Regression has the best performance with a 55% R2 score.