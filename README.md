# Gustavo Santos
Data Science Portfolio of Gustavo R Santos

# | PROJECT 1
## [Car Prices Regression Analysis](https://github.com/gurezende/Car_Prices_Regression_Streamlit)

This is a complete Regression Analysis Project where I demonstrate the exploratory data analysis as well as train a Random Forest Regression model to estimate prices of cars in Brazil.

The main skills demonstrated in this project are:
* *Data Collecting*: I have collected data from the internet to create this dataset with 1352 observations. The data was collected on August, 2021.
* *Data Cleaning*: I have cleaned, parsed, formatted the data to make it ready for modeling.
* *Exploratory Data Analysis*: I have done the descriptive statistical analysis, univariated and bivariated analysis to understand the dataset.
* *Data Visualization*: Several graphics plotted (bars, boxplots, scatterplots etc
* *Data inputation*: I've inputed data using ML prediction with Random Forest from missingpy library.
* *Outliers*: I have identified and removed outliers for better performance of the model.
* Testing and Fitting: There are 5 models in this project and they were improved at each iterations with Feature Engineering, Cross Validation and Grid Search techniques, reaching a 95% of Explained Variance (R-Squared)
* The Project ends with a Web App created with Streamlit.

[Visit the Web App here](https://share.streamlit.io/gurezende/car_prices_regression_streamlit/main/ConsultorVirtualCarros.py)

![](/images/consultorScreenshot.png)

---

# | PROJECT 2
## [Finance-App-with-Streamlit](https://github.com/gurezende/Finance-App-with-Streamlit)

This project has two parts:
1. Performed a complete Data Analysis of a Financial tracking file and built a classification model with Logistic Regression. 
   The model predicts the probability of a given project to end the year within the approved budget. **The accuracy is 93%**.
2. The second part is a Web App created with Python and Streamlit where the user can upload a file with forecast inputs to get a couple of graphics with comparison between the projects and the average of the portfolio, as well as to find the predictions whether the projects uploaded will or will not meet the budget.

See more information in this [link](https://datasciencegus.wordpress.com/2020/07/10/finance-web-app-with-streamlit/) or [visit the app](https://finance-streamlit.herokuapp.com)

![](/images/Financestreamlit.png)

---

# | PROJECT 3
## [Wine_Quality_Predictions](https://github.com/gurezende/Wine_Quality_Predictions)
In this project, the idea was to simulate a business problem where a client (winery) had some data about their products and they wanted to see how the variables measured could possibly affect the wine quality, therefore, resulting in higher or lower grades for their wines. Then the client wanted to have their dataset divided in two clusters (white and red wines) and finally see some predictions about the quality for their new wines. It was all developed in R language, using R to build the app.
The work was divided in 3 main parts:
1. Exploring the data and creating some data visualizations, understanding the correlations between variables.
The result is on the first three tabs of the app: *Histograms, Boxplots and Report*.
2. Divide the dataset in two clusters. I have gathered both datasets (red + white) to simulate a request from the client where they needed to know which wine was what kind. The result was 98% accurate and that can be seen on the *Clustering* tab.
3. The final part was to create a Prediction Interactive Tool for the White Wines from the dataset that allows the client to input some values and have a prediction whether that wine is going to be qualified as High Quality (grades from 7-10) or Low Quality (grades from 3-6). You can interact with the tool in the tab *Predictions*. **The accuracy is 95%**.

See more information in this [link](https://datasciencegus.wordpress.com/2020/07/16/wine-quality-project-with-rshiny/) or [visit the app](https://gurezende.shinyapps.io/wine_quality_project/)

![](/images/WineQualityApp.png)

---

# | PROJECT 4
## [Predicting Employee Turnover of a Business](https://github.com/gurezende/Predict-Turnover-Company)
This is a Project from the Data Scientist Program Degree by Data Science Academy Brazil. The idea is to build a classification model to predict if an employee will or not leave the company based on the variables satisfaction level, number of projects one is working, number of hours worked in a month and the years this person is in that company.

Activities performed:
* Data Exploration and Analysis
* Data Visualization (Histograms, Boxplots, Barplots)
* Correlation check
* Feature Engineering with Random Forest to select the best attributes for the model
* Classification: Training and Prediction with Random Forest **(99% accurate)** and XGBoost **(97% accurate)**
* (Creation of Random Forest and XGBoost with tidymodels)
* Creation of a Shiny App for user interaction and make predictions.

Learn more about this project [link](https://bit.ly/2QguEFX) or [visit the Shiny app](https://gurezende.shinyapps.io/HRAnalytics-Turnover/)

![](/images/EmployeeTurnover.png)


---

# | PROJECT 5
## [Bible Word Clouds](https://github.com/gurezende/Bible_WordClouds)
This project was created in R Language.
- Created a word cloud for each book in the Holy Bible.
  * Used for lops
  * Saved results in a PDF.



---

# | PROJECT 6
## [NYC-Airbnb](https://github.com/gurezende/NYC-Airbnb)
In this project, I was able to do a complete analysis with data exploration and visualization study on the *'New York City Airbnb Open Data'*.
- Created some plots to show the data and extract insights
  - Boxplots, histograms, bar graphics
  - Created a Map using Folium package with the locations of the places for rent and added HeatMap by price 
- Did a simple Natural Language Processing with nltk to analyze the reviews of the rentals.
  - Word Cloud, word frequence count, Bigrams and Trigrams analysis.
- Wrote a Conclusion Report.

See more information in this [link](https://bit.ly/2EdKHSe).

![](/images/mapprojairbnb.png)


---

# | PROJECT 7
## [Recommendation Systems](https://github.com/gurezende/Studying/tree/master/MIT/Module4)

In this project, I have created three different types of Recommendation Systems using Python and the **surprise** package.
* I have created a Popularity Based Recommender
* Created an Item-Based Recommender: Collaborative Filtering
* Created a Model-Based Recommender with SVD algorithm (matrix factorization).

Learn more about this project: [link](https://bit.ly/3oplvL6)

![](/Studying/MIT/Module4/quantiles.png)

---

# | PROJECT 8
## [Tweet's Analysis](https://github.com/gurezende/Studying/tree/master/Python/SentimentAnalysis)

In this project, I have extracted 100 tweets using Tweepy to analyze them.
Activities performed:
* Data extraction from Twitter using Tweepy
* Data Exploratory Analysis including manipulation of dates, text and numbers
* Data Visualization of locations with most tweets, date and hours when people tweet the most about the given subject
* Natural Language Processing using nltk package, being able to create Word Cloud, frequency count and N-Grams analysis
* Topic Analysis of the text using LDA algorithm
* Sentiment Analysis using Text Blob

![](/SentimentAnalysis/FL-wordcloud.png)

---

# | PROJECT 9
## [CSV_to_Parquet_Program](https://github.com/gurezende/CSV_to_Parquet_Program)
Windows application that converts files from CSV to Parquet format or Parquet to CSV.

The main points learned with this project were:
* Learn how to create a GUI (Graphic User Interface) using the *tkinter* Python package.
* Learn something about creating a software, the steps, options offered to the user and programming structure.
* Create a Windows application to help people converting their files from CSV to Parquet compressed file format.

Currently, CSV is one of the most popular data files, as it is easily shareable and many Data Analysis programs can read it. Ergo, the CSV file format became very popular. However, the downside is that the format takes a lot of space in disk. As the number of rows start to increase, the file size grows accordingly. When you have more than 10 thousand rows you start to see the difference between CSV file size and Parquet file size - *.parquet was 5 times smaller in a test with a 5GB csv file.*

This program is available Free for Use under the MIT license, meaning it can be used, copied or changed for personal or commercial use. 
I only ask that my name is mentioned in the credit.

![](/images/csv_to_parquet.png)

