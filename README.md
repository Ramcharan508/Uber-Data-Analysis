Uber Ride Data Analysis (2016)
Overview
This project involves an exploratory data analysis (EDA) of personal Uber rides from 2016. The analysis is performed using Python and popular data science libraries (Pandas, Matplotlib, Seaborn) within a Jupyter Notebook.

The goal is to load, clean, transform, and visualize the ride data to uncover patterns and insights, such as:

Ride frequency by time of day, day of the week, and month.

Common ride purposes and categories.

Distribution of trip distances.

Dataset
The analysis uses the "My Uber Drives - 2016.csv" dataset.

(Note: If you are making this public, ensure the dataset does not contain sensitive personal information. If it does, consider adding a note that the dataset is not publicly available or linking to a sanitized/public version if one exists.)

Analysis Steps
Data Loading: The dataset is loaded into a Pandas DataFrame.

Data Inspection: Initial review of the data structure, columns, data types, and missing values.

Data Cleaning:

Addressed missing values (e.g., imputing 'NOT' for missing PURPOSE* values, dropping records with missing start/end dates).

Converted date/time columns from string objects to proper datetime objects for time-based analysis.

Feature Engineering:

Extracted components like date, hour, day_of_week, and month from the START_DATE* timestamp.

Created a new 'daypart' feature (e.g., Morning, Afternoon, Evening, Night) based on the hour.

Exploratory Data Analysis (EDA) & Visualization:

Visualized the count of rides by CATEGORY and PURPOSE using Seaborn count plots.

Analyzed and plotted ride frequency by hour, day of the week, and month.

Examined the distribution of trip distances (MILES*) using bar plots, box plots, and distribution plots.

Visualized monthly ride patterns over the year.

Tools & Libraries Used
Python 3

Pandas: For data manipulation, cleaning, and analysis.

NumPy: For numerical operations (used implicitly by Pandas).

Matplotlib: For creating basic plots.

Seaborn: For enhanced statistical data visualization.

Jupyter Notebook / Google Colab: As the development environment.

How to Use
Clone this repository.

Ensure you have the required libraries installed (pip install pandas numpy matplotlib seaborn jupyter).

Place the My Uber Drives - 2016.csv dataset in the appropriate directory (or update the file path in the notebook).

Run the uber data analysis project.ipynb notebook using Jupyter Notebook or Google Colab.
