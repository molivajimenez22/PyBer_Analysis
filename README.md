# PyBer_Analysis

## Overview
I will be analyzing the relationship between city type and number of riders utilizing PyBer ride sharing services. Additionally, I will be calculating the percentage total fares, riders and drivers by city type. The goal of this analysis is to help the company improve access to ride sharing services and determine affordability. 

**City Type:** Urban, Suburban, Rural

**Dataset (2)**: City and Rides

## Analysis
To start the analysis, I merged two sets of data. Using Matplotlib in Jupyter Notebook, I created charts to visualize the findings. All three charts below show a high volume of rides and drivers in urban cities, followed by suburban and then rural. 
 
<p align="center" width="100%">
    <img width="66%" src="https://github.com/molivajimenez22/PyBer_Analysis/blob/main/Resources/AnalysisFinal.png">
 
## Results

### Summary Dataframe
As the charts above indicated, urban cities had the highest activity. The summary below was created using the groupsby() function and the purpuse is to outline details for fare per ride, fare per driver and calculates the average fare per ride and driver. Creating this summary allows me to more clearly see that activity in each city. 

<p align="center" width="100%">
    <img width="66%" src="https://github.com/molivajimenez22/PyBer_Analysis/blob/main/Resources/summary%20of%20dataframe.png">
 
 1. Highest Volume: the urban city type had the highest volume at 1,625 rides, 2,405 drivers and average fare of $24.53 per ride and $16.57 per driver. All totaling to $39,854.38. 
 2. Lowest Volume: the rural city type had the lowest volume at 125 rides (-92% vs. urban), 78 drivers (-97% vs. urban), $34.62 (+29% vs. urban), $55.49 (+70 vs. urban), totaling $4,327.93 (-821% vs. urban).
 
### Total Fares by City Type
  To visualize the total fares, I created the multi-line chart below. 
 
  <p align="center" width="100%">
    <img width="66%" src="https://github.com/molivajimenez22/PyBer_Analysis/blob/main/Resources/Multiple%20Line%20Plot.png">
   
   In this summary line chart, we can see weekly fare by city type. All three cities started to see an increase with the highest peak at the end of February. Urban city type saw an ebb and flow throughout March while rural city saw another peak in early April. Suburban city started to see another peak toward the end of April. 

## Summary

   1. PyBer is performing well in the Urban city type. There are plenty of drivers and given the lower fares, I assume the rides are short distances.
   2. My recommendation is that PyBer invest in improving affortability in the rural city type. Given the fares, I imagine the rides are longer so how can the compnay improve affortability with longer rides?
