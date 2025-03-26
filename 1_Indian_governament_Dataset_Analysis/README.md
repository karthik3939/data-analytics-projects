Dataset Description:-
The dataset contains 385 rows and 7 columns, representing transaction data between different states in India.
Columns and Their Descriptions:-
homestatecode (int): Numeric code representing the home state.
salestatecode (int): Numeric code representing the sale state.
month (int): Month of the transaction (e.g., 9 for September).
year (int): Year of the transaction (e.g., 2024).
txn_count (int): Number of transactions recorded.
salestatename (str): Name of the state where the sale occurred.
homestatename (str): Name of the home state from where the transaction originated.

CONCLUSION
Conclusion for the Dataset Operations:-
Based on the various operations performed on the dataset, here are the key takeaways:

Dataset Cleaning & Inspection:-
The dataset was checked for missing values, data types, and inconsistencies.
No missing values were found, ensuring data completeness.
The dataset includes home state, sale state, month, year, and transaction counts.

Data Visualization:-
Histograms & KDE Plots: Analyzed the distribution of transaction counts.
Bar & Line Charts: Showed trends in transactions across months and years.
Box & Violin Plots: Revealed transaction count variations across states and time.
Heatmaps: Displayed relationships between home and sale states.

Statistical Analysis:-
T-test: Compared transaction counts between the two most active states (Delhi vs. Maharashtra).
Result: No statistically significant difference.
Chi-square Test: Assessed whether the transaction category (High/Low) varied by month.
Result: No significant association found

Final Insights:-
Transaction trends vary across states, but there’s no significant difference between top states.
Monthly patterns don’t significantly impact transaction counts when categorized as High/Low.
State-wise distributions show variance but no extreme outliers.
