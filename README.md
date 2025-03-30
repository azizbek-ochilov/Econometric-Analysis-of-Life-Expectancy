This research aims to identify key factors that influence life expectancy across countries.

### Statement of Hypothesis

This study hypothesizes that life expectancy (Y) in a country depends on the following factors:

- **Total population (X1)**  
- **Economic status (X2)**  
- **Alcohol consumption (X3)**  
- **UHC (Universal Health Coverage) Index (X4)**  
- **Density of medical doctors (X5)**  
- **Government health expenditure (X6)**  
- **Adolescent birth rate (X7)**  

![image](https://github.com/user-attachments/assets/c98478ba-f583-4826-b182-74c40f271886)

### Key Findings

The results indicate that the most significant factors affecting life expectancy are:

1. **UHC Coverage Index**  
2. **Government Health Expenditure (%)**  
3. **Adolescent Birth Rate**  

![image](https://github.com/user-attachments/assets/aab17832-326a-4f5e-a69b-88c7f361c8cc)

The **UHC Service Coverage Index** and **Government Health Expenditure** show a **positive correlation** with life expectancy, meaning that as healthcare coverage and government spending increase, life expectancy also rises.

In contrast, the **adolescent birth rate** has a **negative correlation** with life expectancy, indicating that countries with higher adolescent birth rates tend to have lower average life expectancy.

### Regression Model

The estimated econometric model is:

\[ Y = 51.51 + 0.3X_1 + 0.27X_2 - 0.02X_3 + e \]

#### Interpretation of Coefficients:

- **Intercept (b₀ = 51.51):** The baseline life expectancy when all predictors are zero. While not practically meaningful, it serves as the starting point for the model.
- **b₁ = 0.303:** A 1-unit increase in **UHC Service Coverage (X1)** increases life expectancy by 0.303 years, holding other variables constant.
- **b₂ = 0.273:** A 1% increase in **Government Health Expenditure (X2)** raises life expectancy by 0.273 years, assuming other factors remain unchanged.
- **b₃ = -0.02:** A 1-unit increase in the **Adolescent Birth Rate (X3)** decreases life expectancy by 0.020 years, keeping other variables constant.

### Data Source

The data used in this research comes from the **World Health Statistics 2022** report, compiled by **WHO** and other international organizations. It is **cross-sectional data** from the year **2019**, focusing on health-related **Sustainable Development Goals (SDG) indicators**. Only selected variables from the dataset were used to determine which factors influence life expectancy.

[**Source**](https://data.who.int/indicators/i/E3CAF2B/2322814?m49=004?m49=004?m49=004)

For further insights and detailed calculations, download the **Excel file** from the repository!
