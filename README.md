Hotel Data Analytics Project

CSV files used in project :

(1) fact_bookings - The CSV file contains a dataset of fact bookings with the following columns: booking_id, property_id, booking_date, check-in_date, checkout_date, no_guests (number of guests), room_category, booking_platform, ratings_given, booking_status, revenue_generated, and revenue_realized.

Prior to analysis, data cleaning was performed on the dataset. This involved removing records with negative values in the number of guests column and applying a filter to remove outliers in the revenue_generated column. Specifically, data points beyond three standard deviations from the mean were filtered out to enhance the dataset's accuracy and reliability for further analysis.

(2)  fact_aggregated_bookings  :  In this dataset named "agg_bookings" in the project, there are columns like property_id, check-in_date, room_category, successful_bookings, and capacity.

To analyze this dataset, I first calculated the number of successful bookings per property ID. Additionally, I identified days when bookings exceeded the property's capacity, indicating high demand. I also determined the properties with the highest capacity based on the provided data.

For data transformation, I introduced a new column named "Occupancy percent." This column was calculated by dividing the number of successful bookings by the property's capacity. This metric offers insights into the utilization of each property.

Furthermore, I conducted insight generation by calculating the average occupancy rate per room category, providing valuable information about which room categories tend to have higher occupancy rates on average.

