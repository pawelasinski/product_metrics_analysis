# Product Metrics Analysis

This repo contains examples of **analyzing** some **product metrics** being a **data scientist/analyst**.

## Features

- **Revenue analysis** for a specific period.
- **A/B test** result analysis.
- Calculation of the **LTV** metric.

## Possible Project Extensions

- ...

## Author

Pawel Asinski (pawel.asinski@gmail.com)

---

# Key Product Analytics Metrics Overview

## I. User Acquisition Metrics

### 1. Installs

- Number of application installations over a specific period (usually daily).
- Source of installations (traffic source).
- Quality of installations (conversion to registrations and activations).

### 2. Registrations

- Number of new registrations over a specific period (usually daily).
- Important to distinguish: installation ≠ registration.
- Monitor the "funnel" from installation to registration.

### 3. Activation

- First successful user engagement.
- Use of one of the product's key features.
- A crucial stage in user formation.

---

## II. Engagement & Activity Metrics

### 4. DAU / WAU / MAU

- **DAU (Daily Active Users)** — users engaging with the product daily
- **WAU (Weekly Active Users)** — users engaging with the product weekly
- **MAU (Monthly Active Users)** — users engaging with the product monthly

**Sticky Factor Formula:**

$$\text{Sticky Factor} = \frac{\text{DAU}}{\text{MAU}} \times 100\%$$

This metric assesses the regularity of product usage.

### 5. ASL (Average Session Length)

- Average duration of a session in the application.
- A session is the time from launching to closing the application (minimizing, closing).
- Longer sessions indicate higher engagement and potential user value.

---

## III. Retention Metrics

### 6. Retention Rate

Percentage of users returning to the product after their first use.

**Retention N-day Formula:**

$$\text{Retention}\ (N\ \text{day}) = \frac{\text{Number of users who returned on day N}}{\text{Number of new users}} \times 100\%$$

- **1-day retention** — reflects UI/UX issues
- **7-day retention** — indicates engagement potential
- **28-day retention** — reflects the product's long-term value

### 7. Churn Rate

Percentage of users who stopped using the product over a specific period.

**Formula:**

$$\text{Churn Rate} = \frac{\text{Number of lost customers over a period}}{\text{Total number of customers at the start of the period}} \times 100\%$$

Lower churn rates are preferable.

---

## IV. Monetization & Revenue Metrics

### 8. ARPU (Average Revenue Per User)

Average revenue per user (including both paying and non-paying users).

**Formula:**

$$\text{ARPU} = \frac{\text{Revenue}}{\text{Total number of users}}$$

### 9. ARPPU (Average Revenue Per Paying User)

Average revenue per paying user.

**Formula:**

$$\text{ARPPU} = \frac{\text{Revenue}}{\text{Number of paying users}}$$

These metrics help understand the product's monetization status and identify potential segments for revenue growth.

### 10. LTV (Lifetime Value)

Average revenue generated from a user over their entire interaction period with the product.

**Formula:**

$$\text{LTV} = \text{ARPU} \times \text{Lifetime}$$

**Lifetime** — the duration from the start to the end of product usage.

### 11. CAC (Customer Acquisition Cost)

Cost of acquiring a single user.

**Key Ratio:**

$$\text{LTV} > \text{CAC}$$

This is essential for the product's profitable growth.

### 12. CPA (Cost Per Action)

Cost per specific action (registration, first purchase, etc.).

---

## V. Purchases & Conversion Metrics

### 13. Conversion Rate

Proportion of users who performed a target action (purchase).

**Formula:**

$$\text{Conversion} = \frac{\text{Number of users who performed the action}}{\text{Total number of users}} \times 100\%$$

### 14. First Purchase

