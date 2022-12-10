# Goal

The goal of this project is determining the implications of temperature and whether it has affect on COVID-19 like it does with the common cold. There are numerous articles that state that the cold weather does not directly make a person sick, but can make a person more susceptible to getting the cold. We explore the validity of this statement through a test on Bergen county located in New Jersey. Through data cleaning, manipulation, and a hypothesis test we can deduce whether or not the temperature has the same effect on COVID-19. 

# Data Descriptions
**The RAW_us_confirmed_cases.csv** file from the Kaggle repository of John Hopkins University COVID-19 data. This data is updated daily. (https://www.kaggle.com/datasets/antgoldbloom/covid19-data-from-john-hopkins-university)

**mask-use-by-county.csv** is the CDC dataset of masking mandates by county. Note that the CDC stopped collecting this policy information in September 2021. (https://data.cdc.gov/Policy-Surveillance/U-S-State-and-Territorial-Public-Mask-Mandates-Fro/62d6-pm5i)

**new_jersey_covid_data.csv** is the New York Times mask compliance survey data. (https://github.com/nytimes/covid-19-data/tree/master/mask-use)

**flu-ili-byregion-fluseason.csv** is the dataset from the New Jersey set of illness data collectors. NJSHAD. (https://www-doh.state.nj.us/doh-shad/indicator/view/PneuFluDeath.Trend.html)

**temperature.csv** is a dataset of temperature for the state of New Jersey on average between 2019-2021 from the Rutgers monthly climate tables (https://climate.rutgers.edu/stateclim_v1/nclimdiv/).

# Procedures
First we clean the 3 datasets (Kaggle, CDC, and NYT) to decipher the county of Bergen, NJ. Once we do so, we manipulate the dataset to represent its confirmed cases, rates, and plot the identifying characteristics of the county.

Once we do that, we compare the data to the New Jersey state of FLU cases and the temperature during these seasons. By manipulating the dataframe, we can identify matching sets of values for the years of 2019-2021. 

After matching the two sets of data, we run a hypothesis test and give a comparing result found in the final_report.pdf document. 

# Final Report
The final report goes over the following sections: Introduction, Background, Methodology, findings, discussions/implications, limitations, conclusion, references, and data sources. 
