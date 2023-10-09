# Project 1

**Team members:** Fanny Sigouin, Tania Barrera & Merve Celme

This repo contains our work for the first project of the UofT SCS edX Data Bootcamp.

## Dataset

We are using the Major Crime Indicators dataset published by the Toronto Police Services in the Toronto Open Data website.

**Link:** https://open.toronto.ca/dataset/major-crime-indicators/

From the dataset page: 

> This data is provided at the offence and/or victim level, therefore one occurrence number may have several rows of data associated to the various MCIs used to categorize the occurrence.

Therefore, we decided to consider rows that are identical (i.e. same event ID and Offence) as a single data point, keeping those with the same event ID but different Offence name as separate.

The process of getting and cleaning the data is detailed in this Jupyter Notebook: [get_and_clean_data.ipynb](get_and_clean_data.ipynb)

## Goal

Analyze major crime indicators in the city of Toronto, identifying trends by type of offences and by neighbourhoods, as well as comparing years from 2014 to 2022 to identify changing crime trends.

## Audience

Our target audience is the general public, mainly the people living in the City of Toronto that are interested in the crime patterns of their city.

## Questions

1. Year to year, has there been an overall increase or reduction in crime?  Has a certain type of offence seen a significant decrease or increase?
2. What are the peak times for crime occurences? Does it change according to season? Is there a concentration of crime around a specific period of the year?
3. On average, how long after the offence date was it reported (offence date vs reporting date)?
4. Can we identify trends or patterns in specific neighbourhoods (e.g. certain neighbourhoods seeing an increase or decrease in crime)? Is there a correlation between the type of offence and the location (e.g. are burglaries more common in residential areas)?
5.  Is there a correlation between certain types of offences (e.g. do areas with high drug-related crimes also see increased violent crimes)?

### Q1: Year to year, has there been an overall increase or reduction in crime?  Has a certain type of offence seen a significant decrease or increase?



### Q2: What are the peak times for crime occurences? Does it change according to season? Is there a concentration of crime around a specific period of the year? 



### Q3: On average, how long after the offence date was it reported (offence date vs reporting date)?




### Q4: Can we identify trends or patterns in specific neighbourhoods (e.g. certain neighbourhoods seeing an increase or decrease in crime)? Is there a correlation between the type of offence and the location (e.g. are burglaries more common in residential areas)?



### Q5: Is there a correlation between certain types of offences (e.g. do areas with high drug-related crimes also see increased violent crimes)?
