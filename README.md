# Weekly Fuel Price Volatility and Spike Detection in Cavite

## Problem Statement
I want to answer, "How volatile are weekly gasoline and diesel prices in Cavite during 2026?" by analyzing weekly changes in gasoline and diesel prices, this project will identify weeks with significant price spikes and provide a better understanding of fuel price trends throughout 2026.

## Audience
This project is intended for daily commuters in Cavite who want to better understand how fuel prices change over time and how those changes may affect their transportation expenses. The insights may also be useful to transport operators, delivery drivers, and local policymakers who monitor transportation costs and fuel price trends.

## KPI or Key Metric
The primary KPI for this project is fuel price volatility, measured using:
- Average week-to-week price change (PHP per liter)
- Average week-to-week percentage change (%)
- Frequency of significant weekly price increases (price spikes)

## Likely Data Source
I will use the Department of Energy (DOE) Philippines (https://www.doe.gov.ph/), specifically the PRICE MONITORING OF LIQUID FUELS – Region IV-A (CALABARZON) weekly reports. These official PDF reports provide weekly gasoline and diesel prices from different fuel stations across Cavite. 

## Possible Final Dashboard
The dashboard should help the audience quickly see:
- Weekly gasoline and diesel price trends in Cavite
- Week-to-week fuel price changes
- Fuel price volatility throughout 2026
- Weeks with significant price spikes
- Comparison of gasoline and diesel price movements
- Summary statistics describing fuel price behavior over time

## Data Source Notes

### Primary Source
- Name: PRICE MONITORING OF LIQUID FUELS - REGION IV-A
- URL: https://doe.gov.ph/articles/group/liquid-fuels
- Format: PDF
- Coverage: 
    - Weekly fuel price monitoring reports for Region IV-A (CALABARZON), including Cavite municipalities and cities. 
    - The reports contain gasoline, RON 100, RON 97, RON 95, RON 91, diesel, diesel plus, and kerosene prices from multiple fuel companies such as Petron, Shell, Caltex, Phoenix, Unioil, Flying V, PTT, Independent Stations. 
    - Each report also provides an Overall Range from lowest to highest observed price and Common Price for each fuel type.
- Why it fits the problem: The reports are published by the Department of Energy (DOE) and provide official weekly fuel prices for Cavite, allowing weekly analysis of fuel price volatility and identification of significant price increases.
- Known limitations: 
    - Data is provided in PDF format and requires extraction before analysis.
    - Some fuel stations or brands may have missing values ("No LFRO" or blank cells).
    - Reports are published weekly, so there is no daily price data.

