
Dataset Statistics Report
-------------------------

Basic Information:
- Total instances: 1,000,000
- Number of features: 32
- Missing values: 0
- Duplicate rows: 0
- Fraud class distribution: 
  � Legitimate (0): 988,971 
  � Fraudulent (1): 11,029

Numerical Features Summary:
|                                  |   count |    mean |     std |     min |     25% |     50% |     75% |      max |
|:---------------------------------|--------:|--------:|--------:|--------:|--------:|--------:|--------:|---------:|
| fraud_bool                       |   1e+06 |    0.01 |    0.1  |    0    |    0    |    0    |    0    |     1    |
| income                           |   1e+06 |    0.56 |    0.29 |    0.1  |    0.3  |    0.6  |    0.8  |     0.9  |
| name_email_similarity            |   1e+06 |    0.49 |    0.29 |    0    |    0.23 |    0.49 |    0.76 |     1    |
| prev_address_months_count        |   1e+06 |   16.72 |   44.05 |   -1    |   -1    |   -1    |   12    |   383    |
| current_address_months_count     |   1e+06 |   86.59 |   88.41 |   -1    |   19    |   52    |  130    |   428    |
| customer_age                     |   1e+06 |   33.69 |   12.03 |   10    |   20    |   30    |   40    |    90    |
| days_since_request               |   1e+06 |    1.03 |    5.38 |    0    |    0.01 |    0.02 |    0.03 |    78.46 |
| intended_balcon_amount           |   1e+06 |    8.66 |   20.24 |  -15.53 |   -1.18 |   -0.83 |    4.98 |   112.96 |
| zip_count_4w                     |   1e+06 | 1572.69 | 1005.37 |    1    |  894    | 1263    | 1944    |  6700    |
| velocity_6h                      |   1e+06 | 5665.3  | 3009.38 | -170.6  | 3436.37 | 5319.77 | 7680.72 | 16715.6  |
| velocity_24h                     |   1e+06 | 4769.78 | 1479.21 | 1300.31 | 3593.18 | 4749.92 | 5752.57 |  9506.9  |
| velocity_4w                      |   1e+06 | 4856.32 |  919.84 | 2825.75 | 4268.37 | 4913.44 | 5488.08 |  6994.76 |
| bank_branch_count_8w             |   1e+06 |  184.36 |  459.63 |    0    |    1    |    9    |   25    |  2385    |
| date_of_birth_distinct_emails_4w |   1e+06 |    9.5  |    5.03 |    0    |    6    |    9    |   13    |    39    |
| credit_risk_score                |   1e+06 |  130.99 |   69.68 | -170    |   83    |  122    |  178    |   389    |
| email_is_free                    |   1e+06 |    0.53 |    0.5  |    0    |    0    |    1    |    1    |     1    |
| phone_home_valid                 |   1e+06 |    0.42 |    0.49 |    0    |    0    |    0    |    1    |     1    |
| phone_mobile_valid               |   1e+06 |    0.89 |    0.31 |    0    |    1    |    1    |    1    |     1    |
| bank_months_count                |   1e+06 |   10.84 |   12.12 |   -1    |   -1    |    5    |   25    |    32    |
| has_other_cards                  |   1e+06 |    0.22 |    0.42 |    0    |    0    |    0    |    0    |     1    |
| proposed_credit_limit            |   1e+06 |  515.85 |  487.56 |  190    |  200    |  200    |  500    |  2100    |
| foreign_request                  |   1e+06 |    0.03 |    0.16 |    0    |    0    |    0    |    0    |     1    |
| session_length_in_minutes        |   1e+06 |    7.54 |    8.03 |   -1    |    3.1  |    5.11 |    8.87 |    85.9  |
| keep_alive_session               |   1e+06 |    0.58 |    0.49 |    0    |    0    |    1    |    1    |     1    |
| device_distinct_emails_8w        |   1e+06 |    1.02 |    0.18 |   -1    |    1    |    1    |    1    |     2    |
| device_fraud_count               |   1e+06 |    0    |    0    |    0    |    0    |    0    |    0    |     0    |
| month                            |   1e+06 |    3.29 |    2.21 |    0    |    1    |    3    |    5    |     7    |

Categorical Features Summary:
|                   |   Unique Values | Most Frequent Value   |   Frequency of Most Common |
|:------------------|----------------:|:----------------------|---------------------------:|
| payment_type      |               5 | AB                    |                     370554 |
| employment_status |               7 | CA                    |                     730252 |
| housing_status    |               7 | BC                    |                     372143 |
| source            |               2 | INTERNET              |                     992952 |
| device_os         |               5 | other                 |                     342728 |

Top Correlations with Fraud Class:
|                              |         0 |
|:-----------------------------|----------:|
| fraud_bool                   | 1         |
| credit_risk_score            | 0.0706236 |
| proposed_credit_limit        | 0.0689066 |
| customer_age                 | 0.0629587 |
| income                       | 0.0450792 |
| device_distinct_emails_8w    | 0.0357041 |
| current_address_months_count | 0.0337012 |
| email_is_free                | 0.0277576 |
| foreign_request              | 0.0168846 |
| month                        | 0.01325   |