- The first purchase within the application (a significant indicator of a user's readiness to pay).
- Helps assess the monetization effectiveness for new users.

### 15. DAP (Daily Active Purchases)

- Number of purchases made daily.
- Reflects the regularity and stability of monetization.

---

## VI. Investment Efficiency Metrics

### 16. ROI (Return On Investment)

Indicator of return on investment.

**Formula:**

$$\text{ROI} = \frac{\text{Revenue} - \text{Costs}}{\text{Costs}} \times 100\%$$

Reflects the efficiency of spending on user acquisition and retention.

---

## Additional Notes

- Monetization and purchasing power vary across platforms: AppStore users are typically more willing to spend than Play Market users.
- Regular analysis of metric dynamics is recommended, considering the product's specifics when selecting key KPIs.

---

# Traffic Attribution Models Overview

Traffic attribution is the process of assigning the value of a conversion to the various traffic sources a user interacted with on their journey to completing a desired action, such as a purchase or registration. It helps identify which marketing channels most effectively contribute to business goals, aiding in the optimization of advertising budgets and promotional strategies.

There are several attribution models, each evaluating the contribution of channels to a conversion differently:

1. **First-Click Attribution**. Assigns all conversion value to the user's initial interaction with the brand. This model is useful for assessing channels that generate initial audience awareness.

2. **Last-Click Attribution**. Credits the entire conversion to the final interaction before the desired action. While widely used, it may undervalue earlier touchpoints.

3. **Linear Attribution**. Distributes the conversion value equally among all brand interactions.

4. **Time Decay Attribution**. Gives more credit to interactions closer in time to the conversion, reflecting their immediate influence on the user's decision.

5. **Position-Based Attribution (U-Shape)**. Typically, assigns 40% of the value to both the first and last interactions, with the remaining 20% distributed among intermediate touchpoints.

Choosing the appropriate attribution model depends on business specifics, marketing campaign objectives, and audience behavior. For instance, companies focusing on brand awareness might prefer first-click attribution, while evaluating the effectiveness of closing sales stages may warrant a last-click model.

Understanding and correctly applying traffic attribution models allows for more accurate assessment of marketing channel effectiveness and informed decisions regarding advertising budget allocation.

---

# Key Financial Metrics Overview

## I. Revenue and Costs (Foundation)

### **1. Revenue (Sales / Turnover)**

- **Definition:** Total income generated from selling goods or services. It is the "top line" figure in the income statement.  
- **Example:** Selling 100 units at \$50 each results in a revenue of \$5,000.  
- **Formula:**  

$$\text{Revenue} = \text{Quantity Sold} \times \text{Selling Price per Unit}$$

### **2. Cost of Goods Sold (COGS)**

- **Definition:** Direct costs attributable to the production or purchase of the goods sold.
- **Example:** If each unit costs \$20, then for 100 units, COGS = \$2,000.
- **Formula:**

$$\text{COGS} = \text{Quantity Sold} \times \text{Cost per Unit}$$

---

## II. Margins (Unit-Level Profitability)

### **3. Absolute Margin**

- **Definition:** The difference between the selling price and the cost per unit.  
- **Example:** For a product sold at \$50 with a cost of \$20, the margin is \$30.  
- **Formula:**

$$\text{Margin} = \text{Price} - \text{Cost}$$

### **4. Profit Margin (Gross Margin Percentage)**

- **Definition:** The margin expressed as a percentage of the selling price, indicating how much of every dollar earned translates into profit (before other expenses).  
- **Example:** With a margin of \$30 on a \$50 sale, the profit margin is 60%.  
- **Formula:**

$$\text{Profit Margin} = \left(\frac{\text{Margin}}{\text{Price}}\right) \times 100\%$$

---

## III. Profit Measures (Overall Profitability)

### **5. Gross Profit**

- **Definition:** Profit remaining after subtracting COGS from revenue, reflecting earnings from core business activities before operating costs.  
- **Formula:**  

$$\text{Gross Profit} = \text{Revenue} - \text{COGS}$$

### **6. Operating Profit**

- **Definition:** Earnings after deducting operating expenses (like wages, rent, and advertising) from gross profit.  
- **Formula:**  

$$\text{Operating Profit} = \text{Gross Profit} - \text{Operating Expenses}$$

### **7. Net Profit**

- **Definition:** The "bottom line"—the profit remaining after all expenses, including operating expenses, taxes, and other costs, have been deducted.  
- **Formula:**  

$$\text{Net Profit} = \text{Operating Profit} - \text{Taxes} - \text{Other Expenses}$$

---

## IV. Additional Financial Metrics (Extended Insights)

### **8. EBITDA (Earnings Before Interest, Taxes, Depreciation, and Amortization)**

- **Definition:** A measure of a company's operating performance that looks at earnings before non-operating expenses and non-cash charges. It provides an insight into the business’s operational efficiency.  
- **Formula:**  

$$\text{EBITDA} = \text{Operating Profit} + \text{Depreciation} + \text{Amortization}$$

### **9. Operating Cash Flow**  

- **Definition:** The cash generated by a company’s regular business operations. Unlike net profit, it excludes non-cash expenses and provides a clear picture of liquidity.  
- **Importance:** Vital for assessing whether a company generates enough cash to sustain operations, reinvest in the business, and meet obligations.

### **10. Earnings Per Share (EPS)**

- **Definition:** The portion of a company’s profit allocated to each outstanding share of common stock. It is an indicator of a company’s profitability on a per-share basis.  
- **Formula:**  

$$\text{EPS} = \frac{\text{Net Profit}}{\text{Number of Outstanding Shares}}$$

### **11. Return on Investment (ROI)**

- **Definition:** A measure used to evaluate the efficiency or profitability of an investment relative to its cost.  
- **Formula:**  

$$\text{ROI} = \left(\frac{\text{Net Profit}}{\text{Investment Cost}}\right) \times 100\%$$
