### Examining the impact of actor/actress experience on movie genre:
Using the information about actor/actress experience, we see if there is a relationship with the genre of the movie. For example, do more experienced actors/actresses tend to star in certain genres more frequently?

### also
It could be a good idea to analyze the relationship between actor/actress experience and movie success, as well as other factors, for different time periods. Doing this could allow us to see if there are any trends or patterns that differ between the different eras. For example, we can compare the average experience of leading actors/actresses in movies released during the baby boomer era versus the millennial era and see if there are any differences.

It's important to keep in mind that making a distinction between different time periods could also introduce other variables that could influence the results of your analysis. For example, there may be differences in movie-making technology, audience preferences, or economic conditions that could affect the success of a movie and confound the relationship between actor/actress experience and movie success. We  need to consider these factors and try to control for them in your analysis as per what the assistant said.

# However we remain aware of the potential confounders
When analyzing the relationship between actor/actress experience and movie success for different time periods there are unobserved latent variables that might be implicitly affecting our results

  - Movie-making technology: The technology available for making movies can change over time, and this could potentially impact the success of a movie. For example, advances in special effects or cinematography could make a movie more visually appealing and impact its box office success.

  - Audience preferences: The preferences of moviegoers can also change over time. What may have been popular in one era may not be as popular in another. It's important to consider how audience preferences may have changed over the different time periods we are analyzing.

  - Economic conditions: Economic conditions can also impact the success of a movie. For example, during times of economic downturn, people may be less likely to go to the movies or may have less disposable income to spend on entertainment. It's important to consider how economic conditions may have differed between the different time periods we are analyzing.

  - There are other factors that could potentially impact the success of a movie, such as the quality of the script, the marketing campaign, or the performance of the actors. Unfortunately we can't possible have access to such information, but we can shield our selves by using a sensitivity analysis model (what we saw in week 6 of class)

### Some ideas to control confounding variables
- Stratified analysis : We divide our data into subgroups that depend on time periods (think baby boomer era vs gen Z era for example) to reduce the impact of the previously considered confounders; movies in the same time-period are much more likely to be made using similar technology and during comparable economic conditions.  We can see how audience preference shifts through time (by seeing how the top movies genres vary through time for example) 


We recognize that it is impossible to completely encapsulate the effect of the confounders, but we hope that by taking them into consideration and communicating the limits of our analysis we are increasing the validity of our analysis.

# Without IMDB revenue, only average rating and number of votes, we can still...
...explore the relationship between actor/actress experience and movie success. Just use the IMDB average movie rating as a measure of movie success, and the number of votes as a proxy for the popularity of the movie.

Idea:
create a scatterplot to visualize the relationship between actor/actress experience and IMDB average movie rating. We can fit a regression model to predict IMDB average movie rating based on actor/actress experience, and use the number of votes as a control variable to account for the popularity of the movie. This would allow us to see if there is a relationship between actor/actress experience and movie success, controlling for the popularity of the movie.

Of course, there are still drawbacks; using IMDB average movie rating and the number of votes as a measure of movie success has some limitations. For example, these measures may not be directly related to box office revenue, and there could be other factors that influence the IMDB rating or the number of votes a movie receives that are not related to the quality or success of the movie. However, using these measures can still provide valuable insights into the relationship between actor/actress experience and movie success.

<!-- # Correlation between actor features and success metrics (building credibility for our chosen features)

Linear relations between the actor features and also with ratings, revenue and budget


| Feature    | Description       | 
|:-------------|:------------------|
| Age                   | Age of the actor |
| Experience            | Number of movies as lead actor before the time of realease of the movie   |
| Genre background      | Vector showing the different type of genres the actor has worked in - signifying diversity    |
| Gender                | Actor:0/Actress:1 | -->

## Non-trivial difference between popularity and critical acclaim []
The quote 
> Whether the work that I do shall succeed or achieve critical acclaim is for the audience to decide.

by Amitabh Bhachan is proof that there is difference between the two still remains non-trivial

Many movies such as Tenet, Avatar and other huge budget movies backed by very well acclaimed directors have lead to success by both metrics.
# How do actor profiles change over time ?? Does it suggest something


## Have a comparison of features based on different success metrics

*   This is an unordered list following a header.
*   This is an unordered list following a header.
*   This is an unordered list following a header.

##### lifetime of an actor in a genre - first movie to last movie
1.  This is an ordered list following a header.
2.  This is an ordered list following a header.
3.  This is an ordered list following a header.