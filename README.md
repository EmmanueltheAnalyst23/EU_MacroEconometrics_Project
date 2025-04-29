 EU Macroeconometrics Project

 Introduction
This project looks at how fiscal deficits, unemployment rates, and inflation affect GDP growth in five European Union countries: Poland, Germany, France, Czech Republic, and Lithuania.  
The data covers the years from 2014 to 2024.

The goal is to see if there is a significant relationship between these factors and how GDP grows over time.

Data and Method
- The data was collected from Eurostat.
- I used Excel for cleaning the data.
- I used Gretl to run simple regressions and check relationships.
- The model I used was:

    GDP_Growth = α + β₁(Fiscal_Deficit) + β₂(Unemployment_Rate) + β₃(Inflation_Rate) + β₄(Government_Expenditure) + error

Results
Each country had different results:
- **Poland:** Fiscal deficits were linked to higher GDP growth. The model fit was quite good (R² = 67%).
- **Germany:** Inflation seemed to help growth a little. The model was moderate (R² = 54%).
- **France:** Higher unemployment hurt growth. Model fit was low (R² = 29%).
- **Czech Republic:** Very low unemployment, but government spending had a negative effect.
- **Lithuania:** Strong growth after COVID, but very high inflation later.

Main Findings
- Fiscal deficits can sometimes help growth, depending on the country.
- Inflation has mixed effects. Moderate inflation helped Germany but hurt Lithuania.
- Unemployment sometimes behaves differently than expected.

 Files
- Final_Report_EU_MacroEconometrics.pdf`: Full report with results and conclusions.
- Data_EU_Econometrics.xlsx`: The cleaned dataset used for the analysis.

