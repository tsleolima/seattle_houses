### Do you want to boost your Air bnb listings?

Applying the CRISP-DM process to solve business problems.

### Motivation

The central idea is, based on listings made using AirBnb, to analyze frequencies, distributions and insights that allow us to understand if there is any trend or pattern that relates this to the price of listings in the city of Seattle.

To do this, we will answer 3 questions

1. What is the seasonality and the trend of property prices in Seattle?
2. Which neighbourhood in Seattle have the highest price and why?
3. What influence does location and proximity to tourist attractions have on property prices?
4. How do property features, such as number of rooms, amenities or property type, affect prices?

### Libraries Used

pandas==2.0.3
matplotlib==3.7.2
seaborn==0.12.2
wordcloud==1.9.2

### Installation

This code runs with Python version 3.9.12 and requires some libraries, to install theses libraries you will need to execute

`pip install -r requirements.txt`

### File Description

**EDA.ipynb:** Notebook containing the data analysis
**plots:** Folder containing the plots used in medium post
**data/calendar.csv:** data containing the hiring day with price.
**data/listings.csv:** data containing information about the houses for rent.
**data/reviews.csv:** data containing reviews of each customer for the listings.

### Licensing, Authors, and Acknowledgements

**Data Source:** (Seattle Houses Dataset)[https://www.kaggle.com/datasets/airbnb/seattle/data]

**Post:** ()[https://medium.com/@miraxe/eda-seattle-houses-air-bnb-bussines-questions-6e8501df82eb]
