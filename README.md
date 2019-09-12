# Austin City Crime and Property Analysis (2015-2018)

## Our Team:
* Ahmar Jamal (Population Analysis)
* Bhavini Vyas (Crime Analysis)
* Mark Findley (Property price Analysis)

### Project Description:
Austin crime relationship to home prices by zipcodes 2015-2018 along with seperate analysis of property price, population and crime.

### Hypothesis:
##### * H-Null: There is no relationship between crime and housing prices. If crime increases within zipcode, housing price doesn't decrease in that specific zipcode.
##### * H-Alt: An increase in crimes, over a period, will negatively impact home prices in an Austin zip code.  Conversely, a decrease in crime, over a period, will positively impact home prices in an Austin zip code.

### Research Questions to Answer:
1. Does housing price impact by the raise of crime in Austin? 
2. Which zipcode having more crime and which one having less?
3. Which are the zipcodes where crime decreases over the period of time and visa versa.
4. How are violent and property crime changing over the period of four year 2015 to 2018?
5. Which month having more crime and which month has less crime?
6. Which zipcode has highest %change increase in median home price?

### Data Sources
* US Cencus Data (Pupulation by zipcode)
* MLS listing data (zipcode, listing date, listing price)
* austintexas.gov (zipcode, crime type, occurance date)

### Breakdown of Tasks

1. Get Datasets for Austin Crime, population and housing price.
2. Clean the datasets. Keep only data between year 2015 to 2018.
3. Breakdown & Analyze Data Sets.
4. Property Analysis
    * Plot the map showing %change increase in median home price?
5. Populatin Anlysis
    * Plot the map showing change in population from 2015 to 2018 by zipcode.
6. Crime Analysis
* Get total crime (2015-2018) per 1000 population by zipcode.
    * Plot map showingList zipcodes with 5 highest and 5 lowest crime.
* Get the %change in crime from year 2015 to 2018.
    * Plot map showing the percentage change in crime (from 2015 to 2018) for every zipcode.
    * Plot map showing crime analysis by zipcode on heatmap with symbol marker.
* Seperate the dataset based on violent and property crime.
* Get the percentage change of violent crime year by year.
    * Plot the map showing how violent and property crime changes year by year over the period of four year.
    * Plot the map showing violent and property crime by month.
    * Plot the map showing crime by day.
7. Crime Vs Property Price Analysis
    * Plot the map showing the relation between %change in crime vs %change in property price.
8. Find if there is any corelation between %change in crime Vs % change in property price.


### Tools & Techniques:
1. Pandas
2. Matplotlib, Google Map API for Visualization
3. Python with Json for cencus and austintexas.gov API

### Our Findings
* Since the p-value is greater than .05, it supports the null hypothesis and rejects our hypothesis that there is a correlation between crime and property value in Austin zipcodes.
* Currently, it does not appear that crime data has a significant influence on home prices in Austin.
* Other factors such as neighborhood location, schools, walkability, neighborhood character, property taxes and long-term value may be more important.
* Overall, Austin is not a particularly violent city.  This study might lend itself better to cities where violent crime is a major problem like Chicago.



* Zipcode with five highest and five lowest number of crime per 1000 population over four years 2015 to 2018.

| ZipCode | No Of Crime per 1000 population |
| ------- | ----------- |
| 78728 | 2 |
| 78730 | 25 |
| 78725 | 26 |
| 78739 | 28 |
| 78717 | 43 |
| 78723 | 241 |
| 78702 | 289 |
| 78742 | 298 |
| 78719 | 373 |
| 78701 | 1072 |

* Zipcode with 5 highest and 5 lowest % change in crime over four years 2015 to 2018.

| ZipCode | %Change in Crime (per 1000 Population) |
| ------- | ----------- |  
| 78739 | -42.22 |
| 78719 | -32.82 |
| 78747 | -31.60 |
| 78705 | -29.60 |
| 78753 | -24.59 |
| 78727 | 17.17 |
| 78729 | 19.21 |
| 78717 | 29.36 |
| 78730 | 62.77 |
| 78742 | 111.69 |

* %Change in Violent Crime is getting reduced while %Change in Property Crime is getting increased over the four year from 2015 to 2018.
* From 2017 to 2018, Violent crime has been decreased by 5%, while Property crime has been increased by 7%.
* February is the month with lowest crimes. October is the month with comparatively high crime based on four year total crime.
* %change in median housing price for all zipcode increases over the period of four year 2015-2018.


