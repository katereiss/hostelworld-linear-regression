# Predicting Hostel Prices in South America

## **Abstract**

One’s experience at a hostel depends on many factors. This project aims to explore these variables through linear regression, and to provide insights to backpackers and budget travelers who frequent hostels. Using features such as location, rating, and number of reviews, I built a linear regression model that predicts hostel price. 

## **Design**

The project is centered around predicting hostel price from a variety of features available on HostelWorld and Wikipedia. 

## **Data**

This project's data was scraped from hostelworld.com/hostels/ using BeautifulSoup and looping through a list of cities in South America. Additionally, I added a table from Wikipedia of all 80 cities in South America with populations of over 500,000 in order to distinguish hostels in large cities, a feature of my model. After cleaning the data to remove hostels with obviously incorrect values, the dataset included 1,001 hostels. The initial features were country, distance from city center, number of reviews, average rating out of 10, and if the hostel is located in a large city.

## **Algorithms**

*Models* 

I built, refined, and tested Linear Regression, Ridge, and Lasso models to compare their performances. All models performed similarly.

*Feature Engineering*

Added a polynomial feature and a combined feature, neither of which made much of a difference in the model. 

One-hot-encoded the categorical variable country into binary dummies so it could be included in the model.

Removed a collinear feature.

*Model Evaluation & Selection* 

The dataset was split, trained, and validated with 5-fold cross-validation, and evaluated with R squared and Mean Absolute Error. 

## **Tools**

Scraping: BeautifulSoup 

Data Manipulation: Numpy, Pandas 

Modeling: Scikit Learn

Plotting: Matplotlib & Seaborn

## **Communication**

I delivered a 5-minute presentation on this project. Slides and code are included in this repo.
