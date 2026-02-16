# Project Backgrond

This project focuses on **improving** Accounts Receivable (AR) and Cash Application visibility through **a live analytical dashboard** designed for high-volume, multi-currency logistics operations.

The objective was to **transform** raw transactional payment data into actionable insights that **support daily decision-making** for AR, Cash Application, and Credit teams, while reducing operational risk caused by unapplied cash.

In freight and logistics, **cash application is inherently complex** due to high transaction volumes, partial payments, FX differences, and incomplete remittance information. When incoming **cash remains unapplied**, it can **distort** AR aging, misrepresent customer exposure, and lead to incorrect credit decisions such as unnecessary credit blocks or shipment delays.

This project **bridges the gap** between cash inflows and AR visibility, ensuring that received cash is accurately reflected and operational teams can act quickly based on reliable data.


## Data Confidentiality & Anonymization

This project is based on real-world operational scenarios, but all underlying data has been anonymized and modified to protect confidentiality.

Client identifiers, monetary values, and timestamps have been modified and rescaled, while preserving the original data structure, distributions, and business logic to ensure analytical validity.

## Business Problem

**Unapplied cash creates several downstream business issues:**

- **AR aging** becomes inflated despite cash being received.

- **Credit risk** is overstated, triggering unnecessary credit holds.

- Operational teams **lack visibility** into where and why cash is stuck.

- Manual investigation effort increases due to **poor prioritization**.

The challenge was to **centralize**, **structure**, and **analyze** unapplied cash data in a way that highlights risk, ownership, and trends — rather than just static balances.

## Project Objectives

**The primary objectives of this analysis were to:**

- Provide **live visibility** into unapplied cash balances for daily operational monitoring.

- Track **week-over-week (WoW) trends** to assess whether unapplied cash exposure is improving or deteriorating.

- Identify **regional drivers** of unapplied cash to support targeted process improvements.

- **Categorize** unapplied cash by **root cause** (e.g. Overpayments, Missing Remittance, FX Differences, Credit Memos, Unknown Payments).

- Enable teams to prioritize actions based on financial impact, not just volume.

An interactive Gsheet Dashboard can be seen [here](https://docs.google.com/spreadsheets/d/12twqOFy3n5iX-K_nj_9m4yKXR-6CCAETWreXp42kgP8/edit?gid=1941537939#gid=1941537939)


## Executive Summary

## Overall Findings

The weekly trend analysis shows that total unapplied cash in EMEA **declined materially** toward year-end 2025, followed by a modest and controlled rebound in **early 2026**.

From **Weeks 44 to 49**, unapplied cash fluctuated between **approximately $3.5M and $4.0M**, peaking in late November. A sharp decline occurred between Weeks 50 and 52, with balances falling to a low of approximately $2.6M, reflecting focused year-end cleanup efforts and improved cash application throughput.

**Entering 2026**, unapplied cash increased gradually, stabilizing at approximately $3.22M as of today, representing a +1.49% week-over-week increase. Importantly, this increase occurred alongside a decline in average unapplied cash per item (-1.28% WoW), despite a higher number of unapplied items (+4.22% WoW).

This divergence indicates that the early-year increase is driven more by volume and timing effects rather than larger-value exceptions, suggesting controlled exposure growth rather than a deterioration in cash application quality.

**Overall**, the trend reflects a structural **improvement in year-end performance**, followed by a predictable early-year normalization rather than a reversal of progress.


<img width="2034" height="1273" alt="image" src="https://github.com/user-attachments/assets/5f479400-b21d-4e66-88ec-53c6a1e977a5" />

## Unapplied Cash Trends by Key Drivers

- **Overpayments** consistently represent the largest share of unapplied cash, accounting for approximately 55% of total exposure (~$1.74M). This category remained elevated throughout the period, indicating that unapplied cash is primarily driven by recurring customer payment behavior rather than isolated processing exceptions. While balances declined toward year-end, overpayments rebounded moderately in early 2026 in line with increased payment volume.

- **Unknown Payments** declined materially toward the end of 2025 and into **early 2026 (-21.06% WoW)**. This reduction coincides with improved payment identification and matching processes, suggesting that recent process enhancements are effectively converting previously unidentified cash into allocable items.
  
- **Remittance Requests** increased **in early 2026 (+15.97% WoW)** following the year-end trough. This increase is consistent with seasonal remittance gaps observed at the start of the fiscal year, where payment receipt temporarily outpaces the availability of remittance documentation, leading to short-term unapplied balances.

- **Credit Memos** showed a sharp week-over-week increase (+59.86% WoW), contributing disproportionately to the early-2026 rise. This behavior reflects timing differences between credit issuance and application, rather than a deterioration in upstream billing accuracy.

- **FX-related** unapplied cash remained relatively stable throughout the period, indicating that currency conversion effects are not a primary driver of volatility and that existing FX handling controls remain effective.


<img width="2010" height="1398" alt="image" src="https://github.com/user-attachments/assets/ba8711d0-71c1-4272-8eb1-6de31e6201ad" />


## Unapplied Cash by Region

**West EU** is the primary driver of unapplied cash, consistently representing the largest share of exposure across all weeks. While balances declined materially at year-end, West EU also accounts for most of the early-2026 rebound, reflecting its higher transaction volume rather than regional control issues.

**North EU** shows stable but elevated unapplied cash, with increases concentrated in Overpayments and Remittance Requests, indicating recurring customer payment behavior rather than isolated processing exceptions.

**South EU** and SMB EU contribute smaller but persistent balances. Although their absolute exposure is lower, unapplied items tend to remain open longer, suggesting slower resolution cycles.

The sharp decline between Weeks 50–52 is visible across all regions, pointing to a coordinated year-end cleanup, while the early-2026 increase appears seasonal and broad-based, not region-specific.

<img width="1259" height="1264" alt="image" src="https://github.com/user-attachments/assets/770637c9-ce58-42dd-ba86-b2dc37d122d7" />



## Recommendations

Based on the uncovered insights, the following recommendations are proposed:

**Prioritize structural reduction of overpayments**
With overpayments accounting for approximately 55% of total unapplied cash, reducing repeat overpayment behavior should be the primary focus. Clearer invoice-level payment instructions, improved customer guidance, and closer alignment with billing and sales teams would help prevent recurring overpayments before they enter the AR process.

**Improve remittance capture and documentation workflows**
The increase in Remittance Requests in early 2026 indicates a recurring timing gap between cash receipt and remittance availability. Standardizing remittance formats, increasing automation, and proactively engaging high-volume customers would accelerate application and reduce short-term unapplied buildup.

**Sustain and scale payment identification improvements**
The continued decline in Unknown Payments demonstrates that recent matching and identification controls are effective. Maintaining and expanding these enhancements will help ensure unidentified cash does not re-emerge as a material driver.

**Apply regional focus to high-exposure areas**
As West EU and North EU consistently represent the largest unapplied cash exposure, region-specific action plans and ownership would deliver greater impact than uniform global interventions.




