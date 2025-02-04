# LOAN-ANALYSIS-REPORT
# Introduction
As part of assessment in the Data Analytics class organized by PSP Analytics, one of the analytics projects I’ll be working on is the Microfinance Loan Credit Dataset.The Microfinance Loan Credit Dataset contains the Loan_ID,	Mode of application,	loan_status,	Principal,	terms,	effective_date,	due_date,	paid_off_time and other data of the Microfinance Loan Credit. The goal of this work is to analyze the Microfinance Loan Credit performance and to uncover insights to be used for the business growth.

# Data Sourcing
This dataset used in this work is gotten from the Data Analytics Class announcement channel, which was posted by Mr. Kingsley Adisa.

# Data Preparation
I will load the dataset in excel format into powerbi. If data is clean, I can just load it directly or transform it to clean it on PowerBi.

## Data Cleaning/Transformation
Here, I check if the format of each column is correct and correct it were necessary. I also address inconsistencies in the columns to ensure a more accurate dataset for analysis.

# Data Exploration/Visualization
This is where I answered specific business questions for loan performance analysis using charts and tiles. Some of these questions include:

Total Loan Amount
MAX.Amount Paid
Total Amount Owed
Count of Defaults
Total no.of Payers

# KEY PERFORMANCE INDICATORS (KPI)
Before going ahead to answer the question, I first need to specify the KPI (Key Performance Indicators). The KPI include the Total Loan Amount, MAX. Amount Paid, Count of Defaults,Total Amount Owed and Total No. Payers. This is done by creating measures and using DAX to calculate the Total Loan Amount, MAX. Amount Paid, Count of Defaults, Total Amount Owed and Total No. Payers 

Total Loan Amount: I use SUM function to get total loan amount

  ![Total Loan amount](https://github.com/user-attachments/assets/77456f67-732f-41ae-8d50-60f458072f43)


MAX.Amount Paid: MAX of Principles in the dataset

  ![Max  amount ](https://github.com/user-attachments/assets/b1418fa9-28e0-44cf-b5b5-d12a63be7fc1)


Count of Defaults: Count of collection in the dataset

  ![Count d](https://github.com/user-attachments/assets/333fa3dd-5a0e-488f-b853-96205dd85675)


Total Amount Owed: SUM of total collection in the dataset

  ![Total amount owed](https://github.com/user-attachments/assets/f725c360-27fd-4402-920d-5cd059acc930)


I used the KPI tile to visualize my KPI. i could also use the Card tile.

1.Count of Guarantor by Loan-Status? 

  ![COUNT G](https://github.com/user-attachments/assets/db615139-bae5-441e-a1ff-fd3a504f0fba)


2.Count of Paid-off-Time by Mode of Application?

  ![COUNT P](https://github.com/user-attachments/assets/58b6939c-5adf-4f89-9012-84dbb9630525)


3.  Count of Loan-Status by Gender?

  ![COUNT GE](https://github.com/user-attachments/assets/499a8c78-2985-49b7-82a1-b8bfe39e1de0)
  
4. Sum of Principal by Mode of Application?
     
  ![SP](https://github.com/user-attachments/assets/debc0abc-a3cc-4235-8443-93dfcad4e3c4)
  
5.Count of Loan-ID by Highest Education?

  ![CLP](https://github.com/user-attachments/assets/52827fdc-3ac5-4e84-9514-e2d2518c2084)



Conclusion
So far, I’ve been able to analyze the Microfinance Loan Credit Dataset and to draw valuable insights through the business questions. Based on these findings, i can be able to provide data-driven recommendations to help for business growth. The resulting dashboard built from powerbi is shown below:

PBI DashBoard

  ![DSH](https://github.com/user-attachments/assets/bf64a848-3b51-49f7-a95f-5491f05bd25b)

