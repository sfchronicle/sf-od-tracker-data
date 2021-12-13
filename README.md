# San Francisco Chronicle Overdose Tracker

Live project URL: https://www.sfchronicle.com/projects/2021/san-francisco-drug-overdoses-map/

This repository contains multiple datasets from varying sources relating to San Francisco’s drug overdose epidemic.

The Chronicle primarily relies on the San Francisco Office of the Chief Medical Examiner’s [monthly reports](https://sf.gov/resource/2020/ocme-accidental-overdose-reports) to track the monthly changes in the number of deaths and the share of those that involve fentanyl. Those reports are the most up-to-date and reliable source of information.

We also use the more detailed data on the circumstances of individual deaths, which we obtained through rolling public records requests, for analysis on the combinations of drugs contributing to the deaths and in other limited instances. Because it offers many more details, it takes the medical examiner’s office longer to verify the information and release it publicly. That means data about more recent deaths are not immediately available.

The California Department of Public Health Overdose Surveillance Dashboard provides the county-level death rates. The Chronicle includes crude death rates, which are death rates based on the entire population of a geography, as opposed to age-adjusted death rates, which are calculated based on a subset of a population, for consistency and accurate comparisons, based on data availability.

We compiled the death rates of some U.S. metro areas, which were selected based on population size, according to U.S. Census data, and data availability. See below for a list of files and more information about them.


**Data on San Francisco trends**

1. Circumstances of deaths that occurred between January 2020 and August 2021
File name: `sf_accidental_od_deaths_jan20_aug21_prelim_ocme.csv`
Source: San Francisco Office of the Chief Medical Examiner, obtained through public records requests
Update frequency: TBD

2. Accidental overdose deaths by month from January 2020 to October 2021
File name: `sf_od_deaths_monthly_2020_2021.csv`
Source: Compiled based on monthly reports from the San Francisco Office of the Chief Medical Examiner
Update frequency: Monthly

3. Cause of death variant (drug type) in deaths that occurred in 2020
File name: `sf_od_drug_type_2020.csv`
Source: Compiled based on individual death data from the San Francisco Office of the Chief Medical Examiner
Update frequency: Yearly

4. Race/ethnicity breakdown of accidental overdose deaths in 2020 and 2021
File name: `sf_od_race_2020_2021.csv`
Source: Compiled based on monthly reports from the San Francisco Office of the Chief Medical Examiner
Update frequency: Monthly

5. Street Overdose Response Team program data (Updated Dec. 13, 2021)
File name: `sf_od_sort_nov21.csv`
Source: San Francisco Department of Public Health
Update frequency: TBD

**Data on broader trends:**

1. Overdose death rates in California counties with 100,000+ population in 2020
File name: `ca_od_counties_100k.csv`
Source: California Department of Public Health Overdose Surveillance Dashboard/Centers for Disease Control and Prevention
Update frequency: Yearly
Note: These death rates are lower than the calculated rates in San Francisco-specific tables because of the differences in how the CDC defines overdose deaths.

2. Overdose death rates in the Bay Area’s nine counties from 2011 to 2020
File name: `bay_area_od_counties.csv`
Source: California Department of Public Health Overdose Surveillance Dashboard/Centers for Disease Control and Prevention
Update frequency: Yearly
Note: These death rates are lower than the calculated rates in San Francisco-specific tables because of the differences in how the CDC defines overdose deaths.

3. Overdose and fentanyl-involved death rates in selected U.S. metro areas in 2020
File name: `us_od_metro.csv`
Source: Medical examiner’s offices or health departments of applicable jurisdictions
Update frequency: TBD
