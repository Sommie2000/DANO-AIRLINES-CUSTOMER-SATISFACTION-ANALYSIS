# DANO-AIRLINES-CUSTOMER-SATISFACTION-ANALYSIS
### PROJECT OVERVIEW
This project analyzes passenger satisfaction data for Dano Airlines to identify the key factors influencing customer satisfaction and provide data-driven recommendations for improving the overall passenger experience.
The analysis was conducted using Power BI and focuses on passenger demographics, travel characteristics, service quality ratings, and customer satisfaction outcomes.

### OBJECTIVE
Following the data set passengers survey, the overall satisfaction rate has fallen below the 50% threshold for the first time. This decline signals potential risks to customer loyalty, brand perception, and future revenue.
The objective of this analysis is to identify the reason for the decline and provide data-driven recommendations to improve passenger satisfaction and restore confidence in the airline’s service delivery. 
This report summarizes key findings from over 129,000 passenger responses and outlines practical actions that can be taken to reverse the trend.

### TABLE OF CONTENT
* [Project Overview](#project-overview)
* [Dataset Overview](#dataset-overview)
* [Data Cleaning](#data-cleaning)
* [Tools](#tools)
* [Excel Dashboard](#excel-dashboard)
* [Dashboard](#dashboard)
* [Key Insights](#key-insights)
* [Interactive Analysis](#interactive-analysis)
* [Recommendation](#recommendation)
* [Data Source](#data-source)
* [Conclusion](#conclusion)



### DATASET OVERVIEW

COLUMNS:
- ID
- Gender
- Age
- Customer Type
- Type of Travel
- Class
- Flight Distance
- Departure Delay
- Arrival Delay
- Departure and Arrival Time Convenience
- Ease of Online Booking
- Check-in Service
- Online Boarding
- Gate Location
- On-board Service
- Seat Comfort
- Leg Room Service
- Cleanliness	Food and Drink
- In-flight Service
- In-flight Wifi Service
- In-flight Entertainment
- Baggage Handling
- Satisfaction

|ID|	Gender|	Age|	Customer Type|	Type of Travel|	Class|	Flight Distance|	Departure Delay|	Arrival Delay|	Departure and Arrival Time Convenience|	Ease of Online Booking|	Check-in Service|	Online Boarding|	Gate Location|	On-board Service|	Seat Comfort|	Leg Room Service|	Cleanliness|	Food and Drink|	In-flight Service|	In-flight Wifi Service|	In-flight Entertainment|	Baggage Handling|	Satisfaction|
|----|------|----|---------------|--------------|--------|-----------------|-----------------|--------------|----------------------------------------|-----------------------|------------------|------------------|---------------|-----------------|--------------|-----------------|-------------|----------------|-----------------|------------------------|-------------------------------|-------------------|-------------|
|1|	Male|	48|	First-time|	Business|	Business|	821|	2|	5|	3|	3|	4|	3|	3|	3|	5|	2|	5|	5|	5|	3|	5|	5|	Neutral or Dissatisfied|
|2|	Female|	35|	Returning|	Business|	Business|	821|	26|	39|	2|	2|3|	5|2|5|	4|	5|	5|	3|	5|2|	5|	5|	Satisfied|
|3|	Male|	41|	Returning|	Business|	Business|	853|	0|	0|	4|	4|	4|	5|	4|	3|	5|	3|	5|	5|	3|	4|	3|	3|	Satisfied|
|4|	Male|	50|	Returning|	Business|	Business|	1905|	0|	0|	2|	2|	3|	4|	2|	5|	5|	5|	4|	4|	5|	2|	5|	5|	Satisfied|
|5|	Female|	49|	Returning|	Business|	Business|	3470|	0|	1|	3|	3|	3|	5|	3|	3|	4|	4|	5|	4|	3|	3|	3|	3|	Satisfied|




DATASET SAMPLE PREVIEW:
|Year|	Month| Days| Region|	Model| Units_Sold| Avg_Price_EUR| Revenue_EUR| BEV_Share| Premium_Share| GDP_Growth| Fuel_Price_Index|
|----|--------|-----|-------|------|-----------|--------------|------------|----------|--------------|-----------|-----------------|
|2019|	1/4/1900|	Wed|	Europe|	MINI|	$2.6K|	$40K|	$105M|	0.06|	17.63|	3.98|	1.04|
|2020|	1/4/1900|	Wed|	USA|	MINI|	$2.5K|	$43K|	$110M|	0.061|	19.81|	3.52|	1.16|
|2018|	1/1/1900|	Sun|	Europe|	MINI|	$2.6K|	$43K|	$110M|	0.013|	19.12|	3.5|	1|
|2021|	1/2/1900|	Mon|	Europe|	MINI|	$2.8K|	$40K|	$113M|	0.084|	15.12|	4.2|	1.14|
|2018|	1/10/1900|	Tue|	China|	MINI|	$2.7K|	$42K|	$114M|	0.025|	19.19|	5.28|	0.92|


[Dataset file showing the pivot tables][bmw_global_sales_2018_2025.xlsx](https://github.com/user-attachments/files/26570700/bmw_global_sales_2018_2025.xlsx)


### DATA CLEANING
