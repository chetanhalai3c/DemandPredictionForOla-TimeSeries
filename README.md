# DemandPredictionForOla-TimeSeries

This project predict ride requests (demand forecast) for a particular latitude and longitude for a requested future time window/duration.

## Problem statements

Ola Bikes are suffering losses and losing out from their competition due to their inability to fulfill the ride requests of many users. To tackle this problem I am asked to predict demand for rides in a certain region and a given future time window. This would help them allocate drivers more intelligently to meet the ride requests from users.

## Project Purpose 

The goal of this project is to predict ride requests (demand forecast) for a particular latitude and longitude for a requested future time window/duration.

## Data Description

Raw Data contains a `number` (unique for every user), ride request DateTime (IST time),
pickup and drop location latitude, and longitude.

**Data Fields**

1. number: unique id for every user
2. ts: DateTime of booking ride (IST time)
3. pick_lat: ride request pickup latitude
4. pick_lng: ride request pickup longitude
5. drop_lat: ride request drop latitude
6. drop_lng: ride request drop longitude

## Solution Steps

The project was accomplished through the following steps 
1) Data importation
   * Imported data into jupyter notebook using pandas 
3) Cleaning
4) Feature Engineering 
5) Exploratory Data Analysis
6) Data Preparation For Modeling
7) Building Models
8) Model Deployment
9) Model Monitoring  
   

