# MatPlotLibChallenge
The purpose of this challenge to use Python including Pandas and MatPlotLib to clean and analyze data around tests of various drug regimens on mice, including data visualizations to gain insights from the raw data. 

Using the duplicated method based on recommendation from Pooja Niranjan in my class: 
duplicates = merged_df[merged_df.duplicated(subset=['Mouse ID', 'Timepoint'], keep=False)]
duplicates
