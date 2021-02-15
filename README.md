# geospatial-data-project
"""
My aim in this project is to figure out the best location for an office of tech and design, composed by a solid teamspirit which will be enhanced with the different venue possibilities there will be around the location. 

Firstly I will extract from a dataset through Mongodb, a collection with companies founded after the year 2000. In fact, companies with said conditions are mainly located in California. Limiting my $near scope (as I want the office to be near others) I keep 4 San Franciscean firms. 

Secondly I do API calls to Foursquare to find how many karaoke, starbucks, nurseries and Rock Climbing spots there are around these four offices. I then make a decision in function of the equilibrium of this data.  

"""
