# Economical Variable Correlation and Productivity Model
## Analysis Report

### Data Overview
The dataset includes key economic variables such as M1 money supply, exchange rate, stock market index, and inflation rate for the USA. Four differnt dataset were used including, The M1 money supply, US stock Market, Exchange Rate and Inflation rate.

### Data Cleaning and Processing
Using the vlookup function the dataset were combined together to form a single dataset so as to ease the analysis. After this process, I have the following columns on the dataset: "Date", "Open" which stand for the opening price of the stock market, "High" the highest price the stock market hit in a month, "Low" which is the opposite of "high","Close" the closing price of the stock market which is also " the stock market index","Monthly inflation rate" ,"Annually inflation rate", "TWEXBGSMTH" the exchange rate of the United state of Ameican and also the "M1SL" which is the monthly money supply.After which dataset was import into python "google collab" for further analysis and data cleaning such as empty and error cell removal.

#### Correlation Analysis
The correlation analysis reveals the relationships between these variables. Notably:
- M1 Money Supply and Stock Market Index show a strong positive correlation.
- Inflation Rate has a negative correlation with the Stock Market Index.

![correlation matrix](https://github.com/user-attachments/assets/23694672-8504-4453-99c4-75a84a530bfc)

#### Theoretical Framework
Our theoretical framework assumes that productivity can be modeled as:
\[ \text{Productivity} = \frac{\text{M1 Money Supply}}{\text{Inflation Rate}} \times \frac{\text{Exchange Rate}}{\text{Stock Market Index}} \]

#### Productivity Model
The productivity model indicates that:
- Productivity appears to fluctuate over time.
- There are periods of significant increase and decrease, reflecting economic events and policies.
![Productivity Overtime](https://github.com/user-attachments/assets/6bf736d6-5271-4eeb-988a-22a12ef8c8e0)

#### Currency Devaluation
We calculated the real currency devaluation using a reference currency with flat M1 growth and stable productivity. The real currency devaluation shows how the exchange rate changes relative to the reference currency over time.
![CURRENCY DEVALUATION](https://github.com/user-attachments/assets/aeffc152-5162-46b1-be4b-152fe192b54d)

#### Productivity Baseline
The productivity baseline is calculated using the formula:
\[ \text{Productivity Baseline} = \frac{\text{M1 Money Supply}}{\text{Stock Market Index}} \]
This baseline helps to understand the underlying productivity trends when the money supply and stock market index are stable.
![PRODUCTIVITY BASELINE OVERTIME](https://github.com/user-attachments/assets/700de8bd-abc0-42f6-8eef-514e103d7db6)

#### 7. Implications

The observed correlations, productivity trends, currency devaluation, and productivity baseline provide valuable insights:
- *Monetary Policies and Market Performance*: Understanding how these factors interact helps in making informed policy decisions.
- *Economic Forecasting*: The productivity model and currency devaluation analysis can be used to forecast economic conditions and guide investment strategies.

#### 8. Conclusion

The analysis successfully correlates key economic variables and develops a preliminary productivity model for the USA. Key takeaways include:
- Strong positive correlation between M1 Money Supply and Stock Market Index.
- Negative correlation between Inflation Rate and Stock Market Index.
- Fluctuations in productivity over time, influenced by economic policies and events.
- Real currency devaluation analysis highlights changes in exchange rates relative to a stable reference currency.
- The productivity baseline provides a stable measure of productivity trends.
### References: here is the link to the dataset and the pyhon coding and full visualization
#### Dataset: https://docs.google.com/spreadsheets/d/1vXvkh43K1i9UKj988Qniv9VsQlnSiztV/edit?usp=sharing&ouid=100485104845932051388&rtpof=true&sd=true
#### Python code:https://colab.research.google.com/drive/1ybHVEWPhupHraFqQt44jaTyeqzTfuimJ?authuser=0#scrollTo=ahtGD3bP7qXm

