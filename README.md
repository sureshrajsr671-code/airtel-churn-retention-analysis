### Project 2: Airtel Customer Churn Analytics

* **Repository Name:**  
  `airtel-customer-churn-analytics`
* **GitHub Description:**  
  `Telecom churn diagnostics and revenue defense framework across 7,043 subscriber accounts analyzing contract friction, payment methods, and fiber optic attrition.`[cite: 8]

```markdown
# Airtel Customer Churn Diagnostics and Retention Strategy

Uncovering Subscriber Defection Patterns, Revenue Risks, and Strategic Retention Roadmaps for Airtel.

---

## Executive Diagnostics and Overview
An empirical investigation across 7,043 active subscriber accounts to diagnose the root drivers of cancellation, protect recurring revenue, and safeguard market share.

### Key Performance Metrics
- Total Analyzed Subscribers: 7,043 accounts
- Total Churned Subscribers: 1,869 customers
- Overall Churn Rate: 26.5%
- Monthly Recurring Revenue Leakage: $1.40M+ in lost recurring revenue
- Replacement Cost Multiplier: Acquiring a replacement subscriber costs 5x to 7x more than retaining an existing user.

---

## Dataset and Analytics Scope
- Account Variables: Evaluating contract terms (Month-to-month, 1-Year, 2-Year), payment methods, and monthly charges.
- Service Subscriptions: Analyzing fiber optic internet, DSL, tech support, online security, and streaming add-ons.
- Target Variable: Customer churn status across billing cycles.

---

## Core Behavioral Churn Catalysts

### 1. Contract and Payment Friction
- Month-to-Month Contracts: Subscribers on month-to-month terms exhibit a 42.7% churn rate due to zero commitment friction.
- Electronic Check Payments: Users paying via Electronic Check churn at 45.2%, reflecting payment failure friction and low banking stickiness.

### 2. Fiber Optic Price Disconnect
- Fiber Optic users churn at 41.9% (compared to 19.0% for DSL).
- Higher monthly bills ($70-$110) combined with missing technical support create perceived value mismatch and dissatisfaction.

### 3. Early Tenure Risk and Missing Protection
- Over 50% of total customer attrition occurs within the first 12 months of tenure.
- Customers without Online Security or Tech Support churn at 3x the rate of protected subscribers (41% vs 14%).

---

## High-Risk Customer Segment Matrix

| Customer Segment Profile | Churn Rate | Avg Monthly Bill | Primary Risk Driver | Risk Level |
| :--- | :--- | :--- | :--- | :--- |
| Fiber Optic + Month-to-Month | 54.6% | $88.50 | High cost, low contract lock-in | Critical |
| Electronic Check + No Tech Support | 48.1% | $74.20 | Payment friction and unassisted issues | Critical |
| Tenure < 12 Months (New Users) | 47.4% | $65.80 | Lack of onboarding and brand loyalty | High |
| DSL + One-Year Contract | 11.2% | $49.10 | Moderate cost, established lock-in | Low |
| Two-Year Contract (All Services) | 2.8% | $61.30 | Long-term commitment and discounts | Low |

---

## Strategic Retention Roadmap

- Q1 - Early Onboarding: Deploy structured 90-day onboarding nudges and welcome discounts for new users.
- Q2 - Auto-Pay Incentives: Offer $5/month bill credits to transition Electronic Check users to Bank Auto-Pay.
- Q3 - Value Bundles: Bundle free Tech Support and Online Security with premium Fiber Optic plans.
- Q4 - Predictive AI Engine: Integrate real-time ML churn scoring into call centers for proactive save offers.

---

## Repository Structure
```text
├── data/
│   └── airtel_customer_churn_dataset.csv
├── working_files/
│   └── Airtel_Customer_Churn_Working_File.xlsx
├── screenshots/
│   └── airtel_churn_dashboard_clean.png
├── presentation/
│   └── Airtel Customer Churn Analytics.pptx
└── README.md
