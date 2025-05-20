# Racial Bias in Criminal Bike Summons 
### Paige Oamek 
#### *CUNY School of Journalism* // Advanced Data Reporting

This data journalism project investigates how Class C criminal summons for bicycling infractions were given to cyclists of different races. Historically these criminal summons for bicycling infractions made up only a fraction of violations cyclists could receive. However, since this project was originally conceived the NYPD has put forth a new effort to categorize all infractions, like running a red light or failure to yield, as criminal "pink ticket" summons. 

As there is not currently open data to track the criminal summons cyclists are receiving, it is integral to interrogate the data we do have. 

## Data Sources

I accessed annual Class C criminal summons from [NYPD Criminal Court Summons Incident Level Data (Year To Date)](https://data.cityofnewyork.us/Public-Safety/NYPD-Criminal-Court-Summons-Incident-Level-Data-Ye/mv4k-y93f/about_data), updated quarterly, and [NYPD Criminal Court Summons (Historic)](https://data.cityofnewyork.us/Public-Safety/NYPD-Criminal-Court-Summons-Historic-/sv2w-rv3k/about_data), updated annually. 

## Methodology 

While examining the historic data, which records every criminal summons issued in NYC going back to 2006, I noticed that the NYPD started recording race as a category around summer 2016. This was around the same time as certain reforms around racialized policing took effect. (Civil summons do not record race data). Previously race was left empty or marked as unknown. Since 2016 is when the NYPD began recording race, the dataset I created begins at 01/01/2016. 

I then sorted by SUMMONS_CATEGORY_TYPE as "bike" to query the data for all bike related criminal summons from 2016 to as recent as possible. One spreadsheet includes the historic data from 2016-2024. Another sheet includes the updated data from the first quarter of 2025 which was uploaded by the NYPD April 15th. 

To recap, I ignored data pre-2016 as it did not have race as a category and I only looked at criminal (Class C) summons related to the category bike. 

## What I found

Though our data is not up to date with the current NYPD policy of giving criminal summons to all cyclist infractions--it can tell us a bit about what giving our "pink tickets" to cyclists has looked like recently. 

Over the past decade, if cyclists received a criminal summons it was likely for biking on the sidewalk or for a "commercial" infraction for failing to carry identification that proves you're a commercial bicyclist. 

Throughout the years, Black cyclists were more likely to receive criminal summons for biking infractions than people of other races---sometimes at incredibly higher levels. From 2016 - 2024 Black (including Black Hispanic) bikers are **about 6 times more likely** to receive a summons than White (non-Hispanic) bikers.

Though the findings of perceived racial bias by the NYPD are striking, one limitation of my data is that we don't have a great understanding of *who* actually rides on New York's streets to begin with. Could it be possible that Black people make up more than 40 percent of bike riders? Not likely. According to a limited [2022 Citywide Mobility Survey](https://www.nyc.gov/html/dot/html/about/citywide-mobility-survey.shtml) white non-Latino New Yorkers, 51% bike at least on occasion, and 20% bike weekly whereas among New Yorkers of color, 37% bike at least on occasion, and 14% bike weekly, the number for Black New Yorkers are even lower. 
