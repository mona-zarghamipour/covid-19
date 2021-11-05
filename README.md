# covid-19
covid-19-vaccinations-visualization-prediction-Germany and Switzerland

Hello :) 

This is my first experience training a model. I would appreciate any feedback!

the data set https://www.kaggle.com/gpreda/covid-world-vaccination-progress
'2020-12-27', '2021-07-15'
Content

The data (country vaccinations) contains the following information:

•	Country- this is the country for which the vaccination information is provided;
•	Country ISO Code - ISO code for the country;
•	Date - date for the data entry; for some of the dates we have only the daily vaccinations, for others, only the (cumulative) total;
•	Total number of vaccinations - this is the absolute number of total immunizations in the country;
•	Total number of people vaccinated - a person, depending on the immunization scheme, will receive one or more (typically 2) vaccines; at a certain moment, the number of vaccination might be larger than the number of people;
•	Total number of people fully vaccinated - this is the number of people that received the entire set of immunization according to the immunization scheme (typically 2); at a certain moment in time, there might be a certain number of people that received one vaccine and another number (smaller) of people that received all vaccines in the scheme;
•	Daily vaccinations (raw) - for a certain data entry, the number of vaccination for that date/country;
•	Daily vaccinations - for a certain data entry, the number of vaccination for that date/country;
•	Total vaccinations per hundred - ratio (in percent) between vaccination number and total population up to the date in the country;
•	Total number of people vaccinated per hundred - ratio (in percent) between population immunized and total population up to the date in the country;
•	Total number of people fully vaccinated per hundred - ratio (in percent) between population fully immunized and total population up to the date in the country;
•	Number of vaccinations per day - number of daily vaccination for that day and country;
•	Daily vaccinations per million - ratio (in ppm) between vaccination number and total population for the current date in the country;
•	Vaccines used in the country - total number of vaccines used in the country (up to date);
•	Source name - source of the information (national authority, international organization, local organization etc.);
•	Source website - website of the source of information;
There is a second file added recently (country vaccinations by manufacturer), with the following columns:
•	Location - country;
•	Date - date;
•	Vaccine - vaccine type;
•	Total number of vaccinations - total number of vaccinations / current time and vaccine type.
