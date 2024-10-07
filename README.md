# Hotel_Booking_Analysis_EDA
 Hotel Booking Analysis project explores booking trends, pricing strategies, and customer behavior using a dataset. Key variables like lead time, ADR, total guests, and stay duration are analyzed through visualizations created using Python libraries (pandas, seaborn, matplotlib). The insights help optimize hotel operations and strategies.

Overview

This project focuses on analyzing and visualizing hotel booking data using Google Colab. The primary objectives include data cleaning, exploratory data analysis (EDA), and extracting insights from the dataset. It showcases various visualization techniques using popular Python libraries.

Key Features

Data Preprocessing: Cleaning and preparing the dataset for analysis.
Exploratory Data Analysis (EDA): Gaining insights through visualizations such as heatmaps, pair plots, and bar charts.
Correlation Analysis: Understanding relationships between different variables in the dataset.
Data Visualization: Representing key insights using libraries like Matplotlib, Seaborn, and Plotly.
Dataset
Dataset Name: Booking.com
Number of Rows: 119390
Number of Columns: 32

Key Variables:

adr: Average Daily Rate
lead_time: Time between booking and arrival
is_canceled: Indicates whether the booking was canceled
hotel: Type of hotel (City or Resort)
total_guest: Total number of guests
total_duration: Total duration of stay (weekdays + weekends)

Dataset Source

The dataset can be sourced from https://drive.google.com/file/d/1RQZFrADGApHEP_2-NaHVQ8D1tvs0ykBO/view?usp=sharing

Libraries Used

The project utilizes the following Python libraries:

pandas: For data manipulation and handling.

numpy: For numerical operations.

seaborn: For generating statistical plots.

matplotlib: For creating static visualizations.

plotly: For interactive data visualizations.


Installing Required Libraries
To install the necessary libraries, run the following command in your Google Colab notebook or local environment:

pip install pandas numpy seaborn matplotlib plotly 

How to Run the Project
Clone the Repository:
git clone https://github.com/sanchita98/Hotel_Booking_Analysis_EDA

Open the Project in Google Colab:
Upload the .ipynb file to Colab or select it from Google Drive.

Run the Code Cells:
Execute the cells one by one to see the results, visualizations, and insights generated during the analysis.

Visualizations
The project includes various visualizations:

Heatmap: Illustrating the correlation between different features.
Pair Plot: Displaying relationships between lead time, ADR, total guests, and total duration.
Bar Charts: Comparing average ADR by hotel type and cancellation status.
These visualizations aid in understanding data patterns and relationships between variables.

Results and Insights

Correlation: Lead time shows a weak positive correlation with ADR.
Cancellation: Canceled bookings have a slightly higher average ADR.
Guest and Duration Trends: Larger groups tend to have a slightly higher ADR, while longer stays are associated with lower ADR.
These insights can help hotels optimize revenue management, customer segmentation, and pricing strategies.

Contributing
Feel free to contribute to the project by forking this repository and submitting pull requests. Any feedback and improvements are welcome!
