# Project 1 Proposal

Team members: Fanny, Tania & Merve

## Dataset

We are using the Major Crime Indicators dataset published by the Toronto Police Services in the Toronto Open Data website.

**Link:** https://open.toronto.ca/dataset/major-crime-indicators/

## Goal

Analyze major crime indicators in the city of Toronto, identifying trends by type of offences and by neighbourhoods, as well as comparing the years 2018, 2020, and 2022 to identify changing crime trends pre-, during and post-COVID.

## Questions

Research questions:

1. For each year: On average, how long after the offence date was it reported (offence date vs reporting date)?
2. In each year: What are the peak times for crime occurences? Does it change according to season? Is there a concentration of crime around a specific period of the year?
3. For each year: Can we identify trends or patterns in specific neighbourhoods (e.g. certain neighbourhoods seeing an increase or decrease in crime)? Is there a correlation between the type of offence and the location (e.g. are burglaries more common in residential areas)?
4. For each year: Is there a correlation between certain types of offences (e.g. do areas with high drug-related crimes also see increased violent crimes)?
5. Year to year, has there been an overall increase or reduction in crime? What has been the change in crime per neighbourhood? Has a certain type of offence seen a significant decrease or increase?

## Audience

Our target audience is the general public, mainly the people living in the City of Toronto that are interested in the crime patterns of their city.

## Q1: For each year: On average, how long after the offence date was it reported (offence date vs reporting date)?

Columns: OCC_DATE, OCC_HOUR, REPORT_DATE, REPORT_HOUR


## Q2: In each year: What are the peak times for crime occurences? Does it change according to season? Is there a concentration of crime around a specific period of the year? 

Columns: OCC_DATE, OCC_YEAR, OCC_MONTH, OCC_DAY, OCC_DOY, OCC_DOW, OCC_HOUR

## Q3: For each year: Can we identify trends or patterns in specific neighbourhoods (e.g. certain neighbourhoods seeing an increase or decrease in crime)? Is there a correlation between the type of offence and the location (e.g. are burglaries more common in residential areas)?

Columns: all except: _id, UCR_CODE, UCR_EXT, HOOD_140, NEIGHBOURHOOD_140

## Q4: For each year: Is there a correlation between certain types of offences (e.g. do areas with high drug-related crimes also see increased violent crimes)?

Columns: HOOD_158, OCC_YEAR, LOCATION_TYPE, PREMISES_TYPE, OFFENCE, MCI_CATEGORY

## Q5: Year to year, has there been an overall increase or reduction in crime? What has been the change in crime per neighbourhood? Has a certain type of offence seen a significant decrease or increase?

Columns: HOOD_158, OCC_YEAR, LOCATION_TYPE, PREMISES_TYPE, OFFENCE, MCI_CATEGORY
