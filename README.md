# PhonePe-Pulse-Data-Analysis 

## Project Overview

This project analyzes digital payment trends using the PhonePe Pulse dataset.

The objective is to understand transaction behavior, user adoption, payment preferences, and regional growth patterns across India.

---

## Business Problem

Digital payments have transformed the financial ecosystem in India.

This analysis aims to answer:

- Which transaction types dominate the platform?
- Which states generate the highest transaction volumes?
- How are registered users growing over time?
- What is the relationship between app engagement and transactions?
- How does transaction value vary across regions?

---

## Dataset

Source: PhonePe Pulse Dataset

The dataset contains:

### State-Level Data
- State
- Year
- Quarter
- Transactions
- Amount (INR)
- Registered Users
- App Opens

### Transaction Data
- Transaction Type
- Transaction Count
- Transaction Amount

### Device Data
- Brand-wise device usage
- User adoption metrics

### District Data
- District-wise users
- Population
- Density
- Geographic information

---

## Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

---

## Analysis Performed

### Data Cleaning
- Missing value checks
- Data type corrections
- Duplicate validation

### Exploratory Data Analysis

- State-wise transaction analysis
- Transaction amount analysis
- User growth analysis
- App opens trend analysis
- Device market share analysis
- District demographic analysis

---

## Key Findings

### Transaction Behavior

- Peer-to-peer payments accounted for the highest number of transactions.
- Merchant payments ranked second in transaction volume.
- Financial services transactions represented the smallest share.

### User Growth

- Registered users and app opens increased significantly across states.
- User adoption accelerated during later quarters.

### Geographic Insights

- Certain states contributed disproportionately to transaction volume.
- District-level demographics influenced adoption patterns.

### Platform Engagement

- Higher app opens generally correlated with higher transaction activity.

---

## Skills Demonstrated

- Data Cleaning
- Exploratory Data Analysis
- Data Visualization
- Business Analytics
- Trend Analysis
- Customer Behavior Analysis
- Python Programming
- Data Storytelling



---

# Summary :

#1. Uttar Pradesh has the highest number of districts i.e. 75. As UP is geographically and demographically 
#large, payment service providers should prioritize creating district-level targeted campaigns instead of 
#a single state-wide campaign.

#2.Top 5 states with highest transaction volume:  
            
#	       State        Transactions
#15       Karnataka    2981044533
#20     Maharashtra    2833670154
#31       Telangana    2347430243
#1   Andhra Pradesh    1781091169
#28       Rajasthan    1382918930

#5 states with lowest transaction volume:  

#                       State      Transactions
#22                  Meghalaya       5648913
#23                    Mizoram       2162776
#17                     Ladakh       1880109
#0   Andaman & Nicobar Islands       1223565
#18                Lakshadweep         71610

#3. District with Highest population is North 24 parganas, West Bengal
#and lowest population is Lakshadweep, Lakshadweep.

#4. Average transaction value is the highest in Ladakh and lowestest in
#West Bengal.

#5. The highest transactions are done under the "Peer to peer payments" transaction type
#and lowest number of transaction are done under "Financial services". Company should increase awareness of 
#Financial Services (insurance, loans, bill payments, investments) inside the app.

#6. Telangana has the highest and Lakshadweep as the lowest number of Registered users for the app. Telangana 
#should invest in UPI upgrades and new features on the app. Lakshadweep should increase awareness campaigns, 
#and Government partnerships to improve connectivity.


---

## Author

Suparna Guha
