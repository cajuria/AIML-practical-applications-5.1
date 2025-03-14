# AIML-practical-applications-5.1
CAA AIML-Practical Applications 5.1

## Overview
In this first practical application assignment of the program, you will seek to answer the question, “Will a customer accept the coupon?” The goal of this project is to use what you know about visualizations and probability distributions to distinguish between customers who accepted a driving coupon versus those who did not.

## Data
This data is from the UCI Machine Learning Repository and was collected via a survey on Amazon Mechanical Turk. The survey describes different driving scenarios, including the destination, current time, weather, and passenger, and then asks people whether they will accept the coupon if they are the driver.There are three possible answers people can choose from:

*“Right away”
*“Later, before the coupon expires”
*“No, I do not want the coupon”
=>> The first two responses are labeled as “Y = 1,” and the third is labeled as “Y = 0.” There are five different types of coupons: Less expensive restaurants (under $20), coffee houses, carryout and takeaway, bars, and more expensive restaurants ($20–$50).


## Initial Analysis

The initial review of the data shows that the field car is almost of no value as it only contains 108 entries out of 12,684, thus obtaining a medain or similar value would not be representative of the data:


![image](https://github.com/user-attachments/assets/ad91187a-e82e-4917-8b11-bd3dc8027c30)

### Find out % of missing data:

![image](https://github.com/user-attachments/assets/4605b5fc-4e84-44e8-986d-a3a263a4679e)


### Next steps: 
 Drop car value
 Create Multiple charts for analysis: 
* General acceptance
* By Coupon types
* By Age
* By Expiration Type
* By passanger 
* By Temperature
* By Occupation
* By Education (And descending as well)
* Find correlation between Age, Income and Education and plot it
* Group data by Age for CoffeeHouse
* By Coupon Tyoe and Gender
* By Gender in General
* BY Destination
* By Income
* By Carry out and take away by destination

## Analysis Highlights
### General Overview
General acceptance shows a 57% ratio
Cofee House is the most accepted coupon by type
Most other charts do not sho major differences, including gender, age, etc

### Acceptance by Education
Customer with High School education tend to have a higher acceptance rates, and the acceptance rate decreases as does the education level, which would be interesting to further follow up

![image](https://github.com/user-attachments/assets/253f81fc-6982-4187-ac05-865fb4aa4357)

## Recommendations:
Furher research if the Acceptance by Destination (Not urgent) can be further explored, home and work seem evenly split and could further determine if a coffe on the way to work or a drink at the bar at the end of a day might be enticeing, as well as a take away for dinner as the charts showcase.

When not in a rush drivers area almost evenly divided between restaurant and take out.

## Final Note: 
The problem presented was too broad to the point that I had a hard time getting started and figuring out which route to go. Additionally never having used GitHub my account was blocked for a couple of weeks. Overall using Github is an area that still requires much more exploring for me. From navigating to understanding how to use it professionally.


