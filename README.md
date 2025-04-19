Task Objective:
Hello, I’m Rituraj. I am developing a strategic recommendation using Python for Julia, the
Category Manager, based on an in-depth data analysis of chip purchasing behavior.
The primary focus of this analysis is to identify key customer segments and gain insights into
who buys chips and what factors influence their purchasing decisions.
Key Definitions:
• LIFESTAGE: Represents the family and age stage of a customer (e.g., young singles,
families with kids, etc.).
• PREMIUM_CUSTOMER: Reflects a customer’s price sensitivity and brand
preference, helping to distinguish between value-conscious and premium-oriented
buyers.
Task Summary
Objective:
Provide a strategic, data-backed recommendation to Julia (the Category Manager) for the
upcoming category review. The focus is on understanding customer segments and chip
purchasing behavior.
Steps Covered in the Notebook (EDA.ipynb)
1. Data Import & Basic Cleaning
– Loaded two datasets: QVI_transaction_data.csv and
QVI_purchase_behaviour.csv.
– Merged datasets using LYLTY_CARD_NBR (loyalty card number).
2. Initial Data Exploration
– Checked for nulls, duplicates, and outliers.
– Cleaned up column formats (e.g., converting dates, standardizing names).
– Removed outliers from product quantities (e.g., suspiciously high pack sizes like
200 units).
3. Feature Engineering
– Extracted Pack Size and Brand Name from product names.
– Derived metrics like:
• Total spend per customer
• Average unit price
• Frequency of purchase
4. Customer Segmentation Analysis
– Grouped by:
• LIFESTAGE (e.g., young singles/couples, retirees)
• PREMIUM_CUSTOMER (budget vs. mainstream vs. premium)
– Analyzed:
• Average spend
• Number of transactions
• Popular chip brands by segment
5. Key Metrics Considered
– Spend per transaction
– Units per transaction
– Preference for premium or budget chips
– Frequency and recency of chip purchases
Key Initial Findings
• Mainstream mid-age families tend to spend more on chips overall.
• Premium customers pay more per packet and lean toward branded products.
• Budget-conscious young singles/couples buy more during promotions.
• Some brands or pack sizes are significantly more popular across all segments, indicating
strong brand loyalty or pricing attractiveness.
Strategic Recommendation
Use these insights to:
• Tailor promotions by customer segment.
• Increase visibility of premium products for premium customers.
• Offer family-sized packs or combo deals for family segments.
• Focus on high-performing brands when allocating shelf space.
