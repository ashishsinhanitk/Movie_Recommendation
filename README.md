# MOVIE RECOMMENDATION SYSTEM


![movie](https://miro.medium.com/max/1132/1*N0-ikjPv4RUVvS-6KCgLPg.jpeg)

There are 3 ways to implement a Movie Recommendation System

* ### Content Based <br />
* ### Collabrative filtering based <br />
* ### Hybrid <br /> <br />
**************** FLOW CHART ********************<br /><br />
1. I did this project by Content Based technique.<br />
2. After importing libraries and data.I merged data of both csv file into one, <br />
3. Then i performed data cleaning (removing blank space &duplication).<br />
4. After that i removed unwanted columns which was of no use .<br />
5. Then Tags for each column of each movie was created and finally each column tag of one movie is added to produce one overall tags.<br />
6. New data base is craeted which contains id,Title of movies and tags only.<br />
7. The tags were processed by removing blank space,doing morphological affixes and changing the cases of words into lower.<br />
8. Finally each tags of movie was vectorized and the Recommendation was given based on least angle between movies.
