# Movies-ETL

This project uses large files of raw movie data, cleans the files, and stores them for use in future projects. The client wanted to use the cleaned data for hackathons. 

## Summary ##

The first stage of this project is housed in the ETL_functions test file. This creates the ETL framework to read in the raw data from three sources (two CSVs and one JSON). These functions will be used on later steps.

The second stage of this project is housed in the ETL_clean_wiki_movies file. This section created a function that cleans raw data pulled from Wikipedia Movies (a JSON) detailing charactertistics about the film, its creation, and its reception. Since some data was incomplete or not relevant, that data is filtered out. The completed DataFrame contains only clean Wiki movies data.

The third stage of this project is house in the clean_kaggle_data file. The penultimate section of this project added to the function created in the second phase to include code that would clean data pulled from Kaggle (ratings and movie data in two seperate CSV files). Once complete, three DataFrames are created to organize each type of data.
