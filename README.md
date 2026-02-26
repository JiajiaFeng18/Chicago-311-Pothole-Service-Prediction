# Chicago Pothole Response Prediction (311 Service Analytics)
### Project Overview

This project aims to predict the operational efficiency of Chicago's 311 service. Specifically, the goal is to build a classification model that predicts whether a reported pothole will be responded to within seven days, regardless of the final action taken (filled, labeled as "not found," or escalated).
This is a typical Urban Informatics and Binary Classification problem where multiple heterogeneous datasets (Census, Traffic, and Service Requests) are joined to provide predictive insights.

### Dataset Description
The model integrates data from four primary sources:
- train.csv / test.csv: Primary pothole service requests (2011–2018).
- community_acs.csv: Demographic data (poverty rates, income, etc.) from the American Community Survey.
- congestion_region.csv: Aggregated traffic congestion estimates by region.
- community_region_crosswalk.csv: A mapping table to link Community Areas with Traffic Regions.
- Note on Temporal Alignment: As per project constraints, the most recent ACS data is used despite the pothole records spanning 2011–2018.
