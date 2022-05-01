# Covid Mapping

For this project, I used data gathered by the New York Times to create two maps visualizing summary statistics from the Covid-19 pandemic: Case rate (cases/county population), and raw number of cases, mapped on the county level.

## Covid Cases Rates (cases/county population)
![map 1](/img/map1.png)

This maps primary function is to visualize the distribution of the highest and lowest case rates in counties across the United States.  It shows counties with relatively high case rates in darker shades of red, and those with relatively low case rates in a lighter shade of red.  This allows the user to quickly ascertain those counties that were more or less severely affected by Covid-19. 

The map also implements and interactive feature that allows the user to hover their cursor over any given county, and the name of the county, as well as the rate of Covid cases in that county.  This functionality is demonstrated using King county below. (in the full map, this information would be displayed in the top left corner)

![map 1](/img/map1_interactive.png)


## Covid Cases by County
![map 1](/img/map2.png)

This maps primary function is to visualize the raw number of cases by county across the United States.  It shows which counties had the largest raw number of Covid Cases, without making any adjustments for population.  It uses proportional symbols to represent the number of cases in a county, with a larger circle indicating more cases in that county.  You can see the interactive portion demonstrated in King county.  When the user clicks on King county (or any other) It will tell them the county name and number of cases in that county.

This project primarily uses mapbox for all mapping.  Data was obtained from [the New York Times](https://github.com/nytimes/covid-19-data/blob/43d32dde2f87bd4dafbb7d23f5d9e878124018b8/live/us-counties.csv).  Both maps were created with reference to lecture material and lab assignment spec provided by Professor Jacob Zhao for the Geography 458 course at the University of Washington.
