# Predictive-Credit-Risk-Modeling by Brighton Mezie
  External CIBIL data provides supplementary credit information from the Credit Information Bureau (India) Limited (CIBIL), including credit scores, histories, repayment behavior, and outstanding debts. Integrating this data with internal banking information helps enhance credit risk models and improves the accuracy of borrower evaluations.


Metadata Analysis of the External_Cibil_Dataset.xlsx File
1. Dataset Overview
The dataset contains 51,336 records and 62 columns.
It consists of customer credit behavior data, which can be used for credit risk modeling.
The dataset includes demographic variables, credit history, delinquency records, credit inquiries, and utilization metrics.
2. Key Metadata Fields
Below are the major attributes categorized by their function:

A. Identification and Status Fields

1.PROSPECTID: Unique identifier for a customer.

2.Credit_Score: Numerical credit score assigned to the customer.

3.Approved_Flag: Loan approval status (P1, P2, etc.).

B. Delinquency and Payment History

1.time_since_recent_payment: Time since last payment.

2.time_since_first_deliquency: Time since the first delinquency.

3.time_since_recent_deliquency: Time since the most recent delinquency.

4.num_times_delinquent: Number of times the customer has been delinquent.

5.max_delinquency_level: Maximum level of delinquency experienced.

C. Loan and Credit Behavior

1.num_times_30p_dpd: Number of times the customer was 30+ days past due.

2.num_times_60p_dpd: Number of times 60+ days past due.

3.num_std, num_std_6mts, num_std_12mts: Number of standard loans over different periods.

4.num_sub, num_sub_6mts, num_sub_12mts: Number of subprime loans.

5.num_dbt, num_dbt_6mts, num_dbt_12mts: Number of debt accounts.


D. Credit Utilization and Inquiries


1.tot_enq: Total credit inquiries made by the customer.

2.CC_enq, PL_enq: Credit card and personal loan inquiries.

3.CC_utilization, PL_utilization: Credit and personal loan utilization rates.


E. Demographics

1.MARITALSTATUS: Marital status of the customer.

2.EDUCATION: Education level of the customer.

3.AGE: Age of the customer.

4.GENDER: Gender of the customer.
