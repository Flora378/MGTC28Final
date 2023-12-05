### DISCLAIMER: All data is **simulated** and **not real**.

# Company Need State Analysis
MGTC28 Final Group Project

## Tableau Link:
https://public.tableau.com/views/CompanyNeedStateAnalysis/CompanyNeedStateAnalysis?:language=en-US&:display_count=n&:origin=viz_share_link

## Project Plan
**Group members:** Flora Kwan, Katherine Feng, Minda Shi

Our analysis will consist of using forecasting to determine an optimal sales plan for a specific need state.

We will need to clean the data set. The Pandas library will be used to clean and combine data sets. 

We will use and combine all the data sets, but we will mostly be focusing on factory POS and total trade spend. After cleaning the data, we will look at the analysis and seasonality trends then pick a need state to focus on. We will be using external data to aid our specific need state analysis, as we will be using web-scraping (including Reddit API, with Regex for parsing specific strings) to gather more data on factors affecting forecasting.

To do our analysis, we will be using Python, which has various libraries to support our project. As mentioned, the Pandas library will be helpful for cleaning the data. Statsmodel, Seaborn, and Matplotlib are libraries we can use to do regression analysis and visualize the data with graphs, respectively. Our code will be written in JupyterNotebook. Since this is a collaborative project, we will use GitHub to share the code and Git Bash to track its changes. We will also use Tableau for visualizing the data. 

Based on our findings, we will offer suggestions including when the need state should be promoted, and any adjustments that could be made to the trade spend and inventory.

### Division of Labour
* Cleaning and combining data sets (all members do their own and then combine insights)
* General analysis of data set (all members do their own and then combine insights)
* Specific need state analysis:
  - Use web-scraping to gather data on external factors tied to forecasting (Minda)
  - Insights from trade spend (Flora)
  - Create a time-series forecasting model to predict future sales/Conduct demand forecasting using time series decomposition (Katherine)
* Concluding analysis + Conclusion (all members)
