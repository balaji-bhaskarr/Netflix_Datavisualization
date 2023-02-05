# Netflix_Datavisualization

Netflix is an over-the-top (OTT) streaming service that offers a wide variety of TV shows, movies, documentaries, and original content.
It is one of the largest streaming platforms in the world.

I wanted to know more about the movies and TV shows that are available on Netflix. Due to this, I searched through the Kaggle datasets and came upon one created by Senapti Rajesh.
The majority of the information needed for data visualisation was present, including Show ID, type, title, nation, genre, ratings, etc.

For visualisation purposes, it was necessary to ignore several fields' null values.
Tableau, which is known for its sophisticated data visualisation capabilities, including interactive dashboards and maps, was my pick of the data visualisation platforms.
I chose this because of its ease of use and powerful data blending features. 

Final observation: 
1. The US has produced the most content for Netflix, followed by India. 
2. Movies account for 70% of total content, while TV shows account for 30%. 
3. Since 2014, Netflix has added an exponentially greater volume of new content. 
4. Nearly 35% of the content is rated TV-MA, while only three are rated NC-17. 
5. There are more than 300 documentaries and stand-up comedy shows. 

URL to the dataset: https://www.kaggle.com/datasets/senapatirajesh/netflix-tv-shows-and-movies?datasetId=2812514&sortBy=dateRun&tab=profile

Challenges using this dataset: 
* This dataset considers only data up to January 2021; thus, the amount of information added for 2021 appears to be minimal. A dataset with recent data will provide more insightful results. 
* Numerous values had to be disregarded since they were null. 
* Some values in the country column could not be read because they weren't consistent with the values used by Tableau maps.
