# Funnel Analysis using Google Sheets

## Overview

This project analyzes a user signup and purchase funnel using Google Sheets.

The goal was to:
- Count unique users at each stage
- Calculate conversion rates
- Identify the biggest drop-off in the funnel

## Dataset

The dataset contains three columns:

- user_id
- step
- timestamp

## Funnel Stages

1. visited_site
2. signup_started
3. details_filled
4. email_verified
5. purchase_completed

## Results

| Stage | Users | Conversion Rate | Drop-off |
|-------|-------:|---------------:|---------:|
| visited_site | 200 | - | 50 |
| signup_started | 150 | 75.00% | 54 |
| details_filled | 96 | 64.00% | 44 |
| email_verified | 52 | 54.17% | 8 |
| purchase_completed | 44 | 84.62% | - |

## Key Finding

The biggest drop-off occurred between **signup_started** and **details_filled**, where **54 users** left the funnel.

## Tools Used

- Google Sheets
- Pivot Tables
- COUNTUNIQUE
- Basic Spreadsheet Formulas

## Files

- Funnel_Analysis_Assignment.xlsx
- funnel_events_sample.csv
