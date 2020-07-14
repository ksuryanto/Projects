# BSAN6070 - CA01
Exploratory Data Analysis – India Pollution Data

## Background
This data is released by the Ministry of Environment and Forests and Central Pollution
Control Board of India under the National Data Sharing and Accessibility Policy
(NDSAP), using this one can explore India’s air pollution levels at a more granular scale.
The India Air Quality Dataset is downloaded from Kaggle.

## Getting Started
Let’s start: Import the dataset
Download the dataset (data.csv ) from this link:
https://www.kaggle.com/shrutibhargava94/india-air-quality-data
Create a new Notebook using the Notebook Template provided with this assignment.
Now, read the data into pandas DataFrame using read_csv() and display the first few
rows with head(). 

## Instruction
### Cleansing the dataset
In this step, we need to clean the data by adding and dropping the needed and unwanted
data respectively. From the above dataset,
### Dropping of less valued columns:
stn_code, agency, sampling_date, location_monitoring_agency do not add much
value to the dataset in terms of information. Therefore, we can drop those
columns.
### Changing the types to uniform format:
When you see the dataset, you may notice that the ‘type’ column has values such
as ‘Industrial Area’ and ‘Industrial Areas’ — both actually mean the same, so let’s
remove such type of stuff and make it uniform.
### Creating a year column
To view the trend over a period of time, we need year values for each row and also
when you see in most of the values in date column only has ‘year’ value. So, let’s
create a new column holding year values.
### Handling missing values
The column such as SO2, NO2, rspm, spm, pm2_5 are the ones which contribute much
to our analysis. So, we need to remove null from those columns to avoid inaccuracy in the
prediction.
Use the Imputer from sklearn.preprocessing to fill the missing values in every column
with the mean.

### Prerequisites
Write all your code using the provided .ipynb template file.
