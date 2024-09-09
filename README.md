# project-1
Repo for the first Project in data science bootcamp

## Stat Analysis
Contained in the files
- airfare.ipynb
- evan.ipybn
- Dimity.ipybn

## Questions this Analysis attempts to cover
- How does GDP growth and airfare prices relate over time?
- Is there a clear relationship between flight demand and a state’s GDP?
- Do wealthier states have higher or lower airline ticket prices?
- Do lower-income states face higher airfare costs compared to wealthier states?

## Data sources
- https://www.kaggle.com/datasets/bhavikjikadara/us-airline-flight-routes-and-fares-1993-2024
- https://www.kaggle.com/datasets/solorzano/gdp-per-capita-in-us-states
- https://www.kaggle.com/datasets/aravindram11/list-of-us-airports
- https://www.kaggle.com/datasets/flashgordon/usa-airport-dataset 
- https://www.kaggle.com/datasets/bingecode/us-national-flight-data-2015-2020

## Data cleaning
- Some areas like NJ have large amounts of missing flight because they are grouped into metropolitan areas
  - This data was removed during analysis
- There is some unexplained 0 or empty values in this data that was removed

## Interesting Outliers, and caveats with the data sources
- Alaska (As this is only domestic air travel, and there's no all in the US ground route. Plus weather)
- Delaware (has odd/inconsistent flight scheduals)
- The data sets used are not intended for production, but mostly for educational purposes
- 2020 and years after not looked at because of the effects of covid on air travel

## Example graphic from the project
![alt text](https://github.com/cosmopaladin/project-1/blob/main/fig_7_Airfare_Comparison_Boxplot.png?raw=true)


