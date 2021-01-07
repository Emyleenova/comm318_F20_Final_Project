## Data analysis notebooks for COMM318 _Stories from data_ Final Project


* This folder contains the notebooks in which I ogranized and analyzed my data, which are descried below. The notebooks dedicated to cleaning data are subsetted in the folder 'cleanup.'

#### Included in Cleanup Folder
* covid_data_cleanup: Cleaned and subsetted raw data from [CDC.gov](https://data.cdc.gov/Case-Surveillance/United-States-COVID-19-Cases-and-Deaths-by-State-o/9mfq-cb36); reorganized daily reports to monthly data aggregates. 
* covid_state_policy_cleanup: Subsets and organizes data from [Boston University School of Public Health](https://github.com/USCOVIDpolicy/COVID-19-US-State-Policy-Database) described below: *"The COVID-19 US State Policy Database tracks the dates when each US state implemented new social safety net, economic, and physical distancing policies in response to the COVID-19 pandemic, combined with data on existing health and social policies and information on state characteristics. This database is developed and maintained by researchers at the Boston University School of Public Health, and is updated at least biweekly."

* employment_data_2020: Contains month by month, state by state unemployment rates for 2020, cleans raw data uploaded from [Bureau of Labor Statistics](https://www.bls.gov/web/laus/ststdsadata.txt)

* OD_Data_Cleanup: Cleaned and reorganized raw data from [CDC Vital Statistics Rapid Release](https://www.cdc.gov/nchs/nvss/vsrr/drug-overdose-data.htm) 

### Analysis Notebooks

* covid_data_analysis: Compared COVID-19 cases and deaths by state over the course of 2020 

* factors_analysis_economic: In this notebook, I analyze the relationship between states' respective overdose rates and their economic state in the pandemic, including unemployent rates, economic/social safety nets, and minimum wage. This notebook brings together several dateframes 

* factors_analysis_isolation: In this notebook, I analyze the relationship between states' overdose rates and the implementation of different COVID policies

* factors_analysis_healthcare: In this notebook, I briefly look at the relationship between states' healthcare policies and overdose rates. Ended up not including in final analysis. 

* initial_data_exploration:Breifly explores COVID-19 case and drug overdose fatality data, respectively, from the CDC to get a sense of the dataframes and begin to outline my research question. 


* naloxone_distribution_2019: Uses [Medicaid claims data](https://healthdata.gov/dataset/state-drug-utilization-data-2019) to estimate the number of doses of Naloxone, an overdose reversal drug, in 2019. This analysis should establish a baseline to determine if Naloxone distribution changed in 2020. Ended up not including in final analysis.

* OD_Data_Analysis: Initial analysis of changes in overdose rates during COVID and compared to baseline average over the previous 4 year period.

