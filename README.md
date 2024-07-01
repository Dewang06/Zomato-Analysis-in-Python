
# Zomato-Analysis-in-Python

### Project file Link : https://github.com/Dewang06/Zomato-Analysis-in-Python/blob/main/Zomato%20Analysis%20%26%20Visualization.ipynb

## Problem Statement

In the competitive landscape of Bengaluru's restaurant industry, understanding consumer preferences and market trends is crucial for businesses to thrive. This project, "Zomato Sales Analysis," aims to uncover valuable insights from Zomato's sales data in Bengaluru to help restaurant owners, marketers, and stakeholders make informed decisions.

By thoroughly analyzing and visualizing the data, this project seeks to address the following problems:

- Identify the pricing trends and preferences for different cuisines.
- Determine the impact of online ordering on pricing and customer preference.
- Recognize the most esteemed and popular restaurants within specific price ranges.
- Evaluate the significance of restaurant booking options on customer choices.
- Provide actionable insights to help restaurant businesses optimize their offerings, pricing strategies, and marketing efforts.
- The goal is to empower restaurant businesses in Bengaluru to enhance customer satisfaction, increase sales, and achieve sustainable growth in the highly competitive food industry.

### Steps followed 

- Step 1 : Imported the resturant.xlsx file into Jupyter Notebook.
- Step 2 : The cleaning process, using pandas, involved the following steps:
    - `Removing irrelevant columns`
    - `Eliminating duplicate records`
    - `Cleaning values using regular expressions`
    - `Filling null values with statistical methods`

### Table after the cleaning process is complete.

![cleaned_table](https://github.com/Dewang06/Zomato-Analysis-in-Python/assets/91787570/be24c61e-25d7-4b62-aefb-7b784ddd70f7)
        
- Step 3 : Insights were gained from the cleaned data using pandas after thorough analysis.
- Step 4: Following the analysis, insights were visualized using matplotlib and seaborn libraries.

# Insights

Insights were gained from the cleaned data using pandas after thorough analysis.

Following inferences can be drawn from the code:

- Top-ranked cuisines average Rs 1000; least favored average Rs 500.
- Online orders, 10% cheaper, drive higher preference.
- The pricing for the highest and lowest-rated restaurants is similar, indicating that ratings are influenced by factors other than pricing.
- We observed the distribution of restaurants across different locations, noting that "1947" has a significant presence throughout the city.
- Restaurants offering bookings are vastly preferred, capturing 86% of votes.
- Belgian Waffle Factory is the highest esteemed affordable option under Rs 500, while 1947 operates the most city locations with top ratings.

# Visuals Snapshot

### Some of the key Visuals are as follows:

#### 1.) Online orders are slightly more preferred due to their cost-effectiveness, making them the best option for busy individuals.
![Average_votes](https://github.com/Dewang06/Zomato-Analysis-in-Python/assets/91787570/c2fd59a9-d7c3-40f6-9479-e4b059d3b5f7)

#### 2.) It makes it easy to know highest rated cuisins in each restraunt to know the best each one offer
![best_cuisine_by_rest](https://github.com/Dewang06/Zomato-Analysis-in-Python/assets/91787570/795ad70a-6825-4b48-a053-70d1f3571058)

#### 3.) Average cost of biryani in all restraunt helps us choose the best option suited for our budget. Biryani is among the most popular cuisine hence its important to have some insights to improve sales.
![avg_biryani cost](https://github.com/Dewang06/Zomato-Analysis-in-Python/assets/91787570/524fccac-dd1d-4ef1-b765-2ba943216923)

#### 4.) As we can see the pricing for most rated and least rated restraunts are roughly the same hece ratings do not depends on the pricing and other factors are involved in ratings of the restraunts.
![ratings_vs_pricing](https://github.com/Dewang06/Zomato-Analysis-in-Python/assets/91787570/60a7c5a2-3ec7-4181-a7d0-cb547614de4a)

#### 5.) We observed the distribution of restaurants across different locations, noting that "1947" has a significant presence throughout the city.
![rest_by_locations](https://github.com/Dewang06/Zomato-Analysis-in-Python/assets/91787570/d81a5688-654f-4e39-a974-a8ec72c91513)
## Tools and Technologies Used

**Jupyter Notebook:** A web-based interactive computing environment that allows users to create and share documents containing live code, equations, visualizations, and narrative text.

**Python:** A high-level programming language known for its simplicity, readability, and versatility in application across various domains, including web development, data analysis, artificial intelligence, and more.

**Pandas:** A powerful Python library for data manipulation and analysis, offering data structures and operations for manipulating numerical tables and time series data efficiently.

**Matplotlib:** Matplotlib is a comprehensive plotting library for creating static, animated, and interactive visualizations in Python.

**Seaborn:** Seaborn builds on Matplotlib's functionalities and provides a high-level interface for drawing attractive statistical graphics.