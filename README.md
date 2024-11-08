# Cars_24
## web scrapping and EDA using Python
The goal of this project is to analyze and predict car prices based on various features like brand, model, manufacturing year, distance traveled, location, fuel type, ownership status, and monthly EMI. The aim is to identify key factors that influence car pricing and build a predictive model that can estimate car prices accurately.
# Primary Objective:
- Analyze car prices based on features like brand, model, year, distance traveled, location, fuel type, ownership status, and EMI per month.
- Identify key factors that influence car prices, including brand, age of the car, fuel type, and other variables.
- Build a predictive model to estimate car prices accurately using machine learning algorithms.
- Perform data preprocessing by handling missing values, outliers, and encoding categorical variables.
- Conduct exploratory data analysis (EDA) to explore relationships between car price and other features.
- Provide actionable insights and recommendations based on the analysis results to optimize car pricing strategies.

# Website Overview :
![image](https://github.com/user-attachments/assets/e1c10c54-0124-4ba2-84a1-9d4311cd9e3a)

- Website Link : https://www.cars24.com/

# DATA PREPARATION
## Web_Scraping :
In this project, web scraping is used to collect data from online sources for further analysis and prediction. Here's how the process works:
- Using the Requests Library:
The Requests library is used to send HTTP requests to web pages and retrieve the raw HTML content. It allows us to easily extract the HTML code of a page, which serves as the foundation for extracting relevant information for car prices and other features.
- Using the BeautifulSoup Library:
After obtaining the HTML content, the BeautifulSoup library is used to parse and navigate the HTML structure. BeautifulSoup provides a simple and efficient way to extract specific data, such as car model, brand, price, fuel type, location, etc., from the page by selecting HTML elements like tags, classes, and IDs.

BeautifulSoup :
Easy to use: Simple API for common scraping tasks.

Handles broken HTML: Can parse and clean malformed HTML.

Powerful search: Easily find elements by tag, class, id, or attributes.

Efficient parsing: Quickly navigate and extract data from complex web pages.

EXPLORATORY DATA ANALYSIS :
UNIVARIATE ANALYSIS

BI-VARIATE ANALYSIS

MULTI-VARIATE ANALYSIS

CONCLUSION :
Maruti and Hyundai dominate the car market, indicating strong brand loyalty among consumers.

Most cars are priced under 7.5 lakhs, with prices inversely related to mileage.

Newer models (2022, 2019, 2017) retain higher resale value, comprising 63% of total cars.

First-owner cars have a wider price range and better value retention compared to second-owner cars.

Petrol vehicles are most prevalent, particularly in resale markets, with consistent price growth observed over time.

SUGGESTION TO BUYER:
Focus on buying popular brands like Maruti or Hyundai, particularly newer models from 2022, 2019, or 2017 for better resale value.

Target petrol cars with mileage between 20,000 km and 80,000 km, as they are the most available and commonly resold.

Opt for first-owner vehicles to ensure better maintenance and wider price distribution, enhancing overall value.

