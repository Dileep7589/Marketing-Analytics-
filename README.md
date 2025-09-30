# Marketing Analytics(Using SQL, Python and Power BI) #
## 1. Objective ##
To use marketing analytics to identify the factors behind ShopEasy’s reduced customer engagement, low conversion rates, and suboptimal customer feedback, and to provide data-driven recommendations that improve customer engagement, increase conversion rates, and enhance customer satisfaction while optimising marketing costs.

## 2. Challenges ##
Reduced Customer Engagement → Declining interactions with website & marketing content.

Decreased Conversion Rates → Visitors not converting into paying customers.

High Marketing Expenses → Rising campaign costs without expected ROI.

Lack of Customer Feedback Insights → Limited use of reviews/social media for improvements.

## 3. Key Performance Indicators (KPIs) ##
### Conversion Rate:
Percentage of website visitors who make a purchase.

### Customer Engagement Rate:
Level of interaction with marketing content (clicks, likes, comments).

### Average Order Value (AOV):
Average amount spent by a customer per transaction.

### Customer Feedback Score:
Average rating from customer reviews.

## 4. My Approach ## 
### 1. Data Extraction with SQL:
Performed data cleaning and created separate tables for structured datasets.
### 2. Joined Tables:

Combined multiple datasets (e.g., customer details, transaction logs, marketing data) using JOIN queries.

Ensured relationships (like CustomerID, ProductID) were used to merge records accurately.

### 3. Separated Key Records

Extracted specific fields into separate tables for clarity and analysis.

#### Example:
Comments Table → customer feedback, reviews.

Views Table → page views, clicks, impressions.

Transactions Table → orders, conversions, payments.

### Sentiment Analysis (Python in VS Code)

Imported cleaned data into Python environment.

Applied sentiment analytics using Python libraries (e.g., NLTK, TextBlob, or similar).

### Data Visualisation (Power BI)

Imported processed data from SQL Server into Power BI.

Designed interactive dashboards to visualize insights (engagement trends, conversion funnel, customer feedback patterns).

## 5. Outcomes ##

### Conversion Rate Trends

Identified seasonal peaks (e.g., January & July high conversions) and weak months (e.g., May lowest at 4.3%).

Pinpointed drop-off stages in the conversion funnel → helped suggest targeted interventions.

### Customer Engagement Insights

Engagement (views, clicks, likes) declined in later months.

Blog content generated highest views, but clicks and likes were relatively low → need for more engaging formats.

Click-through rate (15.37%) showed that users who engaged were still interacting effectively.

### Customer Feedback Analysis

Average rating ~3.7 (below target 4.0).

The majority of reviews were positive (4–5 stars), but recurring negative/mixed feedback highlighted improvement areas.

Sentiment analysis revealed opportunities to convert mixed reviews into positive experiences.

### Actionable Recommendations

Focus on high-performing products (e.g., Ski Boots, Kayaks) during peak months.

Experiment with interactive/social content to boost engagement.

Implement a feedback loop to address negative/mixed reviews and improve satisfaction.


The project delivered data-driven insights into conversion patterns, engagement trends, and customer feedback, which helped ShopEasy identify where to optimize marketing efforts and improve customer experience






