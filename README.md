# King County Housing Market Analysis
Tools: Python, Pandas, Matplotlib, Excel

Overview:
An exploratory data analysis of 21,000+ residential home sales in King County, Washington, identifying key drivers of sale prices using Python.

Key Finding:
Build quality grade was the strongest predictor of sale price — top-grade homes averaged over 3x the price of the lowest-grade tier.

Files:
  notebook/king_county_analysis.ipynb — full analysis with code and visualizations
  notebook/king_county_analysis.html — rendered version of the notebook (no Python required to view)
  data/ — cleaned CSV files derived from the original dataset

Data Source: Harlfoxem. (2016). House Sales in King County, USA [Dataset]. Kaggle. https://www.kaggle.com/datasets/harlfoxem/housesalesprediction

Methods:
  Merged and cleaned multiple datasets using Pandas
  Built automated descriptive summaries using groupby aggregations, pivot tables, and crosstabs
  Profiled dataset across numeric and categorical variables to identify patterns and outliers
  Communicated findings through Matplotlib visualizations
