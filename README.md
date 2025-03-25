# Zomato Restaurant Data Analysis 
# Project OverView 
This project analyzes a dataset of 148 restaurants to uncover key trends related to customer preferences, ratings, pricing, and online ordering behavior. Using Python, Pandas, Matplotlib, and Seaborn, insights were extracted to assist businesses in understanding market trends and optimizing operations.
# Technologies Used 
Programming Language: Python

Libraries: Pandas, NumPy, Matplotlib, Seaborn

Data Source: CSV file containing restaurant details
# Data Cleaning & Preprocessing

Handled missing values by checking null values (df.isnull().sum()).

Standardized rating format by removing /5 from the rate column.

Converted data types for accurate numerical analysis.
# Key Insights & Visualizations

1. Most Popular Restaurant Type

Used sns.countplot() to visualize the distribution of restaurant types.

Conclusion: Majority of restaurants belong to the Dining category.

2. Customer Votes per Restaurant Type

Aggregated total votes for each restaurant type using groupby().

Conclusion: Dining restaurants received the highest number of customer votes.

3. Rating Distribution

Created a histogram of restaurant ratings using plt.hist().

Conclusion: Most restaurants received ratings between 3.5 and 4.0.

4. Average Spending per Couple

Analyzed approx_cost(for two people) using sns.countplot().

Conclusion: The majority of couples prefer restaurants with an average cost of ₹300.

5. Online vs. Offline Ratings

Compared average ratings for online vs. offline orders using sns.barplot().

Conclusion: Offline orders received lower ratings compared to online orders.

6. Restaurant Type vs. Offline Orders

Created a heatmap to analyze which restaurant types accept more offline orders.

Conclusion: Dining restaurants primarily accept offline orders, whereas Cafes receive more online orders.

# Final Takeaways

Dining restaurants dominate customer preferences in terms of votes and offline orders.

Online ordering has a higher rating, indicating better customer satisfaction.

Affordable pricing (₹300 range) is preferred by most couples.

Data visualization helped uncover meaningful trends, assisting businesses in strategic decision-making.

# Future Enhancements

Perform sentiment analysis on customer reviews.

Predict restaurant success rates using machine learning models.

Expand analysis to different cities or cuisines for deeper insights.


