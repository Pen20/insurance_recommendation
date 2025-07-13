## 📊 Dataset Description

| Column       | Description                                              | Type   | Example / Range             |
| ------------ | -------------------------------------------------------- | ------ | --------------------------- |
| `ID`         | Unique identifier                                        | int    | 63581743                    |
| `KIDSDRIV`   | Number of kids who drive                                 | int    | 0 to 4                      |
| `BIRTH`      | Date of birth (string format)                            | object | 16MAR39                     |
| `AGE`        | Age of the policyholder                                  | float  | 16 to 81                    |
| `YOJ`        | Years on the job                                         | float  | 0 to 23                     |
| `INCOME`     | Annual income (some missing, in strings like "\$67,349") | object | \$0 to \$1M+ (some missing) |
| `HOME_VAL`   | Value of the home                                        | object | "\$124,191", "\$0", missing |
| `OCCUPATION` | Job type (missing values present)                        | object | Doctor, Manager, etc.       |
| `TRAVTIME`   | Travel time to work (in minutes)                         | int    | 0 to 127                    |
| `CAR_USE`    | Car usage category                                       | object | Commercial / Private        |
| `BLUEBOOK`   | Car value estimate                                       | object | "\$15,935", etc.            |
| `CAR_TYPE`   | Type of car                                              | object | Minivan, SUV, etc.          |
| `RED_CAR`    | Is the car red?                                          | object | yes / no                    |
| `CLM_FREQ`   | Claim frequency (number of claims made)                  | int    | 0 to 5                      |
| `REVOKED`    | Is license revoked?                                      | object | yes / no                    |
| `CLM_AMT`    | Claim amount                                             | object | "\$0", "\$4,461", etc.      |
| `CAR_AGE`    | Age of the car (in years)                                | float  | -3 to 28                    |
| `CLAIM_FLAG` | Whether a claim was made (target variable)               | int    | 0 = No, 1 = Yes             |
| `URBANICITY` | Urban area status                                        | object | Highly Urban / Urban        |
