# carbon_accounting_conference

This script will help you to estimate the total CO2e emissions from you conference, from minimal data. 

It reads the excel file with a data example; which can be modified. Minimal data needed are: Location of conference, number of attendees per city, and the latitude/longitude for distance calculation

CO2e emissions are based on the following assumptions:

Attendees from > 700km will take the plane:

Domestic (between 700 and 1500km): 0.22928 kg CO2e/km; *

Short-haul (between 1500 and 8000km): 0.12786 kg CO2e/km; *

Long-haul (>8000km): 0.15282 kg CO2e/km; *


Attendees from <  700km will take the train, car/taxi, bus, or ferry

--> The estimated average of these modes of transport is 0.06 CO2e/km  & the distance is multplied by factor 1.3 



Hotel stays*

10.4 kg CO2e/room-night (UK, different for different countries!)


Conference center emissions**

estimate of 5.25tCO2e for 1000 people per day = 5.25kg / person / conference day


*based on UK Government Conversion Factors for greenhouse gas (GHG) reporting 2025
https://www.gov.uk/government/publications/greenhouse-gas-reporting-conversion-factors-2025 

**based on BNA 2025 numbers 

