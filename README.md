# online-retail-EDA
This was a Coursera exploratory data analysis project to learn data analysis and inspect a retail dataset from 2011-2012 using Python and Pandas to uncover trends in customer behavior, product performance, and sales patterns over time.

# Project Summary
This analysis explored patterns in online retail data from 2010–2011 to identify high-performing months, days of the week. THe analysis follows a structured approach to uncover key sales trends and customer behaviours.

## Key Findings
### Data Cleaning & Preparation
- Removed duplicate records and filtered transactions out with negative or extremely high quantities for data quality.
- Filtered out irrelevant columns down to Quantity, InvoiceDate, UnitPrice, and Country. Also removed Saturdays due to lack of sales activity, likely due to being closed.
- Created a revenue feature and extracted date components for time-based analyses.

### Top Performing Countries
- The UK dominates the market with the highest transactions and sales quantities.
- The next countries of note include the Netherlands, Germany, Ireland, and France, with distinct purchasing activity.

### Monthly Sales Trends
- November is the peak for sales quantities and transactions, likely due to holiday shopping.
- Autumn months have increased activity for the year, which suggests strong seasonality in customer demand.

### Daily and Weekly Sales Patterns
- With November as the highest selling month, I checked for the weekday with the highest selling quantities sold, which was Wednesdays and early to mid-week days being the highest point of activity.
- Across the whole year Thursdays were consistently seeing the most sales while Fridays and Sundays had noticably lower activity than the rest of the week.

### Average Daily Revenue
- Aligning with previous observations, November generates the highest average daily revenue.
- These revenue trends reinforce the importance of pushing business efforts during peak months.

### Business Implications
- This analysis points to UK as the primary market which suggest targeted marketing and resource allocation.
- The seasonal and weekly activity spike patterns present opportunities for increased inventory management, staffing, and promotional campaigns.
- These trends provide data to enable decision making to optimize business operations and maximize profitability.

This exploratory analysis provides insights into sales distribution, seasonal activity, and customer behaviour. It supports strategic planning for resource management, marketing, and logistics.


# Teck Stack
Python – Main programming language for analysis
Pandas – Data cleaning and manipulation
Matplotlib – Data visualization
Seaborn – Enhanced statistical plotting
Jupyter Notebook – Interactive analysis environment

# Requirements
pandas==2.3.1
numpy==2.3.1
matplotlib==3.10.3
seaborn==0.13.2
openpyxl==3.1.5
jupyter
ipykernel
