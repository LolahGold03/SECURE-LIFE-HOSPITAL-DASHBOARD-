
# SECURE LIFE GENERAL HOSPITAL PERFORMANCE DASHBOARD

<img width="1540" height="660" alt="image" src="https://github.com/user-attachments/assets/2062834e-637c-4bbf-8982-522fc1646021" />




## Introduction
Hospitals generate large volumes of admission and billing data, but without a consolidated report it is hard to see how the organisation is performing. This project turns the records of Secure Life General Hospital into an Excel dashboard showing patient volumes, revenue, length of stay, insurance coverage and payment status in one place.

The goal is to help management monitor operations, track unpaid bills and make better-informed decisions.

## About the Dataset
The dataset has **1,000 patient visits** from January 2024 to December 2025. Each row is one visit, not necessarily one unique patient.

| Column | Description |
|---|---|
| Patient ID | Unique ID for each visit |
| Patient Name | Name of the patient |
| Age | Age in years at the time of the visit |
| Gender | Gender as recorded |
| Admission Date | Date admitted |
| Discharge Date | Date discharged |
| Department | Cardiology, Emergency, General, Neurology, Orthopedics, Pediatrics |
| Diagnosis | Medical condition recorded |
| Total Bill Amount | Total amount charged |
| Insurance Coverage (%) | Share of the bill covered by insurance |
| Payment Status | Paid, Pending or Partially Paid |

Calculated columns added: Length of Stay, Admission Year, Admission Month, Age Group and Outstanding Amount (bill value of Pending and Partially Paid visits).

## Problem Statement
Management has observed changes in admissions, outstanding bills and insurance coverage across departments, but has no consolidated view of performance. The dashboard answers:
1. How many patient visits were recorded?
2. Which departments receive the most patients?
3. Which departments generate the highest bills?
4. What is the average length of stay by department?
5. What share of bills is paid, pending or partially paid?
6. How much was billed and how much is outstanding?
7. How does insurance coverage vary by department and diagnosis?
8. Which age groups have the most visits?
9. How do admissions and billing change over time?
10. Which areas need management attention?

## Visualization


![Dashboard](Dashboard%20Image.png)



## Insights

| Metric | Result |
|---|---|
| Total visits | 1,000 |
| Total billed | $8,053,143 |
| Paid amount | $4,568,527 (56.7%) |
| Outstanding | $3,484,616 (43.3%) |
| Average length of stay | 4.8 days |
| Average insurance coverage | 75% |

- **Busiest departments:** General (252 visits), Emergency (190), Orthopedics (159), Pediatrics (153), Cardiology (152), Neurology (94).
- **Highest bills:** Orthopedics $2.55M, Cardiology $2.10M and Neurology $1.22M. These three produce 73% of billing from only 41% of visits.
- **Length of stay:** Orthopedics 8.4 days, Neurology 6.9, Cardiology 6.5, General 3.9, Pediatrics 3.0, Emergency 2.0.
- **Payment status:** 56.4% Paid, 25.7% Pending, 17.9% Partially Paid.
- **Insurance:** average coverage is 73.9% to 76.3% across departments. By diagnosis, Asthma (61.5%) and Arrhythmia (63.5%) are lowest. 44 visits had no coverage at all.
- **Age groups:** 51-65 has the most visits (235), followed by 66+ (232), 36-50 (210), 18-35 (170) and Under 18 (153).
- **Over time:** 508 visits in 2024 and 492 in 2025. November 2025 was the peak month (57 visits, $510K billed). June and August 2025 were the lowest (29 visits each).
- **Unpaid money:** Orthopedics holds $1.10M and Cardiology $0.90M of the outstanding balance.
- **High-cost cases:** 85 visits billed over $20,000 account for 27% of all billing.
- **Collections:** General (49.6%) and Pediatrics (45.4%) have the highest share of billed value unpaid, despite small bills.

## Recommendation
- Set up focused collections follow-up for Orthopedics and Cardiology, and prioritise high-cost visits.
- Review billing and follow-up in General and Pediatrics.
- Verify insurance at admission and offer payment plans for patients with 0-50% coverage.
- Plan beds and staffing around Orthopedics, Neurology and Cardiology, which have the longest stays.
- Prepare for peak months and investigate the dips in June and August 2025.
- Track Collection Rate, Outstanding Amount and Average Stay monthly on this dashboard.

## Conclusion
Secure Life General Hospital handled 1,000 visits and billed about $8.05M over two years, but only 56.7% has been collected. Revenue is concentrated in Orthopedics, Cardiology and Neurology, while General and Emergency drive volume. The biggest opportunity is improving collections, especially in Orthopedics and Cardiology and for patients with low or no insurance, together with better capacity planning for peak periods.
