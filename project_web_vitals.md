# Power Automate Web Vitals Tracker

## Project Overview

I created a 100% automated web vitals tracker for my business unit at Thermo Fisher Scientific. Its purpose is to keep track of the web performance metrics for around 20 URLs, so we can eventually compare the old website's performance to the new website's.

## A 3-Step Process
<img src="images/how to track core web vitals.png?raw=true"/>

## Make Scheduled Google API Calls with Power Automate Flow
1. Set recurrence
2. Access Excel Online + Read in list of URLs
3. Initialize variables for all metrics
4. Make a Google API call and receive JSON data for each URL
5. Parse JSON file for the specific metrics wanted, then update the variables
7. Add a row to Excel data table for each URL each day


<img src="images/Power Automate Flow.gif?raw=true"/>

## Display Data Using Power BI

(Image blurred for company data privacy)

<img src="images/BLURRED Assay Web Vitals Dashboard.png?raw=true"/>
