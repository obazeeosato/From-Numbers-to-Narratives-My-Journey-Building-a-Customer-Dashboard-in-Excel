# From-Numbers-to-Narratives-My-Journey-Building-a-Customer-Dashboard-in-Excel
![my dashboard](https://github.com/obazeeosato)
##  Project Objectives

- Understand purchasing behavior across different customer age groups.
- Identify top-performing product brands and categories based on revenue.
- Analyze the relationship between customer satisfaction and purchase intent.
- Examine revenue distribution across customer gender.
- Develop a dynamic, user-friendly dashboard for visualizing key insights.
- ##  Tools Used

- **Microsoft Excel 365** – For data cleaning, transformation, and analysis.
- **Power Query** – Used to clean and shape the dataset.
- **Pivot Tables** – For summarizing and aggregating data insights.
- **Excel Charts & Slicers** – For interactive visualizations and dashboard creation.

##  Methodology

1. **Data Cleaning**  
   - Removed duplicate entries.
   - Converted gender codes (0–1) to readable labels (Male–Female).
   - Formatted price values to currency.
   - Grouped customer ages into labeled age categories.
   - Transformed purchase intent (0–1) into "Unlikely to Buy" and "Likely to Buy".

2. **Data Exploration**  
   - Performed visual and statistical exploration to understand distributions.
   - Guided analysis using specific business-driven questions.

3. **Dashboard Creation**  
   - Built an interactive dashboard to uncover patterns and trends.
   - Used slicers for dynamic filtering based on brand, age group, gender, and category.
   - ##  Data Overview

The dataset used for this project is a simulated **Consumer Electronics Dataset** sourced from Kaggle. It provides detailed information about customer demographics, product details, and purchasing behavior in the consumer electronics sector.

### Key Fields in the Dataset Include:

- ProductID – Unique identifier for each product  
-  ProductCategory – Category of the product (e.g., Smartphones, Laptops)  
- ProductBrand – Brand of the product (e.g., Samsung, Apple)  
- ProductPrice – Price of the product in USD  
- CustomerAge – Age of the customer  
- CustomerGender – Gender of the customer (Male, Female)  
- CustomerSatisfaction – Satisfaction rating from 1 (Poor) to 5 (Excellent)  
- PurchaseIntent – Purchase likelihood ( Unlikely,  Likely)
- ## Data Preprocessing

To ensure the dataset was ready for analysis, the following preprocessing steps were taken:

1. Added a column to transform CustomerGender from binary 0–1 to categorical labels Male–Female for better readability.
2. Removed duplicate records to maintain data integrity.
3. Created an AgeGroup column to segment customers into relevant age brackets.
4. Formatted the ProductPrice column from numeric to currency format for clarity.
5. Added a new column to map PurchaseIntent values 0–1 to descriptive labels Unlikely Buy – Likely Buy.
6. Cleaned and transformed the data using Power Query in Excel for consistency and ease of use.
   ##  Key Insights

- Senior Adults (56–69) made the highest purchases, totaling $3,678,549.
- Samsung led in brand revenue with $2,907,674, followed closely by HP and Sony.
- Laptops were the top-selling product category with $2,804,346 in revenue.
- Female customers contributed slightly more to total revenue (51%) than males (49%), indicating both genders actively purchase electronics.
- Likely buyers accounted for 66% of total satisfaction ratings, showing a correlation between purchase intent and satisfaction.
- Product categories like Smartwatches and Headphones closely followed Laptops in performance, suggesting a balanced market interest.
##  Recommendations

- **Target Senior Adults**: Given their high spending, marketing efforts should focus more on customers aged 56–69.
- **Boost Brand Partnerships**: Strengthen relationships with top-performing brands like Samsung, HP, and Sony to drive more sales.
- **Enhance Female Engagement**: Since female customers slightly lead in revenue, personalized promotions and loyalty programs can further increase their engagement.
- **Leverage Satisfaction Insights**: Continue monitoring satisfaction levels to predict buying intent and improve customer experience.
- **Diversify Product Focus**: With competitive performance across laptops, smartwatches, and headphones, maintain a diverse product strategy.

##  Conclusion

This project uncovered key patterns in customer behavior using a consumer electronics dataset. Insights around age demographics, brand performance, product preferences, and gender-based spending were derived through structured analysis and dashboard visualization. These findings can support strategic decisions that drive targeted marketing, improve customer satisfaction, and increase sales.
## 📊 Technical Analysis

For a detailed walkthrough of the dashboard project and insights uncovered, view the full analysis on Medium:

👉 [From Numbers to Narratives: My Journey Building a Customer Dashboard in Excel](https://medium.com/@obazeeosato01/from-numbers-to-narratives-my-journey-building-a-customer-dashboard-in-excel-2e43c8541d11)
