# BANK-MARKETING-CAMPAIGN-ANALYSIS
Optimizing Direct Marketing Campaigns for Term Deposit Subscription
# Bank Marketing Campaign Analysis  
## Optimizing Direct Marketing Campaigns for Term Deposit Subscription

---

## Objective

This project aims to analyze a bank’s telemarketing campaign data to identify key factors influencing customer subscription to term deposits.

### Goals:
- Understand customer behavior
- Identify high-conversion segments
- Optimize marketing strategies
- Build a predictive model for lead targeting

---

## Dataset

- Source: Kaggle – Bank Marketing Dataset  
- Records: ~39,000 customers  
- Target variable: Subscription (Yes/No)

### Data includes:
- Customer demographics (age, job, education, marital)
- Financial status (loan, housing, default)
- Campaign details (contact type, frequency)
- Previous campaign performance
- Macroeconomic indicators (interest rate, employment)

---

## Key Metrics

| Metric | Value |
|------|------|
| Total Customers | 39K |
| Total Subscribed | 4,598 |
| Conversion Rate | 11.67% |
| Avg Contacts | 2.62 |

---

## Key Insights

### 1. Contact Channel Effectiveness
- Cellular: ~15% conversion
- Telephone: ~5%

Customers respond significantly better to mobile contact.

---

### 2. Campaign Intensity
- Low contact frequency → highest conversion (~13%)
- High contact frequency → lowest conversion (~5%)

Over-contacting reduces effectiveness (customer fatigue).

---

### 3. Previous Campaign Outcome (Strongest Driver)
- Success: ~65% conversion
- Failure / No history: ~10–15%

Historical success is the strongest predictor of conversion.

---

### ⏱ 4. Contact History
- Previously contacted customers → much higher conversion
- New customers → low conversion

---

### 5. Customer Segments

#### Age
- Highest: ≤30 and >50 (~15–16%)
- Lowest: 41–50 (~8%)

#### Job
- Highest: Not working (~22%)
- Lowest: Blue-collar (~10%)

#### Education
- Higher education → higher conversion

#### Marital Status
- Single > Married / Divorced

#### Financial Status
- No personal loan → higher conversion

---

### 6. Macroeconomic Impact

| Variable | Correlation with Conversion |
|----------|----------------------------|
| euribor3m | -0.31 |
| nr.employed | -0.35 |
| emp.var.rate | -0.30 |

Customers are more likely to subscribe during weaker economic conditions.

---

### 7. Multicollinearity

Macroeconomic variables are highly correlated (0.9+), meaning they represent similar economic signals.

Recommendation:
- Use feature selection
- Or apply tree-based models

---

## Predictive Modeling

### Model:
- Logistic Regression

### Objective:
Predict probability of customer subscription

### Application:
- Lead scoring
- Targeted marketing

---

## Business Recommendations

### 1. Target High-Potential Customers
- Previous successful customers
- Age ≤30 or >50
- Not working / white-collar

---

### 2. Optimize Contact Strategy
- Prioritize cellular channel
- Limit number of contacts (1–3 times)

---

### 3. Leverage Remarketing
- Focus on customers with past interaction
- Build customer lifecycle strategy

---

### 4. Align with Economic Conditions
- Increase campaign intensity during economic downturns

---

### 5. Deploy Predictive Model
- Score leads before contact
- Reduce unnecessary outreach

---

## Dashboard

The dashboard includes:
- Conversion rate overview
- Campaign performance analysis
- Customer segmentation insights
- Macroeconomic impact visualization

---

## Conclusion

This analysis shows that conversion is driven by:
- Previous customer behavior
- Contact strategy
- Economic conditions

By applying data-driven targeting and optimizing campaign strategy, banks can significantly improve marketing efficiency and reduce operational costs.

---

