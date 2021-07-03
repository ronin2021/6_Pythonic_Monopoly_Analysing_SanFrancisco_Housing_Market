# 6_Pythonic_Monopoly_Analysing_SanFrancisco_Housing_Market
-	Indrajith Senevirathne
# Analysis and Visualization of the San Francisco Housing Market using PyViz

## Outline
Using inputs from two .csv files providing year, neighborhood, corresponding latitude, longitude, sale price per square foot, number of housing units, and the gross rent, the code performs analysis and depicts the San Francisco housing market using Python and PyViz. A .env file is required with API key and for Mapbox API where the overlay map extraction is sourced from.   

#### Part 1. San Francisco Rental and Housing Market Analysis
1. Using a provided .csv file “sfo_neighborhoods_census_data.csv”, the year, neighborhood, sale price per square foot, number of housing units, and the gross rent were fed into a data frame via ETL.
2. Using a provided .csv file “neighborhoods_coordinates.csv”, neighborhood, corresponding latitude and longitude were fed into a data frame via ETL.  
3. Data frames were used to perform following analysis with graphical output: Average Annual Housing Unit Occupation, Yearly Variation of the Average Rent, Yearly Variation of the Average Sale Price/Sqr Foot, Yearly Sale Price/Sqr Foot Variation for Each Neighborhood, Yearly Gross Rent Variation for each Neighborhood, Yearly Variation of the Average Sale Price/Sqr Foot, Yearly Sale Price/Sqr Foot Variation for Each Neighborhood, Yearly Gross Rent Variation for each Neighborhood, Top Ten Most Expensive Neighborhoods by Price Per Square Foot, Annual Variation of Sales Price/Square Foot vs. Rent for Each Neighborhood, Annual Variation of Sales Price/Square Foot vs. Rent for top 10 Neighborhoods, Sale Price/Square Foot & Rent, and Averaged over All the Years - Top 10 Neighborhoods. 
4. Last two visualizations are map-overlays rendered via latitude and longitude data from the .csv file together with Mapbox API.  These are:  The Top 10 Most Expensive Neighborhoods and All San Francisco Neighborhoods. 
5. Data corresponding to the graph: Average Annual Housing Unit Occupation was given out and saved in the Data folder as a .cvs file.

#### Part 2. Dashboard		
1. Initial steps for the part is similar to part 1.
2. Using a provided .csv file “sfo_neighborhoods_census_data.csv”, the year, neighborhood, sale price per square foot, number of housing units, and the gross rent were fed into a data frame via ETL.
3. Using a provided .csv file “neighborhoods_coordinates.csv”, neighborhood, corresponding latitude and longitude were fed into a data frame via ETL.  
4. To improve performance all the data frames used by multiple graphs were initialized once at the global level.  These were then called by appropriate functions as needed.
5. Each graph was recreated using the global data frames or local data frames and each graph corresponds to the same graphs in the part 1.  
6. Graphs were loaded into panels in column form and tagged with tabs to complete the dashboard implementation of the visualizations of the analysis.

### Inputs
Data were extracted from the two .cvs files within the Data folder residing with the two files. 

### Outputs
Outputs are presented as graphs/charts. In the second part these were displayed on panels on a tabs separated dashboard. 

### Remarks
None.
