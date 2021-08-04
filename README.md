# R-shiny--Covid-Vaccination

# Background:

SARS-CoV2(COVID-19) crisis created a race to produce a vaccine in record time, and the number of people being
vaccinated in different countries depends on many factors. More than 2.88 billion vaccine doses have been administered
worldwide, equal to 38 doses for every 100 people. There is already a stark gap between vaccination programs in
different countries, with some yet to report a single dose.
Objective and Final Deliverables:
Through this project we aim to determine how COVID-19 vaccines are being distributed and used around the world and
what are the factors affecting the manufacturing and distribution of COVID-19 vaccines. We aim to create a dashboard
with options to modify search using tools and filters.
In this project we are going to take into consideration economic indicators like population density of the country, GDP of
different countries, international trade, age distribution, education, number of physicians per population etc.

# Data Collection:

The dataset for this project is found in Kaggle (https://www.kaggle.com/gpreda/covid-world- vaccination-progress)
which contains the following information.
• Country- this is the country for which the vaccination information is provided.
• Country ISO Code - ISO code for the country
• Date - date for the data entry; for some of the dates we have only the daily vaccinations, for others, only the
(cumulative) total
• Total number of vaccinations - this is the absolute number of total immunizations in the country
• Total number of people vaccinated - a person, depending on the immunization scheme, will receive one or more
(typically 2) vaccines; at a certain moment, the number of vaccinations might be larger than the number of
people.
• Total number of people fully vaccinated - this is the number of people that received the entire set of
immunization according to the immunization scheme (typically 2); at a certain moment in time, there might be a
certain number of people that received one vaccine and another number (smaller) of people that received all
vaccines in the scheme.
• Daily vaccinations (raw) - for a certain data entry, the number of vaccinations for that date/country
• Daily vaccinations - for a certain data entry, the number of vaccinations for that date/country
• Total vaccinations per hundred - ratio (in percent) between vaccination number and total population up to the
date in the country
• Total number of people vaccinated per hundred - ratio (in percent) between population immunized and total
population up to the date in the country.
• Total number of people fully vaccinated per hundred - ratio (in percent) between populatio n fully immunized
and total population up to the date in the country.
• Number of vaccinations per day - number of daily vaccinations for that day and country.
• Daily vaccinations per million - ratio (in ppm) between vaccination number and total population for the current
date in the country
• Vaccines used in the country - total number of vaccines used in the country (up to date);
• Source name - source of the information (national authority, international organization, local organization etc.)
• Source website - website of the source of information
• Location - country
• Date - date
• Vaccine - vaccine type
• Total number of vaccinations - total number of vaccinations / current time and vaccine type.


To enrich this information, we are going to include demographic information collected by the United Nations repository
https://www.kaggle.com/sudalairajkumar/undata-country-profiles/
Possible candidates for the first iteration of this project are the following columns:
• Population density (per km2,2017)
• Sex ratio (m per 100f,2017)
• GDP per capita (current US$)
• International trade: Balance (Million US$)
• Urban population (% of total population)
• Population age distribution (0-14/60+ years, %)
• Health: total expenditure (% of GDP)
• Health: physicians (per 1000 pop.)
• Education: Tertiary gross
Tools and Methods Used:
The main software used for this project are R and R shiny. All the web-based visualizations will be made using R Shiny.
We will first start by processing the data. This step will include analyzing, tidying and sorting the data. In this step we will
also use mathematical functions and operations to find the correlation between various attributes.
Next, we will use data analytics tools and a few machine learning algorithms to find insights and show the visualizations
creating a dashboard on Rshiny app. This dashboard will contain interactive widgets which will enable users to filter and
customize visualizations.
