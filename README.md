# BLS State Labor Market Dataset

This repository contains code for collecting and processing state-level labor market data from the U.S. Bureau of Labor Statistics (BLS) Public Data API.

## Purpose

The purpose of this project is to create an original dataset of monthly labor market indicators for U.S. states. The dataset will be used to explore questions about unemployment patterns, employment levels, and labor force variation across states over time.

## Repository Structure

- `src/` - scripts for API requests and data cleaning  
- `data/` - final processd data.
- `notebooks/` - exploratory processing notebooks  
- `README.md` - repository overview  

## Data Source

Data are collected from the BLS Public Data API, primarily using state-level Local Area Unemployment Statistics.

## Variables

- state
- year
- unemployment rate
- hourly earnings
- industry
- CPI
- wage growth
- real wage index

## Workflow

1. Pull data from the BLS API  
2. Save raw responses  
3. Clean and merge the data  
4. Export a final CSV for analysis  
