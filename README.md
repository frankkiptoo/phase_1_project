# MICROSOFT MOVIE PRODUCTION STRATEGY

![Wallpaper](https://github.com/frankkiptoo/passion_projects/assets/133040810/e35b2357-596f-4746-bd88-fcc34d52a948)

## Overview

Exploratory Data Analysis on movie data files was used to gain valuable insights into the top-performing movie genres at the box office.

### Business Problem

The film industry is dynamic and diverse, with various genres and styles of movies catering to different audience preferences. Box office success depends on factors such as storytelling, cast, production quality, marketing efforts, and timing of release. To maximize the studio's chances of profitability and audience appeal, it is essential to identify the types of films that are currently performing the best in terms of box office revenue and audience reception.

Microsoft's new movie studio needs to understand the prevailing trends in the film industry and use this knowledge to strategically decide the type of films they should produce. The goal is to invest in movie projects that have the potential for commercial success and can capture the attention of diverse audiences.

This project focused on analyzing movie data files to provide recommendations to Microsoft's new movie studio on the type of films to produce and invest in.

The business questions to be answered are:
* What type of genres have the highest rating?
* What is the most popular genre by the number of votes?
* Does the production budget affect the profits and the returns on investment?

### The Data

For this project, the following data files were used
* imdb.title.basics
* imdb.title.ratings
* tn.movie_budgets

## Methodology
The following steps were taken to do exploratory analysis on the data:
* Importation of Libraries and Loading the Data Files into a Dataframe
* Exploratory Data Analysis (EDA)
* Data Visualization
* Findings/Observations
* Recomendations
* Conclussion

### Results & Observations
There's a strong positive relationship between production budget and worldwide gross with a correlation coefficient of 0.7463980543365651. As one variable increases, the other also tends to exhibit a corresponding increase, and vice versa. However, it is essential to note that a strong correlation between the two variables does not imply a causal relationship. Typically, movies with substantial budgets, entailing higher production costs, often come with more extensive marketing campaigns, improved production quality, and broader audience access. These elements collectively contribute to higher box office revenues and global popularity, resulting in a positive correlation between the movie's production budget and its worldwide gross. Despite this evident correlation, it is crucial to acknowledge that causation cannot be solely attributed to the relationship between production budget and worldwide gross.
The correlation coefficient between the production budget and domestic gross is 0.6819410163832446, indicating a moderately positive correlation. This means that, on average, when the production budget rises, the domestic gross revenue also tends to increase. This finding aligns with typical expectations in the film industry, where movies with larger production budgets often enjoy enhanced production values and access to better resources. Consequently, these factors contribute to higher ticket sales and increased revenue at the domestic box office.

![Scatter Plot](https://github.com/frankkiptoo/passion_projects/assets/133040810/e15e655c-7759-41e9-8d53-5fd30255252c)

![Bar Plot](https://github.com/frankkiptoo/passion_projects/assets/133040810/3417f467-b928-4318-8bca-e950bccad3ca)

After conducting the analysis and examining the results, it is evident that short films rank as the highest-rated genre, followed by documentaries and game-shows. This suggests that short films are generally well-liked by the audience. However, it's essential to note that the average rating of short films is influenced by a small number of movies within this genre that have received exceptionally high ratings. As a result, the overall high rating of short films may be attributed to these select few well-rated movies compared to documentaries, which may have a more varied range of ratings. A high rating for a movie indicates positive audience feedback and overall satisfaction with the film.

![Top Genre Rating](https://github.com/frankkiptoo/passion_projects/assets/133040810/7970010d-4d62-4e93-968b-7eda68c4f15f)

The top 4 most popular genre by number of votes is: Drama, Action, Adventure, Comedy. Several factors can influence a movie's high vote count, as it results from a blend of audience engagement and movie quality. Films that have extensive promotion, enjoy wide distribution, and garner substantial media attention tend to draw a larger viewership, ultimately contributing to an increased vote count.

![Top Genre Votes](https://github.com/frankkiptoo/passion_projects/assets/133040810/75f11333-50a8-4b25-8852-f1fde61b751b)

## Recommendations

The analysis led to the following recommendations:
1. Produce films with high ratings. A movie's high rating reflects the audience's favorable reaction and overall contentment with the film. To ensure successful movie production, Microsoft should prioritize creating films with higher ratings by emphasizing essential elements such as compelling storytelling, exceptional acting by talented performers, skilled direction, emotional involvement, originality, creativity, and relevance to social issues.
2. My recommendation to Microsoft is to focus on producing popular movies that appeal to viewers, specifically Drama or Action films, as these genres are highly preferred by audiences. There are several reasons behind the preference for each genre. Drama movies, for instance, evoke emotional depth, character development, and thought-provoking themes, enabling viewers to feel a strong connection with the characters and their stories. The realism and powerful storytelling in dramas often resonate with many, offering opportunities for introspection. On the other hand, Comedy movies aim to entertain through humor and wit, providing lighthearted and enjoyable experiences that serve as a break from the stresses of daily life. The shared laughter and bonding experiences with friends and family make comedies relatable and appealing. As for Action movies, they offer thrilling and adrenaline-pumping experiences that captivate audiences seeking excitement and adventure.
3. My suggestion to Microsoft is to focus on producing cost-effective movies while directing attention towards targeted marketing, limited releases, and streaming platforms. This strategy would enhance their profitability and return on investment (ROI). Despite the lower production costs, it is crucial not to compromise on the movie's quality. When dealing with high production budgets, the movie must generate substantial revenue at the box office to cover its expenses and be deemed profitable. Higher production budgets come with increased financial risks. If a movie with a large budget fails to perform well at the box office, it could lead to significant financial losses for the producers and investors. Conversely, a successful movie with a substantial budget can result in considerable rewards and profits.

## Conclusion

In conclusion, the analysis and findings offer several key recommendations for Microsoft's movie production strategy:

1. Focus on producing movies with higher ratings, emphasizing good storytelling, strong acting performances, skillful direction, emotional engagement, originality, creativity, and addressing relevant social issues. Such films are likely to receive positive responses from the audience, leading to increased popularity and overall satisfaction.
2. Consider producing Drama and Action films as they align with viewer preferences. Drama movies evoke emotional depth and thought-provoking themes, while Action films provide thrilling experiences with fast-paced sequences and high-stakes adventures.
3. Aim to produce movies with lower production costs while strategically utilizing targeted marketing, limited releases, and streaming platforms. This approach can increase profitability and ROI, especially for niche films or low-budget productions. However, maintaining film quality is essential, as audience feedback and critical acclaim significantly impact a movie's overall success.

By implementing these recommendations, Microsoft can enhance their ability to create successful and well-received films, effectively catering to audience interests and preferences while optimizing their return on investment.
