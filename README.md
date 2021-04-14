<img src="https://bit.ly/2VnXWr2" alt="Ironhack Logo" width="100"/>

# Title of My Project
*Weather and and music mood*

*data-squad-152-par, Ironhack-Paris 10/04/2021*

## Content
- [project-description](#project-description)
- [hypotheses-/-questions](#hypotheses-/-questions)
- [Dataset](#dataset)
- [Workflow](#workflow)
- [Organization](#organization)
- [Links](#links)

<a name="project-description"></a>

## Project Description
Write a short description of your project: 3-5 sentences about what your project is about, why you chose this topic (if relevant).

Several researches have proved that weather can have an impact on people mood, we could even talk about :Seasonal Affective Discorder (DAS). 
Based on this fact, we were wondering if people listen to happy or sad songs depending on the weather.
Do weather has an impact on the kind of music we listen to ?

<a name="hypotheses-/-questions"></a>

## Hypotheses / Questions
What are the questions you would like to build your dataset to answer?

Do people listen to calm and sad music when the weather is bad ?
Does the weather has an impact on people music taste ?

<a name="dataset"></a>

## Dataset
What are your data sources? How did you access these sources? How did you transform or merge them into one cohesive and novel dataset? Provide links to the data if available.
1/ Weather for the last year in France from <a href="https://opendata.reseaux-energies.fr/explore/dataset/temperature-quotidienne-departementale/information/?disjunctive.departement&sort=-date_obs">Reseaux Energie Open Data</a> 
2/ <a href="http://www.chartsinfrance.net/charts/200%s/singles.php">Top 50 tracks</a> in France from Charts in France
3/ The audio features for all tracks with Spotify API (search  and audio features)

[Dataset]() 

<a name="workflow"></a>

## Workflow
Outline the workflow you used in your project. What were the steps you went through?
1st Step : Get the weather in a Data frame on a weekly basis
2nd step : Get all the top tracks in a Data Frame on a weekly basis, by ranks, artists and songs
3rd step : Get the Audio features (Valence) for all tracks
Next Step :
Find a correlation between the weather (temperature) and the valence for the top tracks

<a name="organization"></a>

## Organization
How did you organize yourself? Did you use any tools?
Scraping of Opendata and top charts
Spotify API to search and get audio features

<a name="links"></a>

## Links
Include the links to your repository, slides and trello. Feel free to include any other links associated to your project. 

[Repository](https://github.com/)  
[Slides](https://slides.com/)  
[Trello](https://trello.com/en)  
