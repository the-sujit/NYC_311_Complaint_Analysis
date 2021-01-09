
This folder has 4 Jupyter Notebooks:
1. Data_Sort.ipynb
2. Data_Analysis.ipynb
3. Data_Split.ipynb
4. Top_Complaint_Prediction.ipynb
All the releveant data for this project can be downloaded from here: 

The first notebook can be used to ingest the raw data downloaded from the NYC 311 website. This notebook cleans the data and saves it into new csv file.
The second notebook uses the cleaned data and performs analysis on that data
The third notebook splits the sorted data yearwise. Since the original data is too large for prediction modeling, We will use the only one years data.
The fourth notebook uses split data of any one year and performs random forest classification to identify whether the given complaint is the most-severe complaint or not.
 
