# College-Cost-Analysis
Analyzing college scorecard data to determine what variables impact the cost of private, non-profit higher education institutions.

In this project, I analyzed data about US post-secondary institutions about their characteristics, costs, and enrollment provided by the US Department of Education. I explored the data and narrowed down my focus to look at what variables might impact the cost of private, non-profit institutions. I formed a hypothesis and tested it, creating a multiple linear regression model through supervised machine learning. I also conducted a geospatial analysis to evaluate location as a potential influential factor. After these approaches failed to fully explain the data, I performed a k-means clustering algorithm using unsupervised machine learning. In the end, none of the variables I looked at were able to entirely explain cost, but it was clear they had some impact. I made a few recommendations regarding further steps to take and other data to gather and analyze. On a tangentially related note, I completed a time series analysis on the average SAT score of enrolled students at NYU (my alma mater).


Analysis results (this storyboard does not include every step of the analysis): https://public.tableau.com/views/CollegeCostAnalysis_16286284493200/CollegeCostAnalysis?:language=en-US&:display_count=n&:origin=viz_share_link


Breakdown of folders:
01 Project Management – includes project brief
02 Data
•	Original Data – includes original data sets
•	Prepared Data – includes manipulated data sets
03 Scripts – includes Jupyter notebooks


Data Source:
College Scorecard Data from the US Department of Education (accessed July 18, 2021) can be found here: https://collegescorecard.ed.gov/data/ 
Geographic data (US states json file) provided by CareerFoundry and accessed July 20, 2021
