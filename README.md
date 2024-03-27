# EDA---Black-Friday

**Data Story: Exploring Customer Purchase Behavior**

In our exploration of a dataset detailing customer purchases, we embarked on a journey to uncover insights into consumer behavior, demographic trends, and product preferences. Let's walk through the stages of our exploratory data analysis (EDA) project to understand the nuances of our dataset.

**Dataset Walkthrough:**
Upon initial inspection, we encountered missing values primarily in the `Product_Category_2` and `Product_Category_3` columns. To prevent potential data loss, we opted to drop these columns, ensuring our subsequent analyses are based on complete data.

**Analyzing Columns:**
Delving deeper into our dataset, we utilized functions like `unique()` and `nunique()` to examine individual columns. By applying these functions to columns such as `User_ID` and `Product_ID`, we gained insights into the total number of customers and products in our dataset, respectively. Similarly, exploring categorical columns like `Gender` and `Age` provided us with a glimpse into the diversity of our customer base.

**Analyzing Gender:**
Our focus shifted to gender analysis, where we observed a significant disparity between male and female representation in our dataset. Leveraging `groupby()` functions, we discerned purchasing patterns between genders, visually presenting our findings through pie charts and bar plots.

**Analyzing Age & Marital Status:**
Further investigation into age and marital status unveiled intriguing trends. Utilizing `groupby()` functions, we identified age groups with the highest purchasing activity and explored the distribution of marital status among our customers. Visual representations in the form of pie charts aided in understanding these demographic dynamics.

**Multi-Column Analysis:**
Transitioning to multi-column analysis, we employed Seaborn to visualize the interplay between age and gender. By incorporating the `hue` parameter, we effectively showcased nuanced relationships within our data, offering deeper insights into customer segmentation.

**Occupation and Products Analysis:**
Our exploration extended to occupation and product-related insights. Leveraging countplots and bar plots, we uncovered trends in product categories and identified popular products based on purchasing frequency. This analysis provided valuable insights into consumer preferences and market demand.

**Combining Gender & Marital Status:**
In our final exploration, we merged gender and marital status to gain a holistic view of customer demographics. Through visualization techniques like countplots, we explored the intersection of gender and marital status, offering comprehensive insights into consumer behavior.

**Conclusion:**
Our EDA journey unearthed a wealth of insights regarding customer purchase behavior. From demographic trends to product preferences, each stage of analysis contributed to a deeper understanding of our dataset. Armed with these insights, businesses can tailor their strategies to better cater to their target audience, ultimately driving growth and success.
