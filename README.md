# NYC Taxi Profitability and Activity Analysis

![Marvelous-Mrs-Maisel-Filming-Locations-Horn-and-Hardart-Set-Amazon-Studios-Crown-Heights-Brooklyn-NYC14](/Marvelous-Mrs-Maisel-Filming-Locations-Horn-and-Hardart-Set-Amazon-Studios-Crown-Heights-Brooklyn-NYC14.jpg)

## Overview

New York City Taxi and Limousine Commission (TLC) dataset consists of detailed transactions of TLC from 2 different payment gateway providers.
The dataset doesn’t differentiate between Medallion Cab or Boro Cab. It has variable that differentiate type of the taxi ride whether they are street-hail or ordered by dispatch.

- Up to 2600+ Daily Customer
- More than 13000 times pick-ups
- Dataset range from 1 Jan to 31 Jan in 2023
- More than 12000 Miles trip travelled

## General Problem

Albeit being the icon of the city, NYC TLC is still losing money from some unprofitable trips. One of the ways to handle this, is NYC TLC considered opening an ad space that targeted to the most audience within the busiest pick-up zone in the busiest pick-up time.

## Goals

To obtain the busiest pick-up spot and the most profitable spot, and recommend action on which pick-up spot that generates the least profit.

# Steps Of This Analysis

In this analysis we are going through some steps
1. Data Understanding
2. Data Cleaning
3. Data Enriching
4. Statistical Analysis
5. Data Analysis
6. Visualisation

## Variables
Dataset consists of variables:
- VendorID: ID of vendors
- Lpep Pickup Datetime: Datetime where a passenger is picked up
- Lpep Dropoff Datetime: Datetime where a passenger is dropped off
- Store and Forward Flag: To Flag whether the trip record was held in the vehicle memory before sending it to the vendor. (Yes or No)
- RateCodeID: Final Rate Code, in effect at the end of the trip (1=std; 2=JFK; 3=Newark; 4=Nassau|Westchester; 5=Nego Fare; 6=Group Fare)
- Pickup LocationID: ID of location where a passenger is picked up
- Dropoff LocationID : ID of location where a passenger is dropped off
- Passenger Count: Number of passenger in a trip
- Trip Distance: Distance of a trip
- Fare Amount: Amount of fare
- Extra: Surcharges 0.50$ rush hour or 1$ overnight charges
- MTA Tax: Automatically truggered based on the metered rate in use.
- Tip Amount: Amount of tip
- Tolls Amount: Amount of tolls paid in a trip
- Improvement Surcharge: $0.30 improvement surcharge assessed on hailed trips at the flag drop. The improvement surcharge began being levied in 2015.
- Total Amount: Amount charged to passengers. Cash Tips excluded
- Payment Type: type of payment (1= Credit Card; 2=cash; 3=No Charge; 4=Dispute; 5 = Unknown; 6=Voided Trip)
- Trip Type: type of taxi trip (1=Street-hail; 2=dispatch)
- Congestion surcharge: Amount added to the payment due to congestion

## Dashboard

For better experience in viewing the analysis result, check out the dashboard below:
https://public.tableau.com/app/profile/fauzan.harlyanto.putra/viz/NYCTaxiProfitabilityandActivityAnalysis/Dashboard1?publish=yes

# Purwadhika

This repository is part of my capstone projects in Purwadhika School, this is the second iteration of my projects. The capstone series consisted of 3 projects, make sure to check the first one in here:
https://github.com/zanputra/purwadhika_capstone_1
