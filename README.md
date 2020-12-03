# geog5092-lab1
Lab 1 for GEOG 5092, Fall 2020

Completed by Mallory Prentiss

Goal: Learn to work with multiple data files in an automated framework. Gain familiarity with the Pandas and Geopandas module to conduct vector geoprocessing and relational joins.

Task: You will process the SSURGO data by joining each of the tables to the corresponding feature class and then you will merge the 9 feature classes. Next, you will intersect the SSURGO data with the watershed boundaries and finally count the number of map unit polygons within each watershed.

Part I:
1) Join each of the tables to the corresponding feature class. Find a common field to join on.
2) Add a new field named mapunit to each joined feature class and calculate the values for all features as the map unit ID of the feature class. The map unit ID is the suffix of the layer name (e.g., co641).
3) Merge the 9 feature classes into a new feature class.
4) Intersect the merged feature class with the watershed boundaries.

Part II:
Find the number of features in the resulting intersected feature class that correspond to each watershed. Report these two numbers in a print statement at the end of your script. Hint: Look at the groupby function from pandas, which column should you group by?
