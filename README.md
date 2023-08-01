# Stock-Pip-Price-Analysis
**Data Description**
>This dataset contains 24,140 rows and 29 columns, representing 10 seconds of EUR/USD currency exchange rates. The columns include the timestamp, the previous pip value, the previous 9 numbers, the previous 8 pip changes, and the pips value.

>The previous 9 numbers column contains a list of the previous 9 closing prices of the EUR/USD currency pair. The previous 8 pip changes column contains a list of the previous 8 changes in pips from the previous closing price. The pips value column contains the change in pips from the previous closing price.

**Data Cleaning and Preprocessing**
>The data was cleaned and preprocessed as follows:

>The previous 9 numbers and the previous 8 pip changes columns were converted from lists to floats.
The original columns previous 9 number and prev 8 pip change were dropped.
The data was converted to a Pandas DataFrame.

**Exploratory Data Analysis (EDA)**
The following EDA was performed on the data:

Descriptive statistics were calculated for the previous 9 numbers and the previous 8 pip changes columns.
The distribution of the previous 9 numbers and the previous 8 pip changes columns was visualized using histograms.
The correlation between the previous 9 numbers and the previous 8 pip changes columns was calculated.

**Conclusion**
The EDA showed that the previous 9 numbers and the previous 8 pip changes columns are both normally distributed. The correlation between the two columns is weak, suggesting that they are not strongly related.

**Future Work**
>Future work could include:

Further EDA on the data, including feature selection and model building.
Collecting more data to improve the accuracy of the models.
Applying the models to real-world trading scenarios.
>Contact
If you have any questions about the data or the Readme file, please contact me at [your email address].
