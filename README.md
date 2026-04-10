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
- Higher storage does not always mean higher resale price as 256GB averages higher than 512GB, likely due to generation differences
  <img width="580" height="455" alt="Average Price of iPhone Resale according to storage" src="https://github.com/user-attachments/assets/c4484f0b-0d7a-478d-b474-2fb2be6443ec" />

- Geographic location impacts resale price. Pennsylvania leads with an average of $873 despite Texas having the most listings
  <img width="620" height="470" alt="Top 10 States by Average iPhone Resale Price" src="https://github.com/user-attachments/assets/408edf94-1535-4b83-8e50-e4b765915ec3" />

  
- Newer iPhone models are rarely found on the resale market since consumers prefer buying new devices from retailers directly
  <img width="643" height="511" alt="Top Selling iPhone Models" src="https://github.com/user-attachments/assets/490e0ccb-86a4-418b-bf6f-5becd5e4d8e0" />


## Dataset
Source: Kaggle
[ecommerce_iphone_resale_market_intelligence_usa_2026]

## Notes
- Sold column had 1,459 missing values — analysis based on 
  available data only
- Only states with 20+ listings were included for regional 
  pricing analysis
