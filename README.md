# MSAI6102 Project
    
    NTU MSAI6102 2024Spring Project

## Project Structure

- **`docs\`:**
*documents consist of `project_overview`, `roadmap` and `POW` etc. Most Importantly, project notes prepared for report should also be included in this folder*.
*Majority of `docs\` are organized on* [**Notion Link**](https://www.notion.so/Teamspace-Home-5461cf9710624129b99e4f255369e91e)

- **`reference\`:**
*some references for project*

- **`report\`:**
*future report and related resources should be included in this folder*

- **`src\`:**
*project source codes and test/training data*
  - `data\`


```mermaid
---
title: Roadmap of Kaggle:Store Item Demand Forecasting Challenge
---
flowchart TB

start(("`Overview of Kaggle Competitions 
and Choose **Store Item Demand 
Forecasting Challenge**`"))

xgboost1(overview of xgboost)
xgboost2(implement and tune xgboost)
ARIMA1(overview of ARIMA)
ARIMA2(implemnt and tune ARIMA)
competition1[["`determine whether stores be
modeled separately or together`"]]

competition2[[compare ARIMA and xgboost]]

report1(("`**collect documents** of 
results, description and etc.`"))

report2(("`reorganize docs into **atomic 
cards** as resources of report`"))

report3((complete report))

start --> report1
start --> xgboost1
start --> ARIMA1
xgboost1 --> xgboost2
ARIMA1 --> ARIMA2
start --> competition1
competition1 --> competition2
xgboost2-->competition2
ARIMA2-->competition2
competition2 --> report1
report1 --> report2
report2 --> report3
```
