# Usa_productivity_report
## Analysis Report

### Data Overview
The dataset includes key economic variables such as M1 money supply, exchange rate, stock market index, and inflation rate for the USA. Four differnt dataset were used including, The M1 money supply, US stock Market, Exchange Rate and Inflation rate.

### Data Cleaning and Processing
Using the vlookup function the dataset were combined together to form a single dataset so as to ease the analysis. After this process, I have the following columns on the dataset: "Date", "Open" which stand for the opening price of the stock market, "High" the highest price the stock market hit in a month, "Low" which is the opposite of "high","Close" the closing price of the stock market which is also " the stock market index","Monthly inflation rate" ,"Annually inflation rate", "TWEXBGSMTH" the exchange rate of the United state of Ameican and also the "M1SL" which is the monthly money supply.After which dataset was import into python "google collab" for further analysis and data cleaning such as empty and error cell removal.
### Correlation Analysis
The correlation analysis reveals the relationships between these variables. Notably:
- M1 Money Supply and Stock Market Index show a strong positive correlation.
- Inflation Rate has a negative correlation with the Stock Market Index.
![correlation matrix](https://github.com/user-attachments/assets/fa13818f-ee10-4c4f-8aef-3a78098b2910)

### Theoretical Framework
Our theoretical framework assumes that productivity can be modeled as:
\[ \text{Productivity} = \frac{\text{M1 Money Supply}}{\text{Inflation Rate}} \times \frac{\text{Exchange Rate}}{\text{Stock Market Index}} \]

### Productivity Model
The productivity model indicates that:
- Productivity appears to fluctuate over time.
- There are periods of significant increase and decrease, reflecting economic events and policies.
![Productivity Overtime](https://github.com/user-attachments/assets/71e8f6eb-6631-45ae-8ece-28f5c6216120)

### Implications
The observed correlations and productivity trends provide insights into how monetary policies and market performance interact. Further research is needed to refine the model and explore causality.

## Conclusion
The analysis successfully correlates key economic variables and develops a preliminary productivity model for the USA. Future work will focus on enhancing the model's accuracy and exploring time-shifted correlations.

### References: here is the link to the dataset and the pyhon coding and full visualization
#### Dataset: https://docs.google.com/spreadsheets/d/1Vk-VWlN5edNOrcXiKoDJggmauYk9gOER/edit?usp=drive_link&ouid=100485104845932051388&rtpof=true&sd=true
#### Python code:https://colab.research.google.com/drive/1A3GF1zLKl2tkNMw22Lkggvi8UMpxhDwY?authuser=0#scrollTo=bsF757NC6Nnx

