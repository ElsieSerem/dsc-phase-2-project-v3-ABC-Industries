# ABC Industries: Film Industry Analysis

<h1 align="center">
  <img src="https://github.com/ElsieSerem/dsc-phase-2-project-v3-ABC-Industries/blob/main/Images/Cinema.jpg?raw=true" alt="ABC Industries" height = 400 width="800" />
</h1>

## Overview
This project aims to utilize movie data from movie aggregation websites to create proposals for a hypothetical new ABC Industries Studio. It explores the movie industry to identify the most successful film genres, themes, and audience demographics. The goal of this project is to provide actionable insights for a new movie studio to guide content creation and target audience engagement. 

## Business Understanding
This project will analyze box office trends to identify successful film genres, themes, and audience demographics. By providing actionable recommendations, the studio can make informed decisions on content creation and audience engagement. This will help ABC Industries produce successful films and establish a strong foothold in the competitive film industry.

The primary stakeholders for this project include:

   1. ABC Industries Executives: To inform strategic decision-making and investment in content creation.
   2. New Movie Studio Management: To guide the production and marketing strategies.
   3. Content Creators and Directors: To understand current trends and audience preferences.
   4. Marketing Teams: To effectively target and engage the right audience demographics.

The key business questions to be answered are:

   1. What are the top three genres that should be utilized for content creation?
   2. What genres of movies are currently performing well at the box office in terms of income generation?
   3. Which directors tend to produce movies with higher commercial success, and should we consider working with them?
   4. What are the key characteristics that ensure the success of movies in the long run?

## Data Understanding and Analysis

The data used for this analysis comes from four sources:

1. Box Office Mojo (BOM)
2. Rotten Tomatoes (RT)
3. TheMovieDB (TMDB)
4. The Numbers (TN)
[(Access Data Here)](https://github.com/ElsieSerem/dsc-phase-2-project-v3-ABC-Industries/tree/main/zippedData)

The data includes information on movie genres, directors, runtime, vote counts, and worldwide gross amounts and others which are very crucial for this project.

## Results
### Distribution of Worldwide Gross Amount
This histogram shows the distribution of worldwide gross amounts across different ranges.
![ABC Industries](https://github.com/ElsieSerem/dsc-phase-2-project-v3-ABC-Industries/blob/main/Images/Histogram.png?raw=true) 

It is rightly skewed so it shows that there are indeed specific genres that generate a high amount of revenue compared to the other genres.


### Mean Worldwide Gross Amount by Genre
This bar chart shows the mean worldwide gross amount for each genre.
![ABC Industries](https://github.com/ElsieSerem/dsc-phase-2-project-v3-ABC-Industries/blob/main/Images/Bar%20graph%201.png?raw=true)
The plot shows that some genres tend to have higher or lower mean worldwide gross amounts than others, the top three being  **science fiction and fantasy, Animation and Action and Adventure**

### Relationship between Runtime and Vote Count
This scatter plot shows the relationship between runtime and vote count.

![ABC Industries](https://github.com/ElsieSerem/dsc-phase-2-project-v3-ABC-Industries/blob/main/Images/Scatter%20Plot.png?raw=true)
This information can be useful when selecting genres for content creation, as it can help identify the types of movies that audiences prefer in terms of runtime.According to the scatterplots runtime of between 80 and 120 minutes is preferable to most people

A more comprehensive expalnation of the  various relationships between variables and genre popularity can be located in the [Jupyter_Notebook](https://github.com/ElsieSerem/dsc-phase-2-project-v3-ABC-Industries/blob/main/student.ipynb). For  more interaction with the charts and graphs, they can be accessed through this link ([Visualizations](https://github.com/ElsieSerem/dsc-phase-2-project-v3-ABC-Industries/tree/main/Images))

## Recommendations
Based on the analysis, the top three genres recommended  for content creation are:

1. Science Fiction and Fantasy
2. Animation
3. Action and Adventure

These genres tend to perform well at the box office and are popular among voters. By focusing on these genres, the studio can increase its chances of producing commercially successful movies that resonate with audiences.

**Additionally, the analysis suggests that:**

* Movies with a runtime of between 80 and 120 minutes tend to perform well.
* Directors who have a track record of producing successful movies should be considered for collaboration.

By following these recommendations, the studio can make informed decisions and increase its chances of success in the competitive movie industry. [Presentation slides](https://github.com/ElsieSerem/dsc-phase-2-project-v3-ABC-Industries/blob/main/Presentation%20PDF.pdf) have been prepared in order to allow ease of understanding and highlight our next steps derived from the findings of this analysis.

 # Summary of Conclusions
Statistical tests were conducted and it was concluded that:
  1. Based on the t-test results, it can be concluded that Science Fiction and Fantasy movies tend to earn more worldwide than other genres, suggesting that prioritizing these genres could lead to greater financial success.

  2. The linear regression analysis indicates that audience engagement, as measured by the number of votes a movie receives, is strongly correlated with a movie's worldwide gross, highlighting the importance of engaging audiences to achieve financial success.

  3. Finally, the chi-squared test reveals a significant association between movie genres and directors, suggesting that the genre a director works in can impact a film's success. This finding supports the recommendation to collaborate with successful directors in the Science Fiction and Fantasy, Animation, and Action and Adventure genres. 