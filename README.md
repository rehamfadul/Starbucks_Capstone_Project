# Starbucks_Capstone_Challenge

### Project Motivation:
Starbucks sends out an offer to users of the mobile app. An offer can be merely an advertisement for a drink or an actual offer such as a discount or BOGO (buy one get one free). Some users might not receive any offer during certain weeks. Our task is to combine transaction, demographic and offer data to determine which demographic groups respond best to which offer type.

### Required Libraries:
- pandas
- numpy
- math
- json
- datetime
- matplotlib
- seaborn
- sklearn
- pickle

### Files:
The data is contained in three files:

- portfolio.json - containing offer ids and meta data about each offer (duration, type, etc.)
- profile.json - demographic data for each customer
- transcript.json - records for transactions, offers received, offers viewed, and offers completed

#### portfolio.json

id (string) - offer id
offer_type (string) - type of offer ie BOGO, discount, informational
difficulty (int) - minimum required spend to complete an offer
reward (int) - reward given for completing an offer
duration (int) - time for offer to be open, in days
channels (list of strings)

#### profile.json

age (int) - age of the customer
became_member_on (int) - date when customer created an app account
gender (str) - gender of the customer (note some entries contain 'O' for other rather than M or F)
id (str) - customer id
income (float) - customer's income

#### transcript.json

event (str) - record description (ie transaction, offer received, offer viewed, etc.)
person (str) - customer id
time (int) - time in hours since start of test. The data begins at time t=0
value - (dict of strings) - either an offer id or transaction amount depending on the record

### Results
The findings of this project's anslysis can be found HERE https://rehamfadul.medium.com/a-data-science-challenge-towards-better-starbucks-offers-ab1c0d4fe6e1.

### Acknowledgements
This project is part of Udacity Data Scientist Nanodegree program.