# Cyclistic-2025-Data-Analysis-Case-Study

This project was completed as part of the Google Data Analytics Professional Certificate and demonstrates the practical application of data analytics techniques to solve a real-world business problem. In this analysis, I examined Cyclistic’s 2025 bike trip data to understand behavioral differences between annual members and casual riders. The objective was to identify data-driven strategies that could help convert casual riders into annual members and support long-term business growth.

**Business Problem:** Cyclistic’s marketing team wants to increase the number of annual memberships, as members are more profitable than casual riders.

**This project answers the following key questions:**
1. How do annual members and casual riders differ in their bike usage behavior?
2. Why might casual riders choose to purchase annual memberships?
3. How can Cyclistic leverage digital marketing strategies to influence casual riders to become members?

Tools & Technologies: Python (Numpy, Pandas, Matplotlib), Jupyter Notebook, Excel (for initial exploration)

**Data Source:**

The data has been made available by Motivate International Inc. under this [license](https://divvybikes.com/data-license-agreement). The data can be accessed [here](https://divvy-tripdata.s3.amazonaws.com/index.html). This project does not redistribute the raw datasets and is intended for educational purposes only.

I used the data consists of 12 monthly trip files for 2025, provided by Cyclistic (fictional company name). The data includes ride timestamps, station information, rideable type, and membership status. 

**Data Processing:**
* Combined 12 monthly datasets into a single consolidated dataset
* Converted timestamp columns to datetime format
* Created new features: ride_length, day_of_week, hour, month, and week_type
* Removed invalid and extreme outlier rides
* Aggregated data to improve visualization performance and clarity

**Key Findings:**
* Casual riders show strong seasonal patterns, peaking in summer months.
* Casual riders primarily ride on weekends and at tourist locations.
* Annual members show consistent usage throughout the year with peak activity during weekday commuting hours.
* Casual riders have longer average ride durations compared to members.

**Recommendations:**
1. Target high-frequency summer casual riders with seasonal membership promotions.
2. Promote cost savings to frequent weekend riders.
3. Use geotargeted marketing at high-traffic tourist stations.

**[Tableau dashboard](https://public.tableau.com/app/profile/san.winter/viz/Cyclisticbikesharecasestudy_membersvscasualriders/Cyclisticbikesharecasestudy_membervscasualriders)**

**Conclusion:**
The analysis reveals clear behavioral differences between casual riders and annual members. By focusing marketing efforts on high-usage casual riders during peak engagement periods, Cyclistic can increase membership conversions, improve customer retention, and drive long-term revenue growth.
