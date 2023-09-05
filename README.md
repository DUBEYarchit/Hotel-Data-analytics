Hotel Data Analytics Project

CSV files used in project :

(1) fact_bookings - The CSV file contains a dataset of fact bookings with the following columns: booking_id, property_id, booking_date, check-in_date, checkout_date, no_guests (number of guests), room_category, booking_platform, ratings_given, booking_status, revenue_generated, and revenue_realized.

Prior to analysis, data cleaning was performed on the dataset. This involved removing records with negative values in the number of guests column and applying a filter to remove outliers in the revenue_generated column. Specifically, data points beyond three standard deviations from the mean were filtered out to enhance the dataset's accuracy and reliability for further analysis.
