# MatPlotLibChallenge
The purpose of this challenge is to clean and analyze data around test of various drug reimens on mice, using Python including Pandas and MatPlotLib to create visualizations to gain insights from the raw data.
There are six components of this challenge: 
1. Prepare Data
2. Generate Summary Statistics
3. Create Bar Charts and Pie Charts
4. Calculate Quartiles, Find Outliers, and Create a Box Plot
5. Create a Line Plot and a Scatter Plot
6. Calculate Correlation and Regression

Using the duplicated method based on recommendation from Pooja Niranjan in my class: 
duplicates = merged_df[merged_df.duplicated(subset=['Mouse ID', 'Timepoint'], keep=False)]
duplicates
