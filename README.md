# Cyclist_Dataset
## Scenario
You are a junior data analyst working in the marketing analyst team at Cyclistic, a bike-share company in Chicago. 
The director of marketing believes the company’s future success depends on maximizing the number of annual memberships. 
Therefore, your team wants to understand how casual riders and annual members use Cyclistic bikes differently.
From these insights, your team will design a new marketing strategy to convert casual riders into annual members.
But first, Cyclistic executives must approve your recommendations, so they must be backed up with compelling data insights and professional data visualizations.
## About the company 
In 2016, Cyclistic launched a successful bike-share offering. Since then, the program has grown to a fleet of 5,824 bicycles that are geotracked and locked into a network of 692 stations across Chicago.
The bikes can be unlocked from one station and returned to any other station in the system anytime. Until now, Cyclistic’s marketing strategy relied on building general awareness and appealing to broad consumer segments.
One approach that helped make these things possible was the flexibility of its pricing plans: single-ride passes, full-day passes, and annual memberships. 
Customers who purchase single-ride or full-day passes are referred to as casual riders. Customers who purchase annual memberships are Cyclistic members. 
Cyclistic’s finance analysts have concluded that annual members are much more profitable than casual riders. 
Although the pricing flexibility helps Cyclistic attract more customers, Moreno believes that maximizing the number of annual members will be key to future growth.
Rather than creating a marketing campaign that targets all-new customers, Moreno believes there is a very good chance to convert casual riders into members. 
She notes that casual riders are already aware of the Cyclistic program and have chosen Cyclistic for their mobility needs.
### Business Task
Design marketing strategies aimed at converting casual riders into annual members. In order to do that, however, the marketing analyst team needs to better understand how annual members and casual riders differ, why casual riders would buy a membership, and how digital media could affect their marketing tactics. 
Data source: for the purpose of this project, the divvy-tripdata (January - June 2022) was downloaded from https://divvy-tripdata.s3.amazonaws.com/index.html
Therefore only 5 months of previous Cyclistic data was adopted for this study.
## Data Cleaning/ Analysis:
Each Month data was downloaded and the Week Day & Ride Length columns were calculated. The data from each month was formatted to have matching column positions and titles to enable effective joining in SQL. The data was joined, sorted and manipulated using SQL. See query in my github profile: https://github.com/Kelechi-Okezie/Cyclist_Dataset
The resulting tables from the SQL queries were loaded into tableau and represented with bar charts as shown on tableau public: https://public.tableau.com/app/profile/kelechi.okezie/viz/CyclistDataDashboard/Dashboard1?pu
## Summary/Key Findings:
1.	Cyclistic had more annual members (972,878) than casual members (536,650). 
2.	Casual members rode the bikes for longer times (average of 1482.8 seconds ride length) compared to the annual members (average of 722 seconds ride length). 
3.	More annual members used the bikes on week days while more casual members used the bikes on weekends.
4.	Based on bike type, 53% of annual members used classic bike (compared to the 47% that used electric bike). Also 49.1% of casual members used electric bikes compared to the 41.76% and 9.17% that used classic and docked bikes respectively. 
### Recommendations
Based on these insights, what are your top three recommendations based on your analysis?
1.	Targeted Weekend Promotions:
Given that more casual members use the bikes on weekends, Cyclistic should design targeted weekend promotions to incentivize casual riders to become annual members. These promotions could include discounted annual membership rates or special weekend-only membership offers. Highlight the benefits of becoming an annual member, such as cost savings over time, access to exclusive features, and convenience.
2.	Ride Time Threshold Notifications:
Implement a feature in the Cyclistic app that notifies casual riders when they approach a ride time threshold that would make an annual membership more cost-effective. For example, if a casual rider has accumulated a certain number of ride hours over a month, they could receive a notification suggesting an annual membership for better value.
3.	Membership Tier Options:
Offer tiered annual membership options that cater to different usage patterns. For example, provide a "Weekday Commuter" membership with extended ride times on weekdays and a "Weekend Explorer" membership for longer rides on weekends. This flexibility can accommodate varying preferences.
Further,
### Electric Bike Membership Incentives:
•	Since a significant percentage of casual riders use electric bikes, Cyclistic should create membership incentives specific to electric bike users. This could involve offering electric bike annual memberships at a discounted rate or providing extra perks like longer ride times for electric bike users who become annual members. Emphasize the advantages of having unlimited access to electric bikes for daily commuting.

### Missing Data
If possible, price lists for annual and casual members, as well as the price list for ride durations and different bike types should have been provided. This would have enabled the formation of more appealing marketing strategies.


