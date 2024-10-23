# Project 1- Death Rates, Pharmaceutical Sales, and Pfizer Stock: A Correlation Analysis
>
### 1. Project Objectives:
>
>>This project aims to investigate potential correlations between death rates in the United States, Pfizer stock prices, and pharmaceutical sales. By examining these variables, we hope to gain insights into the factors that influence the pharmaceutical industry and public health. 
>
>> Considerations:
>
>> Utilize reputable sources of data:
>>>Centers for Disease Control
>>>https://data.cdc.gov/NCHS/Weekly-Counts-of-Death-by-Jurisdiction-and-Select-/u6jv-9ijr/data_preview
>
>>>Kaggle
>>>https://www.kaggle.com/datasets/milanzdravkovic/pharma-sales-data?resource=download
>
>>>Marketwatch
>>>https://www.marketwatch.com/investing/stock/pfe/download-data?startDate=01/01/2024&endDate=10/14/2024
>
### 2. Usage & Installation Instructions:
>
>>Our team utilized the Python programming language to complete this assignment. We worked in the Visual Studo Code editor along with Jupyter Notebook. 
>
>>The following libraries will need to be installed to properly run code: 
>
>>>Pandas
>
>>>JSON
>
>>>Matplotlib
>
>>>Seaborn
>
>>>Pathlib
>
Order to Run Code:
- First Run the individual Data Cleaning files:
	- death_counts.ipynb
		- data for death counts
	- Pfizer stock/Pfizer.ipynb
		- data for Pfizer stocks
	- clean_weekly_sales_data.ipynb
		- data for drug sales
- Next run the merging files
	- death_by_drug_sales.piynb
		- combines data for drug sales and death counts
	- death_count_pfizer.ipynb
		- combines data for death counts and Pfizer stock
:+1:
### 3. Data Analysis:
>
>>Data sets were pulled from legitimate data sites and then examined. We performed basic data cleaning steps such as renaming columns, addressing missing values, and data type consistency. Data frames were merged and analysed. Annotations were made to accompany code. We generated data visualizations to portray correlations. 
### 4. Conclusions:
>
>>Conclusions were based on the strength of correlation coefficients. The following conclusions were determined:
>
>>>There is a positive correlation between total drug sales and total death counts.
>
>>>Overall drug sales and death counts experience seasonality, with both higher in the winter.
>
>>>There is a positive correlation between total death counts and Pfizer stock prices.

### 5. Notes:
>
>>This project was completed with the assistance of AskBCS and Xpert Learning Assistant



