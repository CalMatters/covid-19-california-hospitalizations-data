# COVID-19 California Hospitalizations Data

CalMatters is compiling a dataset of California hospitalizations due to the COVID-19 pandemic. The data is based on daily updates from the [California Department of Public Health's dashboard](https://public.tableau.com/profile/ca.open.data#!/vizhome/COVID-19PublicDashboard/Covid-19Hospitals) showing hospitalizations. The dashboard does not show historic data.

CalMatters started compiling hospitalization data on March 31, 2020, when the dashboard went live. We carefully input the data by hand, but there's always a chance there is an input error. The state dashboard does not allow the user to download the data. So in the meantime, the dataset we are compiling is available for public, noncommercial use. If you use this dataset, please mention it was **compiled by CalMatters**. The dataset will be updated daily as new numbers are released. 

## About the Data

There are two files available in this dataset:

1. **ca_county_hospitalizations.csv**: Contains daily hospitalization numbers by county.
1. **ca_county_daily.csv**: Contains daily total hospitalization numbers and percentage of responding facilities.

The California Department of Public Health is the source of this dataset. When reporting hospitalization numbers, there are four categories:

1. **Positive Patients:** Total number of lab-tested positive COVID-19 patients (including ICU patients)
2. **Suspected Positive Patients:** Total number of patients that have symptoms consistent with COVID-19 with test results pending (including suspected ICU patients).
3. **Positive ICU:** Total number of lab-tested positive COVID-19 patients in intensive care. 
4. **Suspected Positive ICU:** Total number of intensive care patients that have symptoms consistent with COVID-19 with test results pending

The state data relies on local hospitals to disclose numbers. On any given day, the percentage of hospitals reporting daily hospitalization numbers varies. The state reports both the number of responding facilities and the number of licensed beds reflected in the data. With that in mind, there could likely be more patients than what is being reported on any given day. Also, the patient numbers are not cumulative and update day-to-day as the state releases updates. 

Another note: there have been days where the number of total patients reported by the state does not add up with the county-level sum of patients. We're trying to get answers on why the statewide number is higher at times. 

If you have any questions about this dataset, [feel free to contact us](mailto:john@calmatters.org).

*[CalMatters](https://calmatters.org) is a nonpartisan, nonprofit journalism venture committed to explaining how California’s state Capitol works and why it matters.* 
