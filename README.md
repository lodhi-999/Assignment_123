# Data Analysis Report

This project involves cleaning, merging, and analyzing datasets to gain insights into user behavior, meal preferences, and order trends. Below is a summary of the steps taken and key findings:

## Steps Performed

1. **Data Cleaning**:
   - Removed rows with inadequate or missing data from the `OrderDetails` sheet to ensure data integrity.

2. **Data Merging**:
   - Merged relevant data from all three sheets using Vlookup & Index- Match funtions (`UserDetails`, `CookingSessions`, and `OrderDetails`) into a consolidated table called **MergedData** in the `OrderDetails` sheet for easier analysis.

3. **Analysis of Popular Dishes and Meal Types**:
   - The `OrderDetails` sheet highlights:
     - Popular dishes based on user orders.
     - Share of meal types (e.g., Breakfast, Lunch, Dinner) to understand user preferences.

4. **Meal Types by Location**:
   - The `Meal Types by Location` sheet provides insights into how diverse users from different locations prefer specific types of meals:
     - For example, Dinner is more popular in New York, while Los Angeles shows preferences across all meal types.

5. **Orders vs. Sessions by Users**:
   - The `Orders vs. Sessions by Users` sheet analyzes the relationship between **Total Sessions** (from `CookingSessions`) and **Total Orders** (from `OrderDetails`):
     - Highlights user engagement levels and their likelihood to place orders after participating in cooking sessions.

6. **Demographic Patterns**:
   - The `Demographic Patterns` sheet explores:
     - Choices of meals segmented by age groups.
     - Location-based trends in meal preferences.

---

## Key Insights

- **Meal Preferences**:
  - Dinner is the most popular meal type, especially in New York.
  - Los Angeles demonstrates diverse preferences, appearing across Breakfast, Lunch, and Dinner.

- **User Engagement**:
  - Users with more cooking sessions tend to place more orders, indicating the sessions' influence on driving purchases.

- **Demographics**:
  - Age groups and location play a significant role in determining meal preferences, showing distinct trends across different regions.

---

## Visualizations
- Visualizations for the insights mentioned above (e.g., bar charts, pie charts, and trends) can be found in the respective sheets of the Excel file.
