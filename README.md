# Udacity_capstone_project

### Installation
To run this code, you just need to have Anaconda installed.

### About The Project
Once every few days, Starbucks sends out an offer to users of the mobile app. An offer can be merely an advertisement for a drink or an actual offer such as a discount or BOGO (buy one get one free). Some users might not receive any offer during certain weeks. Moreover, not all users receive the same offer. 

The task is to determine which demographic groups respond best to which offer type. The dataset we use is a simplified version of the real Starbucks app because the underlying simulator only has one product whereas Starbucks actually sells dozens of products.

Every offer has a validity period before the offer expires. As an example, a BOGO offer might be valid for only 5 days.

We are given transactional data showing user purchases made on the app including the timestamp of purchase and the amount of money spent on a purchase. This transactional data also has a record for each offer that a user receives as well as a record for when a user actually views the offer. There are also records for when a user completes an offer.
We have to keep in mind that someone using the app might make a purchase through the app without having received an offer or seen an offer. Therefor it is critical to do a good job preprocessing the data.

### Project goal
From a business perspective, if a customer is going to make a 10 dollar purchase without an offer anyway, you wouldn't want to send a buy 10 dollars get 2 dollars off offer.
Therefor, the question is:
#### What attributes (age, gender, income, etc.) have the highest influence on a person's choice to respond to a starbucks offer or not?

### Data description
The data is contained in three files:

portfolio.json - containing offer ids and meta data about each offer (duration, type, etc.)
profile.json - demographic data for each customer
transcript.json - records for transactions, offers received, offers viewed, and offers completed

### Results

An explanation of the data preprocessing steps and my results can be found [here](). 

### Licensing and Acknowledgements

Data and a few comments on how what to pay attention to were provided by Udacity. 





