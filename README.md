# Layoffs Data Cleaning & Exploratory Data Analysis

## Project Overview

This project uses MySQL to clean, transform, and explore a dataset containing company layoffs. The analysis focuses on preparing the data for reliable analysis and identifying patterns in layoffs across companies, countries, industries, stages, and time periods.

## Objectives

* Identify and remove duplicate records
* Standardize inconsistent data values
* Handle missing and null values
* Transform date fields into usable date formats
* Analyze layoffs by company, country, industry, and company stage
* Identify companies with the highest layoffs by year
* Calculate monthly layoffs and rolling totals

## Tools & Skills

* MySQL
* SQL
* Data Cleaning
* Exploratory Data Analysis (EDA)
* CTEs
* Window Functions
* `ROW_NUMBER()`
* `DENSE_RANK()`
* Aggregate Functions
* Data Standardization
* Missing Value Handling

## Data Cleaning

The cleaning process included:

* Removing duplicate records using `ROW_NUMBER()` and `PARTITION BY`
* Standardizing company and country names
* Standardizing industry values
* Converting date values into the SQL `DATE` format
* Handling missing industry information
* Removing records without meaningful layoff information
* Removing unnecessary columns after cleaning

## Exploratory Data Analysis

The analysis examined:

* Total layoffs by country
* Layoffs by company
* Layoffs by company stage
* Layoffs by year
* Monthly layoffs and rolling totals
* Companies with the highest layoffs each year
* Top 5 companies by layoffs for each year

## Key SQL Techniques

This project demonstrates practical use of:

* `ROW_NUMBER() OVER(PARTITION BY...)`
* `DENSE_RANK() OVER(PARTITION BY...)`
* Common Table Expressions (CTEs)
* Window functions
* Self-joins
* `CASE` expressions
* Aggregate functions
* Date conversion and manipulation
* `UPDATE`, `DELETE`, and `ALTER TABLE`

## Outcome

The project demonstrates a complete SQL workflow from raw data cleaning to exploratory analysis, with emphasis on data quality, transformation, and extracting meaningful insights from structured data.
