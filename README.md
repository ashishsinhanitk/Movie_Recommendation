MOVIE RECOMMENDATION SYSTEM

There are 3 ways to implement a Movie Recommendation System

Content Based 
Collabrative filtering based
Hybrid 
**************** FLOW CHART ********************
I did this project by Content Based technique.
After importing libraries and data.I merged data of both csv file into one, 
Then i performed data cleaning (removing blank space &duplication).
After that i removed unwanted columns which was of no use .
Then Tags for each column of each movie was created and finally each column tag of one movie is added to produce one overall tags.
New data base is craeted which contains id,Title of movies and tags only.
The tags were processed by removing blank space,doing morphological affixes and changing the cases of words into lower.
Finally each tags of movie was vectorized and the Recommendation was given based on least angle between movies.
