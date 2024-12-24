# Assignment
## Project Description
The objective of this project is to analyze datasets related to user behavior, cooking preferences, and order trends. By cleaning and merging the provided datasets, we aim to uncover meaningful insights into the relationship between cooking sessions and user orders, identify popular dishes, and understand how demographic factors influence user behavior. 

The project outcomes include actionable insights, Dashboard using PowerBI, and Business recommendations, with all files organized in a GitHub repository.
## Steps Performed

### 1. Data Cleaning
- Checked for missing, duplicate, or inconsistent values.
- Verified data consistency across all datasets.

### 2. Data Merging
- Merged datasets using `User ID` and `Session ID` as primary keys.
- Resolved duplicate columns (e.g., `Dish Name_x` and `Dish Name_y`) by renaming or dropping as necessary.

### 3. Data Analysis
#### Relationship Between Cooking Sessions and Orders
- Calculated the average session rating for completed orders.
- Analyzed conversion rates of cooking sessions to orders.
- Investigated the impact of session duration on order completion.

#### Popular Dishes
- Identified the most frequently ordered dishes.
- Examined dish preferences for sessions that led to completed orders.

#### Demographic Influence on User Behavior
- Explored how age and locationimpact session ratings and order trends.

## PowerBI Dashboard
![Screenshot (203)](https://github.com/user-attachments/assets/b2a1751f-ce4b-481e-b828-66d4ee80d1d9)

### KPI’S: 
#### Order Completion Rate:
High completion rate of 87.5% indicates that most users who start cooking sessions complete their orders.
#### Average Rating:
Sessions have an impressive average rating of 4.5, suggesting high user satisfaction with the cooking experience.
#### Average Session Duration:
The typical session lasts around 30.31 minutes, aligning with user engagement and time investment.
#### Average Cooking Session Duration by Meal Type:
Dinner sessions have the longest average duration, followed by lunch and then breakfast.
This indicates users dedicate more time to dinner preparation, possibly due to its complexity or the importance of evening meals.
#### Relationship Between Session Duration and Repeat Orders:
Users with shorter session durations are less likely to place repeat orders.
Longer sessions correlate with higher repeat orders, emphasizing the importance of user engagement during cooking.
#### Orders by User Demographics:
Age Group 20–29 has the highest number of completed orders, showcasing strong engagement from younger users.
Age Group 40+ has fewer completed orders, indicating lower adoption or activity levels.
#### One-Time vs. Repeat Customers:
81.25% of customers are repeat users, reflecting strong retention and loyalty.
Only 18.75% are one-time users, suggesting room to convert these users into repeat customers with tailored strategies.
#### Frequency of Cooking Sessions by Meal Type:
Dinner sessions dominate, followed by lunch and breakfast, reinforcing that dinner is the most popular cooking time.
Breakfast has the least engagement, possibly due to time constraints in the morning.
These insights can guide strategies to improve user engagement, retention, and overall platform performance.

Also created a detailed documentation of this.

#### Tools Used:
Jupyter notebook : For exploratory data analysis using python
Library : pandas
PowerBI : for visualization
Excel : Initial exploration of the dataset



