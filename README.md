# Factors Influencing Life Expectancy: An Econometric Analysis Using WHO Data
This research is intended for finding key factors that affects life expectancy rate in countries. 

### Statment of  hypothesis

From this research it is hypothesed that life expectancy rate(Y) in countries is depend on countries:
- Total population (X1), 
- Status(X2), 
- Ammount of alcohol(X3), 
- UHC index(X4), 
- Dencity of medical doctors(X5), 
- Money spent on Healthcare(X6), 
- Adolesent birth rate(X7)

![image](https://github.com/user-attachments/assets/c98478ba-f583-4826-b182-74c40f271886)

The results showed that the most game-changer factors that affects 'Life Expectancy' is UHC Coverage Index, Government Health Expenditure(%) and Adolecent Bith Rate. 

![image](https://github.com/user-attachments/assets/aab17832-326a-4f5e-a69b-88c7f361c8cc)

UNC service coverage index and Government expenditure on health  show positive correlation with Life expectancy rate, indicating that as UHC service coverage and Government spending increase, life expectancy also rises. Meanwhile, adolecent birth rate and Life expectancy are correlated negatively. This suggests that the more adolecents bith in the country, the less years people live in the average.

#### Y = 51.51 + 0.3*X1 + 0.27*X2 - 0.02*X3 + e

Coefficients 
b0 : 51.51 - intercept. This is the predicted baseline life expectancy when all predictors (UHC service coverage, government health expenditure, and adolescent birth rate) are 0. While it doesn't have practical meaning in this case (as these predictors are rarely zero), it sets the baseline level of the model.

b1 : 0.303. For every 1-unit increase in UHC service coverage(X1), life expectancy increases by 0.3032 units, holding all other variables constant.

b2 : 0.273. For every 1% increase in government health expenditure as a percentage of GDP, life expectancy increases by 0.2733 years, holding UHC service coverage and adolescent birth rate constant.

b3 : -0.02. For every 1-unit increase in adolescent birth rate (births per 1,000 women aged 15–19), life expectancy decreases by 0.0204 years, holding UHC service coverage and government health expenditure constant.

For more insights and exploring calculations please download Excel file!

The data is derived from the World Health Statistics 2022, compiled from various sources including WHO and other international organizations. The dataset is cross-sectional, rely on 2019 year informations to provide a comprehensive overview of health-related SDG indicators. For this research only some parts of the World Health Statistics 2022 data is used to identfy which variables effect life expectancy years in countries. 
[Source](https://data.who.int/indicators/i/E3CAF2B/2322814?m49=004?m49=004?m49=004)


