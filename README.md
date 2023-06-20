# 2022-Toronto-Building-Evaluation-Analysis

💻 **Programming Language:** R <br>
📚 **Libraries:** tidyverse, lubridate, dplyr, ggplot2, tidyr, leaflet <br>
📌 **Professional Ability:** Data Cleaning, Exploratory Data Analysis, Evaluation, Interpretation, Data Visualization <br>

## Description
Toronto launched an evaluation result for apartment buildings registered with RentSafeTO. It will help improve access to information for both existing tenants and those looking for a new home. Making evaluation results more accessible increases transparency on the quality of apartment buildings across Toronto and makes building owners and operators more accountable to current and prospective tenants.

Our analysis report aims to summarize the dataset statistically, offering a quick understanding of the data's significance. By presenting statistical data, it enables tenants to grasp the safety status and scores of different areas, aiding them in making informed rental choices. Additionally, it helps building owners and operators identify benchmarks for quality construction. Furthermore, the report can highlight areas requiring special attention, alerting law enforcement officers to locations with lower safety factors.

Overall, this analysis report bridges the gap between the dataset and its implications. It empowers tenants and stakeholders by promoting informed decision-making, accountability, and safer living environments. With improved transparency and access to evaluation results, tenants can make better rental choices, building owners can strive for excellence, and law enforcement officers can prioritize areas in need of attention. Together, these efforts contribute to a safer and more secure housing landscape in Toronto.

<img width="684" alt="3" src="https://github.com/HsinFangHu/2022-Toronto-Building-Evaluation-Analysis/assets/135067776/240790e1-87ea-44d0-96a7-d8852decc737">


## Dataset
This dataset contains building evaluation scores for buildings in Toronto registered with RentSafeTO*. Buildings must undergo evaluation at least once every three years. During evaluations, Bylaw Enforcement Officers inspect common areas, mechanical and security systems, parking and exterior grounds. Each item is inspected and assigned a score from one to five, with one being the lowest and five being the highest. If an item is not applicable to the building at the time of evaluation, the score will show as blank in the dataset.

*RentSafeTO: Apartment Building Standards is a bylaw enforcement program established in 2017 to ensure that owners and operators of apartment buildings with three or more stories or 10 or more units comply with building maintenance standards.

Data Source: https://open.toronto.ca/dataset/apartment-building-evaluation/

## Report Findings
By delving into the results of the 2022 Toronto Building Assessment, we have extracted some fascinating insights into the state of building safety and compliance in specific regions. We made the following findings:
1. Building Safety Scores: The safety scores for private buildings, Toronto Community Housing Corporation buildings, and social housing providers are similar. However, the parking areas in all three building types have lower scores (below 3.5), requiring attention from law enforcement officers.

<img src="https://github.com/HsinFangHu/2022-Toronto-Building-Evaluation-Analysis/assets/135067776/522af1d5-250b-4067-8758-ae47082db528" width="600">


2. Evaluation Time Seasonalization: Evaluations tend to peak at the end of each year, possibly due to performance reviews for law enforcement officers. This concentration of evaluations within a short period may lead to less precise scores. It is recommended to distribute evaluations evenly throughout the year.

<img src="https://github.com/HsinFangHu/2022-Toronto-Building-Evaluation-Analysis/assets/135067776/71fa58de-38f6-4bfd-ab6d-eb690792c778)" width="600">


3. Geographic Distribution: Analyzing the latitude and longitude data reveals the distribution of buildings across different areas of Toronto. This information can assist tenants in making decisions based on the safety of neighborhoods.

These findings provide valuable insights into building safety and compliance in Toronto, enabling better decision-making for tenants and highlighting areas for improvement in evaluation processes.

