<div align="center">

# Equalizing Privileges for Self-Employed Clients to Salary Tier
### Product Management Case Study | Alfa-Bank Online Internship

[![Alfa-Bank Practice](https://img.shields.io/badge/Alfa--Bank-Product%20Management-ef3124?style=for-the-badge&logo=alfa-bank)](https://alfabank.ru/)
[![Author](https://img.shields.io/badge/Author-Eva%20Makarova-blue?style=for-the-badge&logo=github)](https://github.com/makarovaeva)
[![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)]()

---

  [Читать на русском](./README_RU.md)

---

</div>

> **Executive Summary:** 
> This project focuses on delivering a seamless UX and matching payroll-level banking privileges for self-employed clients (higher cashback, boosted savings rates, and simplified credit approvals via Federal Tax Service API analysis) to position Alfa-Bank as their primary bank for work and personal life.

### Key Highlights
* **Research:** 2 in-depth qualitative interviews + quantitative survey ($N=36$).
* **Validated Demand:** **86.1%** of respondents are ready to switch their main banking activity if offered payroll-tier perks.
* **North Star Metric:** Number of self-employed clients adopting additional banking products after activating privileges.

---

## Final Pitch

#### 1. Product/Feature Name
* **Equalizing Privileges for Self-Employed Clients to Payroll Tier**

#### 2. Problem (User Pain Point)
* **Problem:** Lack of payroll-level privileges for self-employed individuals, leading them to split funds and move savings between different banks in search of better conditions.
* **Data Context:** **33.3%** of surveyed users do not use a single bank for both income and daily expenses due to the lack of dedicated self-employed offers. However, **52.8%** are ready to adopt a single bank as their primary financial hub if provided with payroll-tier benefits.

#### 3. Target Audience
* Students and young graduates aged **20–24**.
* Receive income from self-employment into one bank, but divide savings and daily spending across multiple banks based on cashback rates and high-yield savings offers to maximize financial value.

#### 4. Solution (Product Concept)
* Self-employed users gain access to payroll-tier benefits by choosing the bank as their primary hub for income and daily expenses.
* **Automated income verification via Federal Tax Service (FTS) API:** Analyzing receipt regularity and transaction volume enables precise risk assessment (reliability), lowers friction for credit product approvals (security), and fosters user loyalty through status recognition (value).
* **Key User Flow:** The user opens the app $\rightarrow$ sees a home screen banner about self-employed privileges $\rightarrow$ taps to view the benefit list $\rightarrow$ selects an account for income deposits $\rightarrow$ receives guidance on updating payment details in the official tax portal $\rightarrow$ sees a success screen and returns to the main dashboard.

#### 5. Research Insights & Key Findings

##### Qualitative Insights (In-depth Interviews — $N=2$):
* *Anna (21 yrs, 3 yrs self-employed) & Alexandra (20 yrs, 2 yrs self-employed)*
* Users rarely notice issues stemming from a lack of self-employed perks and are largely unaware of standard payroll client privileges.
* They currently hold savings and process income within the same bank they use for daily card payments.
* Highly active users of cashback programs, savings accounts, and deposits. Primary decision criteria: cashback rules, savings interest rates, and partner promotions.

##### Quantitative Survey Results ($N=36$ / 30 hours):
* **86.1%** total readiness to consolidate all financial flows into one bank if offered payroll perks (**52.8%** "Definitely yes", **33.3%** "Rather yes than no").
* **Key Friction/Risk Identified:** One respondent highlighted the fear of card/account suspension as a barrier to moving 100% of funds to a single bank (risk of losing access to funds).

##### Hypotheses Validation:
* ❌ **Initial Idea #1 (Unmet needs/friction due to self-employed status):** Refuted during qualitative interviews — users did not perceive explicit servicing issues.
* 💡 **Post-Interview Hypothesis:** Self-employed users will choose a primary bank if it offers superior terms on savings products.
* ✅ **Core Privilege Hypothesis:** **Confirmed during quantitative survey.** The proportion of respondents ready to select the bank as their primary operational hub upon receiving payroll perks reached **0.528** ("Definitely yes").

> **Summary:** Survey data backed the concept: **86.1%** expressed willingness to make the bank their main financial driver if provided with payroll-tier privileges.

#### 6. North Star Metric (NSM)
* **Number of self-employed clients who activated additional banking products after unlocking privileges.**

#### 7. Business Value
* **Growth, Revenue, and Retention:**
  * **Audience Growth:** Attraction of new self-employed clients.
  * **Monetization:** Net interest margin from credit/mortgage products, profit on attracted liabilities (savings/deposits), transfer fees, acquiring, account maintenance fees, and cross-sold insurance.
  * **Retention:** Sustained usage driven by exclusive, non-replicable privilege tiers.

#### 8. Unfair Advantage (Killer Feature)
* **First-mover advantage:** Banks currently do not offer payroll-equivalent privilege tiers specifically tailored to self-employed clients.

#### 9. Success Metrics (AARRR Framework)
1. **Activation/Conversion:** Percentage of users who unlocked privileges and subsequently adopted a new financial product (proves privileges act as an adoption trigger).
2. **Revenue/LTV:** Aggregate customer profile margin post-privilege activation (net profit generated per client minus privilege program costs).

#### 10. Launch Requirements
* **Integrations:** FTS API integration (receipt & income verification), risk model adjustments, and loyalty engine logic updates.
* **UI/UX Development:** Home screen promo banners, privilege landing page, account binding user flow, and tax portal update guidance.
* **Product Team:** Product Manager, UI/UX Designer, Backend & Mobile Engineers (iOS/Android), QA Engineers.
* **Operations & Compliance:** Legal team (loyalty terms & tax data consent updates), CRM Marketing (push notifications/targeted ads for 20–24 demographic), Support Scripts (addressing account suspension anxiety).