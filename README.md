# Exploratory Data Analysis & Visualisations

The exploratory analysis was performed using Python, primarily with **Pandas, Matplotlib and Seaborn**.

The visualisations were used to examine:

- Customer demographics
- The overall target variable
- Customer subscription behaviour
- Marketing contact methods
- Campaign outcomes
- Contact timing
- Relationships between numerical variables

---

## 1. Overall Subscription Distribution

The target variable `deposit` was first analysed to understand the overall distribution between customers who subscribed and those who did not.

![Target Distribution](https://github.com/Mojalefa-04/WEEK-5/blob/main/Visualizations/Target_Dist.png)

The analysis showed that:

- **52.62%** of customers did not subscribe.
- **47.38%** of customers subscribed.

This provides the overall baseline against which the different customer segments can be compared.

### Overall Subscription Rate

![Overall Subscription Rate](https://github.com/Mojalefa-04/WEEK-5/blob/main/Visualizations/Overall_sub_rate.png)

The overall subscription rate was approximately **47.4%**.

---

## 2. Customer Age Analysis

The age distribution was examined to understand the demographic composition of the customer base.

![Age Distribution](https://github.com/Mojalefa-04/WEEK-5/blob/main/Visualizations/Age_Dist.png)

The dataset contains customers between the ages of **18 and 95**, with an average age of approximately **41 years**.

To further investigate the relationship between age and subscription behaviour, customers were grouped into age categories.

![Subscription by Age](https://github.com/Mojalefa-04/WEEK-5/blob/main/Visualizations/sub_by_age.png)

### Subscription Rate by Age Group

![Subscription Rate by Age Group](https://github.com/Mojalefa-04/WEEK-5/blob/main/Visualizations/sub_rate_by_agegroup.png)

The analysis showed differences in subscription rates between age groups.

| Age Group | Subscription Rate |
|---|---:|
| 66+ | 80.40% |
| 18–25 | 71.11% |
| 56–65 | 53.96% |
| 26–35 | 47.67% |
| 46–55 | 41.55% |
| 36–45 | 41.20% |

The results suggest that age may be useful as one of several variables for customer segmentation.

---

## 3. Job Analysis

The distribution of customers across occupations was examined.

![Subscription by Job Distribution](https://github.com/Mojalefa-04/WEEK-5/blob/main/Visualizations/sub_by_job.png)

The subscription rate was then calculated for each occupation.

![Subscription Rate by Job](https://github.com/Mojalefa-04/WEEK-5/blob/main/Visualizations/sub_rate_by_job.png)

Some notable observations include:

- Students had a relatively high subscription rate.
- Retired customers also showed a relatively high subscription rate.
- Blue-collar customers had a comparatively lower subscription rate.
- Subscription behaviour varied considerably between occupational groups.

### Subscription Rate by Job

| Job | Subscription Rate |
|---|---:|
| Student | 74.72% |
| Retired | 66.32% |
| Unemployed | 56.58% |
| Management | 50.70% |
| Unknown | 48.57% |
| Admin | 47.30% |
| Self-employed | 46.17% |
| Technician | 46.08% |
| Services | 39.98% |
| Housemaid | 39.78% |
| Entrepreneur | 37.50% |
| Blue-collar | 36.42% |

These differences indicate that occupation may be useful when developing targeted marketing segments.

---

## 4. Education Analysis

The education distribution was examined to understand the composition of the customer base.

![Subscription by Education](https://github.com/Mojalefa-04/WEEK-5/blob/main/Visualizations/sub_by_edu.png)

Subscription rates were then compared across education levels.

![Subscription Rate by Education](https://github.com/Mojalefa-04/WEEK-5/blob/main/Visualizations/sub_rate_by_edu.png)

### Subscription Rate by Education

| Education | Subscription Rate |
|---|---:|
| Tertiary | 54.11% |
| Unknown | 50.70% |
| Secondary | 44.74% |
| Primary | 39.40% |

Customers with tertiary education had the highest observed subscription rate, while customers with primary education had the lowest.

---

## 5. Marital Status Analysis

The distribution of customers by marital status was analysed.

![Subscription by Marital Status](https://github.com/Mojalefa-04/WEEK-5/blob/main/Visualizations/sub_by_ms.png)

The subscription rate was subsequently compared across marital-status groups.

![Subscription Rate by Marital Status](https://github.com/Mojalefa-04/WEEK-5/blob/main/Visualizations/sub_rate_by_ms.png)

### Subscription Rate by Marital Status

| Marital Status | Subscription Rate |
|---|---:|
| Single | 54.35% |
| Divorced | 48.11% |
| Married | 43.38% |

Single customers had the highest observed subscription rate among the three groups.

---

## 6. Contact Method Analysis

The analysis examined the distribution of customers across the recorded contact methods.

![Subscription by Contact Method](https://github.com/Mojalefa-04/WEEK-5/blob/main/Visualizations/sub_by_cm.png)

The subscription rate was then calculated for each contact method.

![Subscription Rate by Contact Method](https://github.com/Mojalefa-04/WEEK-5/blob/main/Visualizations/sub_rate_by_cm.png)

### Subscription Rate by Contact Method

| Contact Method | Subscription Rate |
|---|---:|
| Cellular | 54.33% |
| Telephone | 50.39% |
| Unknown | 22.59% |

Customers contacted through cellular communication had the highest observed subscription rate.

However, these results represent an association and do not establish that the contact method itself caused the higher subscription rate.

---

## 7. Contact Month Analysis

The distribution of marketing contacts across months was examined.

![Month of Contact](https://github.com/Mojalefa-04/WEEK-5/blob/main/Visualizations/Month_of_Contact.png)

The analysis was then extended to calculate the subscription rate for each month.

![Subscription Rate by Month](https://github.com/Mojalefa-04/WEEK-5/blob/main/Visualizations/sub_rate_by_month.png)

### Subscription Rate by Month

| Month | Subscription Rate |
|---|---:|
| January | 41.28% |
| February | 56.83% |
| March | 89.86% |
| April | 62.51% |
| May | 32.75% |
| June | 44.68% |
| July | 41.41% |
| August | 45.29% |
| September | 84.33% |
| October | 82.40% |
| November | 42.74% |
| December | 90.91% |

December had the highest observed subscription rate at **90.91%**, while May had the lowest at **32.75%**.

The large differences between months suggest that campaign timing is worth investigating further.

However, the monthly differences should not automatically be interpreted as causal because customer composition and campaign activity may differ between months.

---

## 8. Previous Campaign Outcome Analysis

The previous campaign outcome was analysed because previous customer interactions may provide useful information about future campaign responses.

![Previous Campaign Outcome Distribution](https://github.com/Mojalefa-04/WEEK-5/blob/main/Visualizations/PCC.png)

The subscription rate was then calculated for each previous campaign outcome.

![Subscription Rate by Previous Campaign Outcome](https://github.com/Mojalefa-04/WEEK-5/blob/main/Visualizations/sub_rate_by_pcc.png)

### Subscription Rate by Previous Campaign Outcome

| Previous Campaign Outcome | Subscription Rate |
|---|---:|
| Success | 91.32% |
| Other | 57.17% |
| Failure | 50.33% |
| Unknown | 40.67% |

The strongest observed pattern was among customers whose previous campaign outcome was **successful**.

Their subscription rate was approximately **91.3%**, considerably higher than the other categories.

This suggests that previous campaign engagement could be an important variable for customer targeting.

---

## 9. Correlation Analysis

A correlation heatmap was created to examine relationships between numerical variables.

![Correlation Heatmap](https://github.com/Mojalefa-04/WEEK-5/blob/main/Visualizations/CH.png)

The correlation analysis included numerical variables such as:

- Age
- Balance
- Day
- Duration
- Campaign
- Pdays
- Previous

The heatmap was used as an exploratory tool to identify potential relationships between numerical variables.

Correlation does not imply causation, so the results should be interpreted alongside the other analyses rather than in isolation.

---

# Summary of Visual Findings

The visual analysis revealed several important patterns:

### Customer characteristics

- Customer age varies considerably across the dataset.
- Subscription rates differ between age groups.
- Occupation is associated with different levels of subscription.
- Education levels show differences in subscription rates.
- Single customers have a higher observed subscription rate than married customers.

### Marketing campaign characteristics

- Subscription rates differ across contact methods.
- Subscription rates vary substantially across months.
- Previous campaign outcome shows a particularly strong difference in subscription rates.

### Overall business implication

The visualisations suggest that the bank's customers should not necessarily be treated as one homogeneous group.

Customer characteristics and campaign history can be used to identify different segments and potentially improve marketing targeting.

---

# Key Findings

1. The overall term-deposit subscription rate was **47.38%**.
2. The dataset contained **11,162 customers and 17 variables**.
3. No missing values or duplicate records were identified.
4. Subscription rates varied substantially across age groups.
5. Students and retired customers had relatively high subscription rates.
6. Tertiary-educated customers had a higher subscription rate than secondary- and primary-educated customers.
7. Single customers had a higher subscription rate than married customers.
8. Cellular contact had the highest subscription rate among the recorded contact methods.
9. Customers with a previous successful campaign outcome had a **91.32% subscription rate**.
10. Subscription rates varied considerably by month, with December showing the highest observed rate at **90.91%**.

---

# Business Insights

The analysis suggests several opportunities for the bank:

### Customer segmentation

Different customer groups show different subscription rates. This suggests that targeted marketing may be more effective than treating all customers in the same way.

### Previous campaign history

Previous campaign success is strongly associated with current subscription behaviour. Customers with a successful previous outcome may represent a high-intent segment.

### Contact strategy

Differences between contact methods suggest that communication channels should be monitored and evaluated based on campaign performance.

### Campaign timing

Large differences in monthly subscription rates suggest that campaign timing could be investigated further.

### Data-driven decision-making

The analysis demonstrates how exploratory data analysis can move beyond simply describing a dataset and provide information that can support business decisions.

---

# Recommendations

Based on the analysis, I recommend that the bank:

1. **Prioritise customers with previous successful campaign outcomes** when planning follow-up campaigns.
2. **Develop targeted customer segments** using variables such as age, occupation and education.
3. **Evaluate contact channels** based on their observed subscription performance.
4. **Investigate campaign timing** through controlled testing rather than assuming that a particular month directly causes higher conversion.
5. **Continuously monitor subscription rates** across customer segments, contact methods and campaign periods.

---

# Limitations

The analysis is primarily descriptive and therefore identifies associations rather than proving causation.

Other limitations include:

- Some categories may contain fewer observations than others.
- The `unknown` category is relatively large for some variables.
- Monthly subscription differences may be influenced by customer composition and campaign activity.
- Further statistical modelling would be required to determine which variables independently predict subscription.

---

# Conclusion

This Business Analytics case study used Python to investigate factors associated with term-deposit subscription in the Bank Marketing dataset.

Through exploratory data analysis and visualisation, differences were identified across customer demographics, contact methods, campaign timing and previous campaign outcomes.

The strongest observed pattern was the relationship between previous campaign success and current subscription, where customers with a previous successful outcome had a subscription rate of approximately **91.3%**.

Overall, the analysis demonstrates how data can be used to move from a broad business question to measurable patterns, business insights and actionable recommendations.

A potential next step would be to extend the analysis using statistical modelling or machine learning to estimate the probability of subscription for individual customers.
