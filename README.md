# nosql-challenge

# Setup the MongoDB
* Import the data from a json file to Mongo DB through bash terminal.
* Create a instance of the database in jupiter notebook by using pymongo.
* Update the data base by inserting a new restaurant callsed "Penang Flavours".
* Update its business type ID.
* Update the data base by deleting all the documents from Local Authority of "Dover".
* Update the latitude and longitude fields from string data type to float.
* Update the RatingValue field by changing all non-numeric values to none and then convert all the numeric value data type from string to Int.

# Analysis of the data
* Find all the restaurants that have a hygiene score of 20 (total: 41).
* Save these restaurants in a pandas dataframe.
* Find all the restaurants in the local authority of London by using "regex" method, and restrict the RatingValue to be greater or equal to 4.
* Total of 33 of them are saved in a pandas dataframe.
* Find the top 5 establishments by hygiene score, that have a RatingValue of 5 near (0.01 degree) the "Penang Flavours".
* All the results are saved in a pandas dataframe.
* Find all the establishments that have a hygiene score of 0, and group them by their local authority, and sort them by their count.
* All the results are saved in a pandas dataframe, and top 10 of them are displayed for reference.