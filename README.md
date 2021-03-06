# IEEE-Fradulent-Data(EDA)

This python notebook was created from the Datasets provided by IEEE-CIS Fraud Detection competition from Kaggle. In this competition you are predicting the probability that an online transaction is fraudulent, as denoted by the binary target isFraud. I have done a basic exploratory data analysis for the card transactions. There are two sets of training data and one set of testing data. I have attached the link of the training dataset. The datasets can be downloaded from the link below.
https://www.kaggle.com/c/ieee-fraud-detection/data

I have below given what each column represents from both the datasets

**Transaction Table**

- TransactionDT: timedelta from a given reference datetime (not an actual timestamp)
- TransactionAMT: transaction payment amount in USD
- ProductCD: product code, the product for each transaction
- card1 - card6: payment card information, such as card type, card category, issue bank, country, etc.
- addr: address
- dist: distance
- P_ and (R__) emaildomain: purchaser and recipient email domain
- C1-C14: counting, such as how many addresses are found to be associated with the payment card, etc. The actual meaning is masked.
- D1-D15: timedelta, such as days between previous transaction, etc.
- M1-M9: match, such as names on card and address, etc.
- Vxxx: Vesta engineered rich features, including ranking, counting, and other entity relations.

**Categorical Features:**

- ProductCD
- card1 - card6
- addr1, addr2
- Pemaildomain Remaildomain
- M1 - M9

https://www.kaggle.com/c/ieee-fraud-detection/discussion/101203

**Identity Table**

Variables in this table are identity information – network connection information (IP, ISP, Proxy, etc) and digital signature (UA/browser/os/version, etc) associated with transactions.
They're collected by Vesta’s fraud protection system and digital security partners.
(The field names are masked and pairwise dictionary will not be provided for privacy protection and contract agreement)

- Categorical Features:
- DeviceType
- DeviceInfo
- id12 - id38

A huge shout out to the authors who helped me build my model

- https://www.kaggle.com/c/ieee-fraud-detection/discussion/111696
- https://www.kaggle.com/kabure/extensive-eda-and-modeling-xgb-hyperopt

**Fradulent Transactions Part 2:**
This is the link for the second part of the notebook in case it doesnt open itself inside of github

- https://nbviewer.jupyter.org/github/Kuriankkr/Predicting-Fradulent-Card-Transactions/blob/master/Fradulent%20_Transaction_Part2.ipynb


