# CoffeeClub-Customer-Segmentation-Analysis
A complete data analytics end to end customer segmentation project for The Cozy Place Coffee Club: From PostgresSQL data extraction to R-based, data cleaning, data modeling and clustering analysis to Power BI storytelling. Built to solve real business problems.

**Overview:** 
Coffee Club aims to better understand its customer base to design more effective marketing campaigns, personalize offers, and improve customer satisfaction and loyalty.
This project performs customer segmentation using transaction, offer, and demographic data stored in a PostgreSQL database, complemented with interactive reporting via Power BI.

**Objectives:**
* Segment customers into distinct groups based on demographics, spending patterns, and offer interaction.

* Identify actionable insights to tailor marketing strategies.

* Visualize results with an interactive Power BI dashboard for stakeholders.

**Data Sources**

* PostgreSQL Database (restored from provided backup)

* Customers table – demographic & membership data

* Offers table – details of promotions

* Events table – transactions & offer interactions

**Methodology**
* Data Extraction – Connect to PostgreSQL using RPostgres in R.

* Data Cleaning & Transformation – Handle missing values, join related tables, and engineer features.

* Segmentation – Apply clustering algorithms (e.g., K-means) to group customers.

* Analysis & Interpretation – Profile each segment, identifying key characteristics and value potential.

* Visualization – Build an interactive dashboard in Power BI for exploration and decision-making.

**Key Insights (Summary)**
* Cluster 1 – High-Value Regulars: Loyal, high-spending, responsive to complex offers.

* Cluster 2 – Deal Hunters: Price-sensitive, high purchase volume, prefer simple deals.

* Cluster 3 – Passive Users: Low engagement, need reactivation campaigns.

**Actionable Recommendations**

| Segment             | What to Offer                               | How to Reach Them               | Goal                              |
|---------------------|---------------------------------------------|----------------------------------|-----------------------------------|
| High-Value Regulars | Exclusive loyalty offers, subscriptions     | Email, personalized web dashboards | Retain & Upsell                   |
| Discount Seekers    | Flash deals, instant discounts              | Mobile, SMS                      | Increase conversions & retention  |
| Passive Users       | Reactivation campaigns, “We miss you” offers | Low-frequency emails              | Win back or clean list            |


**Dashboard Preview**
* The Power BI dashboard allows stakeholders to:

* Filter by customer segment

* View offer redemption rates

* Analyze spending trends

* Compare demographic breakdowns

**_Files included:_**

CoffeeClubDashboard.pbix – interactive dashboard file

CoffeeClubDashboard_August2025.pdf – static PDF export

**Tools & Technologies**
* Language: R (data wrangling, modeling, clustering)

* Database: PostgreSQL

* Visualization: Power BI

* Key R Packages: dplyr, ggplot2, cluster, RPostgres
  
**Contact**

For questions or collaboration opportunities:

**Stephen Kappo** - kappostephen@gmail.com

GitHub : Stepheen

X/Twitter handle : @StatsBySteff
