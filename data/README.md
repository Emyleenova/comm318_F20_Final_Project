## Data files for COMM318 _Stories from data_ Final Project



#### This folder contains all the data files used in my analysis, organized into 2 folders: data_raw and data_clean. data_raw includes all unedited raw data from the source; data_clean includes subsetted, cleaned, organized data   
 #### Included in data_raw 
* covid_policy_bystate: state by state historica policies data
* State_Drug_Utilization_Data_2019: Medicaid claims data for 2019
* State_Drug_Utilization_Data_2020: Medicaid claims data for 2020
* unemployment_rates_2020: Contains month by month, state by state unemployment rates for 2020, cleans raw data uploaded from [Bureau of Labor Statistics](https://www.bls.gov/web/laus/ststdsadata.txt)unemployment rate data from BLS 
* United_States_COIVD_19_Cases_and_Deaths_by_State_over_Time: uploaded from CDC COVID-19 tracking site 
*  us_covid19_data: daily case data from CDC downloaded for initial project exploration; has fixed dates from download 
*  us_covid2020: daily case tracking data from CDC; later download date to include cases through May 2020 
* us_overdose_data: fatal drug overdose data from 2015-May 2020 from CDC; second download to get updated data through May 
* us_overdose_data_OG: drug overdose data from CDC downloaded for initial data exploration; tracks caes from 2015-February 2020 
* Copy of ststdsadata copy: unemployment data from Bureau of Labor Statistics for Jan-Sept 2020 

 
 
 
 #### Included in data_clean
* change_OD_2019_to_2020: year over year comparison of overdose rates in 2019 and 2020
* covid_clean_dates: COVID case data, formatted to datetime
* covid_data_clean: reorganized COVID case data 
* covid_policy_dictionary: DF with column heading definitions for state policy data 
* economic_factors: subsetted covid state policies - includes only economic policies 
* isolation_factors:subsetted covid state policies - includes only stay at home order/business closure policies  
* od_data_clean: us_overdose_data reformatted and cleaned for analysis, subsetted to 2020 data 
* od_data_longterm: us_overdose_data reformated same as above, but for 2015-2020
* od_date_clean: same as us_data_clean but without indexby dates 
 