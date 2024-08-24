# Insurance Factors Identification Project

### Background and Objective

This project involves analyzing third-party motor insurance claims data from Sweden for the year 1977. In Sweden, all motor insurance companies apply identical risk arguments to classify customers, allowing their portfolios and claims statistics to be combined. The data were compiled by a Swedish Committee on the Analysis of Risk Premium in Motor Insurance. The objective is to analyze the real influence of various risk factors on insurance claims and compare the findings with the actual tariff structure.

### Domain: Insurance

### Dataset Description

The dataset contains 7 variables, described below:

| Attribute  | Description  |
|------------|--------------|
| **Kilometers** | Kilometers traveled per year. Categories: <br> 1: < 1000 <br> 2: 1000-15000 <br> 3: 15000-20000 <br> 4: 20000-25000 <br> 5: > 25000 |
| **Zone** | Geographical zone. Categories: <br> 1: Stockholm, Göteborg, and Malmö with surroundings <br> 2: Other large cities with surroundings <br> 3: Smaller cities with surroundings in southern Sweden <br> 4: Rural areas in southern Sweden <br> 5: Smaller cities with surroundings in northern Sweden <br> 6: Rural areas in northern Sweden <br> 7: Gotland |
| **Bonus** | No claims bonus; equals the number of years, plus one, since the last claim. |
| **Make** | Car make, where 1-8 represents eight different common car models, and all other models are combined into class 9. |
| **Insured** | The number of insured policy-years. |
| **Claims** | Number of claims made. |
| **Payment** | The total value of payments in Skr (Swedish Krona). |

### Analysis Tasks

#### 1. Descriptive Analysis of Data Fields:
- Conduct a descriptive analysis of each field to gain insights. This includes summary statistics like mean, median, mode, range, and distribution plots for numerical variables, and frequency tables for categorical variables.

#### 2. Relationship Between Payment, Number of Claims, and Insured Policy Years:
- Determine the relationship between payment, number of claims, and insured policy years using correlation analysis.
- Visualize the results with scatter plots or correlation matrices.

#### 3. Factors Affecting Payment Variations:
- Identify factors affecting payment variations through regression analysis or another predictive modeling technique.
- Include variables such as distance, location, bonus, make, insured amount, and claims in the analysis.
- Interpret coefficients to determine the impact of each factor on payments.

#### 4. Impact of Location, Kilometers, and Bonus Level on Insured Amount, Claims, and Payment:
- Aggregate the dataset by location, kilometers, and bonus level.
- Analyze how insured amount, claims, and payment vary across these categories.
- Use visualizations like bar charts or box plots to illustrate relationships.

#### 5. Factors Affecting Claim Rates:
- Conduct logistic regression analysis or another modeling technique to understand the factors affecting claim rates.
- Include variables such as insured amount, zone, kilometers, bonus, and make in the analysis.
- Interpret odds ratios or coefficients to assess the impact of each factor on claim rates.

### Conclusion
This project aims to provide insights that can help the Swedish insurance committee identify key risk factors and adjust premiums appropriately.
