# CARS24 Car Price Analysis and Prediction

## Project Overview
This project involves web scraping data from the CARS24 website, performing exploratory data analysis (EDA), and building predictive models to determine key factors that influence car prices. The insights derived aim to guide buyers in making informed purchasing decisions based on car features and pricing trends.

# Website Overview :
![image](https://github.com/user-attachments/assets/e1c10c54-0124-4ba2-84a1-9d4311cd9e3a)

- Website Link : https://www.cars24.com/

## Table of Contents
1. [Objective](#objective)
2. [About the Dataset](#about-the-dataset)
3. [Data Collection](#data-collection)
4. [Data Preparation and Preprocessing](#data-preparation-and-preprocessing)
5. [Exploratory Data Analysis](#exploratory-data-analysis)
6. [Insights and Recommendations](#insights-and-recommendations)
7. [Usage](#usage)
8. [Conclusion](#conclusion)


## Objective
The goal of this project is to analyze and predict car prices on the CARS24 platform by examining features such as:
- **Brand and Model**
- **Manufacturing Year**
- **Distance Traveled (Mileage)**
- **Location**
- **EMI Per Month**
- **Fuel Type**
- **Ownership Status**

## Team Members
- **B. Vamsi Krishna:** B.Tech in Computer Science and Engineering, recently completed Data Analytics course at Innomatics Research Labs.
- **D. V. Sriram:** B.Tech in Electrical and Electronics Engineering, recently completed Data Analytics course at Innomatics Research Labs.
- **A. Sasi Kumar:** B.Tech in Electrical and Electronics Engineering, recently completed Data Analytics course at Innomatics Research Labs.

## About the Dataset
The dataset contains information scraped from the CARS24 website and includes 500 records with the following columns:
- **Brand** - Car manufacturer
- **Model** - Car model
- **Year** - Manufacturing year
- **Distance Traveled** - Mileage of the car
- **Location** - Car's location
- **EMI** - Estimated EMI per month
- **Fuel Type** - Type of fuel (Petrol, Diesel, CNG, etc.)
- **Ownership** - Number of previous owners
- **Price** - Price of the car

## Data Collection
Data was scraped from [CARS24](https://www.cars24.com/) using:
- **Requests Library** - To retrieve HTML content.
- **BeautifulSoup** - For parsing and navigating the HTML structure.

### Why BeautifulSoup?
- **Ease of Use:** Simple API for common scraping tasks.
- **Robust Parsing:** Handles broken and malformed HTML.
- **Powerful Search Capabilities:** Easily locate elements by tag, class, ID, or attributes.

## Data Preparation and Preprocessing
- **Data Cleaning**: Handled missing values in columns like `Owner` and `Location`. Converted non-numeric columns (`Price`, `Distance`, `EMI`) to numerical formats.
- **Encoding Categorical Variables**: Encoded categorical features to prepare data for analysis.
- **Outlier Detection**: Identified and handled outliers in price and mileage columns.

## Exploratory Data Analysis
### Univariate Analysis
- **Top Car Brands**: Maruti, Hyundai, Honda, Tata, and Ford.
- **Price Range**: Majority of cars are priced below 7.5 lakhs.
- **Popular Models**: Baleno, Nexon, Swift, City, Ecosport.
- **Mileage Range**: 20,000 km to 80,000 km.

### Bivariate and Multivariate Analysis
- **Brand vs Price**: Mahindra has a wide price range; MG brand has the highest starting prices.
- **Fuel Type vs Price**: Petrol cars have the widest price range; diesel and CNG follow.
- **Ownership vs Price**: First-owner cars generally command higher prices.

## Insights and Recommendations
1. **Popular Brands**: Maruti and Hyundai have strong resale values, reflecting brand loyalty.
2. **Preferred Models and Years**: Newer models (2022, 2019, 2017) retain value well.
3. **Fuel Type**: Petrol cars are most commonly available, especially for resale.
4. **Buying Advice**: Target first-owner, petrol-fueled cars within the mileage range of 20,000 to 80,000 km for better value.

## Usage
1. **Web Scraping**: Run the provided Jupyter Notebook to scrape data from the CARS24 website.
2. **Data Preprocessing**: Follow data cleaning and transformation steps outlined in the notebook.
3. **Analysis and Visualization**: Perform EDA to uncover insights using the notebook’s analysis functions.

## Conclusion
This project reveals key insights into the used car market on CARS24, helping buyers make data-driven choices. Maruti and Hyundai cars are highly popular, with certain newer models holding value well in the resale market. First-owner, petrol-powered cars tend to offer the best value within the price range.

