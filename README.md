**Hotel Data Analytics Project**

![image](https://github.com/DUBEYarchit/Hotel-Data-analytics/assets/111683461/3c9058bc-fe1e-4fb8-b242-a8f20a0fd80c)


CSV files used in project :

(1) fact_bookings - The CSV file contains a dataset of fact bookings with the following columns: booking_id, property_id, booking_date, check-in_date, checkout_date, no_guests (number of guests), room_category, booking_platform, ratings_given, booking_status, revenue_generated, and revenue_realized.

Prior to analysis, data cleaning was performed on the dataset. This involved removing records with negative values in the number of guests column and applying a filter to remove outliers in the revenue_generated column. Specifically, data points beyond three standard deviations from the mean were filtered out to enhance the dataset's accuracy and reliability for further analysis.

(2)  fact_aggregated_bookings  :  In this dataset named "agg_bookings" in the project, there are columns like property_id, check-in_date, room_category, successful_bookings, and capacity.

To analyze this dataset, I first calculated the number of successful bookings per property ID. Additionally, I identified days when bookings exceeded the property's capacity, indicating high demand. I also determined the properties with the highest capacity based on the provided data.

For data transformation, I introduced a new column named "Occupancy percent." This column was calculated by dividing the number of successful bookings by the property's capacity. This metric offers insights into the utilization of each property.

Furthermore, I conducted insight generation by calculating the average occupancy rate per room category, providing valuable information about which room categories tend to have higher occupancy rates on average.

**Overview**
This project focuses on Hotel Data Analytics using the Pandas library, as part of the Python certification program from Codebasics. The goal is to perform various data analysis tasks on hotel-related datasets to gain insights and make informed decisions.

**Datasets**
The project utilizes the following datasets:
fact_bookings.csv, dim_date.csv, dim_hotels.csv, dim_rooms.csv, fact_aggregated_bookings.csv

**Key Tasks**
**Exploratory Data Analysis (EDA)**
Exploratory Data Analysis was conducted to understand the structure and characteristics of the datasets. This involved examining key statistical measures, identifying patterns, and exploring relationships within the data.

**Data Cleaning**
Data cleaning was performed to address any inconsistencies, missing values, or outliers in the datasets. This ensures the reliability and accuracy of the analysis.

**Data Transformation**
Data transformation steps were implemented to reshape and restructure the data, making it suitable for the intended analysis. This includes aggregations, merging datasets, and creating new variables if necessary.

**Insight Generation**
The primary objective of the project was to generate meaningful insights from the data. This involves extracting valuable information, trends, and patterns that can aid in decision-making processes related to hotel operations.

**High-Level Detail (HLD) Document**
For a comprehensive understanding of the project, refer to the High Level Detail (HLD) document, which provides detailed insights into each task performed during the analysis.

[Download PDF](HLD_Hotel_data_analytics.pdf)


**Acknowledgments**
Special thanks to Codebasics for providing the Python certification program and the opportunity to work on this Hotel Data Analytics project.

