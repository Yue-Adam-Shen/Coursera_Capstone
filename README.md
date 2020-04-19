The trend of moving around as a life style is emerging among the up-and-coming generation. Aged between 25 and 35 years old, singled or coupled, medium-high income in new-economy industries, those individuals believe in exploring and experiencing life in its full capacities where they live, and embracing the variety of natural and cultural surroundings that different locations in the world provide where they live and work. A business opportunity exists therefore for a platform to provide screening of locations and neighborhoods for those renters/relocators, each of whom come with a different set of priorities and preference.

to build a concept project that showcases the potential of the proposed platform, Four Square Location data will be used for the venues within the cities below:
1. San Francisco
2. Seattle
3. New York
4. Shanghai

Data on location and category of venues within each and every city above will be used for this project.

Exploratory data analyses were done to understand the richness of data from FourSquare regarding the culinary variety of food establishments in those four cities of interest. Initial exploration revealed that categoryId, more than any other parameters in FourSquare API, could pinpoint to establishments that represent food industry. Therefore a specific level of venue category (categoryID=4d4b7105d754a06374d81259, see https://developer.foursquare.com/docs/build-with-foursquare/categories/ for further references). After parsing out relevant data from categories, and standardizing the format across all four cities, I further summarized the number of establishments by city then by detailed category name, to give an overview of the variety of each city.

results showed that Shanghai among all four has the most categories of cuisine presented, but the lowest amount of total establishments. All four cities have coffee shop as their top category by number of establishments, and food court among the top 5 categories for all three cities in the US.

This analysis is a brief example of what is potential for location-base analyses using python and FourSquare API. More opportunities exist in the fine combing of rich data hosted on FourSquare that tells and categories the layout of different areas. One limitation noted in this analysis about using FourSquare API is that it presents a limit of data pull at once, and have different dictionary conventions for venues in different areas of the world. Further analyses building on the idea of mapping areas by its cultural and societal features, similar to the one done in this analysis, need crossing-checking and further refining of some of classification provided in FourSquare. 
 
