# BLS State Labor Market Dataset

This repository contains code for collecting and processing state-level labor market data from the U.S. Bureau of Labor Statistics (BLS) Public Data API.

## Purpose

The purpose of this project is to create an original dataset of monthly labor market indicators for U.S. states. The dataset will be used to explore questions about unemployment patterns, employment levels, and labor force variation across states over time.

## Repository Structure

- `src/` - scripts for API requests and data cleaning  
- `data/` - both raw and final processd data.
- `notebooks/` - exploratory processing notebooks  
- `README.md` - repository overview  

## Data Source

Data are collected from the BLS Public Data API, primarily using state-level Local Area Unemployment Statistics.

## Planned Variables

- state
- year
- month
- unemployment_rate
- unemployment
- employment
- labor_force

## Workflow

1. Pull data from the BLS API  
2. Save raw responses  
3. Clean and merge the data  
4. Export a final CSV for analysis  

## Ethics

This project uses a documented public API and only collects public aggregate statistics. No personal or private data are involved.