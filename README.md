# POWER-GENERATION-DATA-ANALYSIS
India is the third-largest producer and second-largest consumer of electricity world wide, with an installed capacity of 403 GW as of June 2022. India is also ranked fourth in wind power, fifth in solar power and fourth in renewable power installed capacity, according to Economic Times. Electricity use and access are strongly correlated with economic development.

Content
There are two CSV files in this dataset. One has daily power generation of all states and union territories of India since 2013. The other has daily power generation from different sources like Hydro, Wind, Solar, Diesel, Naphtha, etc.

Daily_Power_Gen_States
Region: India is divided into five different regions.
States: All states and union territories.
Max Demand Met during the Day: Maximum demand met during the day in Mega Watts. 1 MW = 1 Million watts.
Shortage during Maximum Demand: Shortage during maximum demand In Mega Watts.
Energy Met (MU): Total power generated on that day in Million Units. 1 Unit = 1 Kilo Watt Hour.
*Energy Shortage (MU): Energy shortage in Mega Units.
Daily_Power_Gen_Source
Source: Hydro, Coal, lignite, Nuclear, RES(Renewables: wind, solar, biomass..)
NR: Northern Region
SR: Southern Region
ER: Eastern Region
WR: Western Region
NER: North Eastern Region.
All India: Total power generation from all regions for the particular source.
date: date

Acknowledgements
Data has been extracted from https://posoco.in/daily-reports. Data was in the form of PDFs. More than 3600 PDFs were downloaded using BeautifulSoup and data from each PDF were extracted using Camelot and PyPDF2 libraries.

Inspiration
Learn about different sources of energy, their share, the growth of renewable energy sources, future projection, etc.
