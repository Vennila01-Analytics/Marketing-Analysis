Marketing Analysis – Project Report
📌 Objective
To analyze the dataset of Shop Easy, an online E-commerce platform to uncover insights about declining user conversion rates, customer engagement and customer review feedback.
Business Case:
•	Shop Easy, an online retail business, is facing reduced customer engagement and conversion rates despite launching several new online marketing campaigns. They are reaching out to you to help conduct a detailed analysis and identify areas for improvement in their marketing strategies.
•	Key Points:
•	Reduced Customer Engagement: The number of customer interactions and engagement with the site and marketing content has declined.
•	Decreased Conversion Rates: Fewer site visitors are converting into paying customers.
•	Need for Customer Feedback Analysis: Understanding customer opinions about products and services is crucial for improving engagement and conversions.

🛠️ Tools & Technologies Used
- Power BI – for data modeling, transformation, and visualization
- Power Query Editor – for data cleaning and shaping
- DAX (Data Analysis Expressions) – for calculated columns and KPIs
- MS SQL Server – For Cleaning and Querying the required data (Data source).
- Python – For sentiment analysis (Data source).

🧹 Data Cleaning & Preparation (Power Query)
1. Column Renaming
   - Renamed columns to be more readable.
2. Data Type Conversion
   - Ensured correct data types.
3. Null Value Handling
   - Removed rows with missing or corrupted values.
4. Filtering
   - Removed tracks with popularity = 0.


📊 Data Modeling
1. Maintained a galaxy schema with three fact tables and two dimensions table along with newly created date table.
2. Created Calculated Columns / Measures using DAX
 
📈 Dashboard Design & Visualizations
1. KPIs:
   - Conversion Rates, Views, Clicks, Likes, Average Rating
2. Trend Analysis:
   - Line Chart for declining Views, Average Rating and Conversion Rate
3. Customer Engagement Analysis:
   - Funnel charts for distribution of Views, clicks, likes and conversion from views to purchase.
4. Interactive Filters:
   - Years, Date, Products and Sentiment Category
5. Scatter Plot:
   - Showed the distribution of customer reviews with average rating and linked it to table with products information along with their customer reviews.

📊 Key Insights Derived
Decreased Conversion Rate:
The conversion rate was quite good during the start of the year but gradually declined throughout the year and noticed a drastic dip during October. However, it had an impressing rebound again at December.
Stockholm noticed the least conversion rate, whereas Amsterdam has the highest conversion rate.
Reduced Customer Engagement:
There is an overall decline in social media engagement with views declining throughout the year.
While the clicks and likes are low compared to views, the click-through rate stands at 19.6% ensuring that engaged users are still interacting effectively.
Customer Feedback Analysis:
Customer Ratings have been consistent throughout the year standing at 3.69.
Although the ratings are stable, it is below the target of 4.0. Hence there is need for focused improvement on customer satisfaction for the products below 3.5 rating.



✅ Outcome
Created an interactive dashboard providing actionable insights into and solving problems in marketing strategies and emphasized focused marketing at seasonal month and underperforming products. Declared the need to address issues on lower performing months. Demonstrated skills in SQL, Python(Sentiment Analysis), Power BI, DAX, data cleaning, and storytelling for real-world analytics.
