<img src="https://bit.ly/2VnXWr2" alt="Ironhack Logo" width="100"/>

# Weather and and music mood

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

Several researches have proved that weather can have an impact on people mood, we could even talk about :Seasonal Affective Discorder (DAS). 
Based on this fact, we were wondering if people listen to happy or sad songs depending on the weather.
Do weather has an impact on the kind of music we listen to ?

<a name="hypotheses-/-questions"></a>

## Hypotheses / Questions

Do people listen to calm and sad music when the weather is bad ?
Does the weather has an impact on people music taste ?

<a name="dataset"></a>

## Dataset

1/ Weather for the last year in France from <a href="https://opendata.reseaux-energies.fr/explore/dataset/temperature-quotidienne-departementale/information/?disjunctive.departement&sort=-date_obs">Reseaux Energie Open Data</a> 
2/ <a href="http://www.chartsinfrance.net/charts/200%s/singles.php">Top 50 tracks</a> in France from Charts in France
3/ The audio features for all tracks with Spotify API (search  and audio features)

[Dataset]() 

<a name="workflow"></a>

## Workflow

1st Step : Get the weather in a Data frame on a weekly basis
2nd step : Get all the top tracks in a Data Frame on a weekly basis, by ranks, artists and songs
3rd step : Get the Audio features (Valence) for all tracks
Next Step :
Find a correlation between the weather (temperature) and the valence for the top tracks

<a name="organization"></a>

## Organization

Scraping of Opendata and top charts
Spotify API to search and get audio features

<a name="links"></a>

## Links

[Repository](https://github.com/MaxCrmr/Ironhack-project-m1#title-of-my-project)  
[Slides](https://docs.google.com/presentation/d/1nBfti7rsO8jOotQtrRp4gAmHXGDKMjPwDvTTG1FHg24/edit?usp=sharing)  
[Trello](https://trello.com/b/TtHXTSwF/final-project-module-1-ironhack)  
