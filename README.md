# Product Metrics Analysis

This repo contains examples of **analyzing** some **product metrics** being a **data analyst**.

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
