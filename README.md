# 311-Complaints
Optimize Parking Regulations using 311 Complaints.


Software: Tableau, Pentaho, Python, Oracle Cloud, SQL Developer

Data source:
https://data.cityofnewyork.us/Social-Services/311-Service-Requests-from-2010-toPresent/erm2-nwe9

# Introduction:

Each day, nyc311 receives thousands of requests related to several hundred types of non-emergency services, including noise complaints, drug activity and side street conditions. Among these complaints, illegal parking is a critical issue for NYC because it’s up to 146,240 complaints in 2017 and it can lead to multiple more severe problems around life in NYC, such as traffic jams or safety issues. We can easily find it when we walk around NYC. Therefore, we think people should attach importance to this problem and it is worth studying the problem. As the NYC parking rules, blocking the driveway, double parking, parking at a bus stop or hydrant or bike line are all in the scope of illegal parking.

Another reason that we want to study illegal parking in NYC is that We are interested in illegal parking from distinct dimensions such as location, time, day, and context. We will analyze this way to try to figure out the root reason of illegal parking and whether the parking lot resource is tight in NYC. Ultimately our goal is to optimize the parking rules to fit the parking demands.

# Steps:
## 1. Get the data from NYC OpenData
There are four steps required to download NYC OpenData data using the Socrata API:

Create a developer account
Create an application and receive an App Token
Locate data of interest and obtain its API endpoint
Use the App Token and API endpoint to query and download data

## 2. create ETL transformations for extracting and loading this data into the data warehouse schema. 

## 3. create a basic “Dashboard” application that displays and incorporates at least 3 different data representations such as graphs, maps, heatmaps, charts, tabular/cross-tab reports, etc.


