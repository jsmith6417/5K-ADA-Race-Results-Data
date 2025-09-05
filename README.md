# ADA Race Results Programs

This repository contains two Python Jupyter Notebook programs for working with American Diabetes Association (ADA) race results. Together, they automate data collection and preparation, eliminating manual effort and reducing errors.

## Motivation
Collecting ADA race results manually requires repeatedly copying and pasting rows across multiple pages. This is slow, error-prone, and becomes overwhelming once results scale from a few entries to several thousand after the event begins. Automating the process ensures accuracy, saves time, and reduces the stress of handling large volumes of data.  

## Programs

### 1. **ADA Race Results**
- Automates the process of connecting to ADA race results pages.  
- Identifies headers and extracts data row by row across multiple pages.  
- Replaces manual copy-and-paste, which is slow and error-prone.  
- Scales efficiently from a small dataset (when results first open) to several thousand records once the event begins.  
- Saves time and reduces stress during high-volume data collection.

### 2. **Clean ADA Race Results SQLite**
- Cleans and standardizes the SQLite race results database.  
- Removes duplicates and ensures consistent formatting.  
- Prepares the dataset for downstream analysis and visualization.  
- Ensures data integrity across multiple event results.  

## Features
- Automated retrieval of race results directly from the source.  
- Structured data storage in SQLite.  
- Cleaning and transformation workflows to create analysis-ready data.  
- Scalable for handling thousands of race result records.  

## Visualizations
Explore the interactive Tableau dashboards here:  
[5K@ADA Race Results](https://public.tableau.com/views/5KADAResults/5KADARaceResults?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

## Article at JCS Analytics
**Adapting the 5K@ADA Race Results Project for 2025**  
https://jcsanalytics.com/index.php/adapting-the-5k-ada-race-results-project-for-2025
