# Fraud-Detection-in-Health-Care-Charges
## Objectives
The objective of this project is to apply unsupervised machine learning techniques, specifically PCA and KNN, to identify unusual data points in a dataset. By comparing and analyzing the results from these algorithms, we aim to assess their effectiveness in detecting outliers and gain insights into exceptional data patterns for potential business implications.
The Medicare Inpatient Hospitals by Geography and Service dataset provides information on hospital discharges for Original Medicare Part A beneficiaries by IPPS hospitals.

DRG Definition : Is a payment category that is used to classify patients for the purpose of reimbursing hospitals for each case in a given category with a fixed fee. Classification system that groups similar clinical conditions (diagnoses) and the procedures furnished by the hospital during the stay.

Provider Id :

Provider Name :

Provider Street Address :

Provider City :

Provider State :

Provider Zip Code :

Hospital Referral Region Description :

Total Discharges : The number of discharges billed by the provider for inpatient hospital services.

Average Covered Charges : The average charge of all providers' services covered by Medicare for discharges in the DRG. These will vary from hospital to hospital because of differences in hospital charge structures.

Average Total Payments : The average total payments to all providers for the DRG including the MS-DRG amount, teaching, disproportionate share, capital, and outlier payments for all cases. Also included in average total payments are co-payment and deductible amounts that the patient is responsible for and any additional payments by third parties for coordination of benefits.

Average Medicare Payments : The average amount that Medicare pays to the provider for Medicare's share of the MS-DRG. Medicare payment amounts include the MS-DRG amount, teaching, disproportionate share, capital, and outlier payments for all cases. Medicare payments DO NOT include beneficiary co-payments and deductible amounts nor any additional payments from third parties for coordination of benefits.

Total Covered Charge Amount = the sum of all covered charges

Average Covered Charges = Total Covered Charge Amount / Total Discharges

Payment is the amount a hospital actually receives for providing patient care. This is the actual amount paid to a hospital by consumers, insurers or governments. The sources of payment are: Medicare and Medicaid, Private insurer if any, The Patient

Average Total Payments = Total Payments / Total Discharges

Average Medicare Payments = Medicare Payment Amount / Total Discharges

## Steps:

1. Data Preparation:Check data quality and clean up.

2. EDA:the distribution of single variable
the distribution of one variable by another categorical variable
the interactions of two or three variables.

3. Create 20 features:summary for each of the features that you build and the insight why the feature will help the fraud detection.
   
5. Learn to use two PyOD methods - PCA and KNNs. You can find the PCA and KNNs method in the PyOD module. 
