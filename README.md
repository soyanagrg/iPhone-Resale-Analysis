# iPhone Resale Market Analysis 📱

Analysis of the US iPhone resale market using a dataset of 2,371 
listings to understand what factors influence resale prices and 
which models are most actively traded.

## Tools Used
- Python
- Pandas
- Numpy
- Matplotlib

## Questions Analyzed
1. Average Resale Price by iPhone Condition
2. Average Resale Price by Storage Size
3. Top Selling iPhone Models
4. Top 10 States by Average iPhone Resale Price

## Key Findings
- Higher storage does not always mean higher resale price — 
  256GB averages higher than 512GB, likely due to generation differences
- Geographic location impacts resale price — Pennsylvania 
  leads with an average of $873 despite Texas having the most listings
- Newer iPhone models are rarely found on the resale market — 
  consumers prefer buying new devices from retailers directly

## Dataset
Source: Kaggle
[ecommerce_iphone_resale_market_intelligence_usa_2026]

## Notes
- sold column had 1,459 missing values — analysis based on 
  available data only
- Only states with 20+ listings were included for regional 
  pricing analysis
