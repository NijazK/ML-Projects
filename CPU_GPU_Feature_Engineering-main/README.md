# CPU GPU Feature and performance Engineering
A data exploration from the chips_dataset csv file from Kaggle datasets. The project utilizes three main steps:
## Imports
* Import all necessary libraries and dependencies to aid in research.

## Data information & preprocessing
* Using pandaas to see the information within the csv dataset. 
* Cleaned null values and irrelevant columns from the data.
* Converted categorical values to numerical and cleaned all null values.
* Null values included TDP (W), Die Size (nm), and Transistors (million).
* Categorical columns array contains ['Type', 'Release Date', 'Foundry', 'Vendor']
* Numerical columns array contains ['Process Size (nm)', 'TDP (W)', 'Die Size (mm^2)', 'Transistors (million)', 'Freq (MHz)']

## Data Visualization
* Using plotly and matplotlib, we explore the processed data to see trends and patterns for more testing. 
* We use data graphs to see correlations between one or more variables to check the difference between CPU and GPU.

## Regressional Analysis
Conclusions:
  * Frequency for CPUs is always higher than the frequency for GPUs.
  * Transistors (million) increased gradually over 20 years with a steady positive slope.
  * correlation heat mapping suggests all variables are >70% threshold.
  * In the data, 54.8% of all data is GPU and 45.2% is the CPU.
