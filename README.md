# Predictor of the Mexican stock exchange
WORK IN PROGRESS

This proyect is aiming to predict the value of the Mexican stock exchange, using different machine learning algorithms based on different marcoeconmic indicators. The proyect is also going to be paying special attention on the visualization of the database and the evaluation of the different machine learning algorithms used. <br/>
<br/>

The database was created by tracking the following macroeconomic indicators over a 20 year period: <br/>
- **GDP**: The perecentage of GDP grown each quarter of a year. <br/>
- **RFR**: The rate of return of government issued bonds (CETES).<br/>
- **Forex**: The exchange rate betwen the Mexican Peso and the US dollar. <br/>
- **CPI**: The inflation rate. <br/>
- **UR**: Unemployment rate. <br/>
- **IPC**: The value of the mexican stock exchange. <br/>
<br/>

A problem was found, because not all of this indicators are reported daily. A code was implemented so that values that are reported quarterly (GDP) or biweekly (RFR) were filled daily. This code is found on the document named "Filler".  <br/>
<br/>
The machine learning algorithm that were implemented are: <br/>
- **Decision Tree (DT)** <br/>
- **Random Forest (RF)** <br/>
- **Support Vector Machine (SVM)** <br/>
<br/>

The models were evaluted by measuring the following elements:
