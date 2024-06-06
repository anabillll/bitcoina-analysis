# CoinMarketCap Analysis

## Overview

This repository contains data and analysis scripts for the CoinMarketCap dataset. The dataset includes information about various cryptocurrencies, including their market capitalization and percentage changes over different time periods.

## Dataset

The dataset used in this project is `coinmarketcap_06122017.csv`, which contains the following columns:
- `id`: The unique identifier for each cryptocurrency.
- `market_cap_usd`: The market capitalization in USD.
- `percent_change_24h`: The percentage change in price over the last 24 hours.
- `percent_change_7d`: The percentage change in price over the last 7 days.

## Analysis

The analysis performed on this dataset includes:
1. **Filtering and Cleaning**: Removing entries with missing or zero values for market capitalization.
2. **Visualization**: Creating bar plots to show the top gainers and losers over 24 hours and 7 days.
3. **Market Cap Categories**: Grouping cryptocurrencies into large cap, mid cap, small cap, micro cap, and nano cap based on their market capitalization and visualizing the counts.

## Repository Structure

