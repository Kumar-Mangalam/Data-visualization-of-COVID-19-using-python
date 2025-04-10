# Data-visualization-of-COVID-19-using-python
This Python program allows users to explore and analyze a COVID-19 dataset using pandas, seaborn, and matplotlib. It provides an interactive menu to visualize trends, distributions, and correlations related to COVID-19 deaths in the U.S., with options to view breakdowns by age, sex, state, and time.

If interactive mode isn't selected, the script automatically bombards you with a full set of graphs 😄

📂 Dataset Info

📌 Source: CDC Provisional COVID-19 Deaths Dataset

📄 Format: .csv

📍 File Path (modifiable):

DATA_PATH = "C:\\Users\\Kumar Mangalam\\Downloads\\Python CA2\\Provisional_COVID-19_Deaths_by_Sex_and_Age.csv"

🔧 What This Script Does

1. Data Preprocessing

Loads the CSV file using pandas.

Displays a quick overview of the data (info, head, description).

Checks for missing values and removes rows with missing critical death-related data.

Drops irrelevant columns like "Footnote" and "Data As Of".

Converts "Start Date" and "End Date" to datetime objects.

2. Interactive Menu

Run the script and choose from the following options:

Option

Description

1

Show Basic COVID-19 Death Statistics

2

Distribution of COVID-19 Deaths

3

Time Series of COVID-19 Deaths

4

Deaths by Sex

5

Deaths by Age Group

6

Top 10 States by COVID-19 Deaths

7

Correlation Heatmap

8

Mean Deaths by Age Group and Sex

9

Run All Analyses

0

Exit

📊 Visualizations

Here’s what the script can generate:

Histogram of COVID-19 death distribution

Line Plot of deaths over time

Bar Charts for deaths by sex, age group, and state

Heatmap showing correlation between different death types

Grouped Bar Chart for mean deaths by age and sex

🛠️ Libraries Used

pandas – Data manipulation

numpy – Numerical operations

seaborn – Data visualization (theme & statistical plots)

matplotlib.pyplot – Core plotting library

Make sure these are installed via pip if not already:

pip install pandas numpy seaborn matplotlib

🚀 How to Run

Make sure your dataset path is correct.

Run the script in a Python environment:

python covid_analysis.py

Choose interactive mode (or not):

Do you want to run interactive analysis? (y/n):

✅ Output Example

If you choose non-interactive mode (n), you'll see:

You Entered Wrong Input , Now You Have To Face So Many Graphs And All
[...plots appear one by one...]
All analysis complete!

📌 Notes

This script is for learning and academic purposes.

Make sure your dataset is the latest from the CDC and the format hasn't changed.

Feel free to expand it with more plots or export options like PDFs or Excel summaries.
