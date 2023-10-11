# CodingAssignment1

## Project goal
Scrape, clean, analyze and visualize data from Wikipedia page "List of United States Cities by Population".

## API Documentation
No API was used for the collection, analysis or visualization of this data.
Python libraries were used, specifically Pandas, BeautifulSoup, Scipy/Scipy.stats and Pyplot

## License Information
This data is under the MIT license, which you can find in the LICENSE.txt file. The source data for this data set is licensed under the Creative Commons deed. The full text can be found here: https://en.wikipedia.org/wiki/Wikipedia:Text_of_the_Creative_Commons_Attribution-ShareAlike_4.0_International_License

## Data Set Information
The data set contains various data types and each has their own attributes found below:
*  Rank (integer): The city rank by population as of July 1, 2022, as estimated by the United States Census Bureau
*  City (string): The name of the city
*  State (string): The name of the state containing the city
*  2022 Estimate (float): The city population as of July 1, 2022, as estimated by the United States Census Bureau
*  2020 Census (float): The city population as of April 1, 2020, as enumerated by the 2020 United States census
*  Percent Change (float): The city percent population change from April 1, 2020, to July 1, 2022
*  2020 Land Area in Sq Mi (float): The city's recorded land area as of 2020 in square miles
*  2020 Land Area in Sq Km (float): The city's recorded land area as of 2020 in square kilometers
*  2020 Population Density per Sq Mi (float): The city population density per square mile as of 2020 (residents per unit of land area)
*  2020 Population Density per Sq Km (float): The city population density per square kilometer as of 2020 (residents per unit of land area)
*  Location (string): The city latitude and longitude coordinates

It is important to note that the data source for this data set and analysis uses US Census Bureau numbers and estimates. The percent change is calculated from 2022 estimated data by the US Census Bureau, not enumerated census data, thus they may be inaccurate. Additionally, census data may have some inherent biases and inaccuracies, due to phenomenons like non-response bias or overcounting/undercounting of certain populations. 

