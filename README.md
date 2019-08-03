# Background

We will be using a dataset of personal auto insurance claims which include an outcome label of Fraud / Not Fraud. This dataset consists of 15,420 claims from between January 1994 and December 1996. The data consist of 6% fraudulent claims and 94% legitimate claims. It contains 6 ordinal and 25 categorical features in addition to the outcome variable. Features are as listed below.

| Column Name | Description |
|-----|-----|
|Month	|	Month of year in which the claim occurred |
|WeekOfMonth	|	Week within the month on which the claim occurred |
|DayOfWeek	|	Day of the week on which the claim occurred |
|Make	|	Make of the vehicle in the claim |
|AccidentArea	|	Urban classification of area where the accident occurred (e.g., urban, suburban, rural) |
|DayOfWeekClaimed	|	Day of the week on which the claim was reported |
|MonthClaimed	|	Month of year in which the claim was reported |
|WeekOfMonthClaimed	|	Week number within the month in which the claim was reported |
|Sex	|	Sex of the claimant |
|MaritalStatus	|	Marital status of the claimant |
|Age	|	Age of the claimant |
|Fault	|	Who was found to be at fault in the accident |
|PolicyType	|	Type of policy the policyholder has |
|VehicleCategory	|	Type of vehicle involved in the accident |
|VehiclePrice	|	Original cost new of the vehicle involved in the accident |
|FraudFound	|	Whether the claim was determined to be fraudulent or not |
|PolicyNumber	|	Unique insurance policy identifier |
|RepNumber	|	Unique identifier of the claims adjuster who handled each claim |
|Deductible	|	Amount the insured must pay before the insurer begins paying for repairs |
|DriverRating	|	Unknown |
|Days:Policy-Accident	|	Days between policy inception and the reported date of accident |
|Days:Policy-Claim	|	Days between policy inception and the date the claim was reported |
|PastNumberOfClaims	|	Number of prior claims on the insured's policy |
|AgeOfVehicle	|	Age in years of the vehicle involved in the accident |
|AgeOfPolicyHolder	|	Age group of the policyholder |
|PoliceReportFiled	|	Whether a police report was filed at the time of the accident |
|WitnessPresent	|	Whether any witnesses were present at the time of the accident |
|AgentType	|	External |
|NumberOfSuppliments	|	Number of additional payments issued on the claim |
|AddressChange-Claim	|	Time between most recent policyholder change of address and date the claim was reported |
|NumberOfCars	|	Number of vehicles on the policy |
|Year	|	Year of vehicle manufacture |
|BasePolicy	|	Base policy type (liability-only or full coverage) |


# Additional Terms

- **Claim**: A report of an accident to an insurance company for the purpose of payment for damages
- **Claimant**:
- **Policyholder**:
- **Coverage**: 
- **Liability Coverage**:
- **Comprehensive/Collision Coverage**:
- **Deductible**:
- **Loss Cost**:
- **Adjuster**:
- **Loss Date**:
- **Reported Date**:

# Goal

The goal of this project is to minimize overall loss costs to the insurer incurred by fraudulent claims. For our purposes, we will assume the following:

| | Predicted Fraud | Predicted Not Fraud |
|-----|-----|-----|
| Fraud | \$400 | \$2500 |
| Not Fraud | \$3500 | \$2000 |

This confusion matrix should be used to assess the relative business value of any proposed model.