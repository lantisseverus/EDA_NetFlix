# EDA_NetFlix
Suggested Data Analysis Project for data analysis which you can exercise your data cleaning, data wrangling, and EDA which can help to answer some basic questions regarding the dataset.

## Dataset Content (Reference from Kaggle)
This dataset consists of TV shows and movies available on Netflix as of 2019. The dataset is collected from Flixable which is a third-party Netflix search engine.

In 2018, they released an interesting report that shows that the number of TV shows on Netflix has nearly tripled since 2010. The streaming service’s number of movies has decreased by more than 2,000 titles since 2010, while its number of TV shows has nearly tripled. It will be interesting to explore what other insights can be obtained from the same dataset.


### Questions:
- Extract the numeric digits from the Movie and TV shows
- Separate Movie and TV shows and understand their duration distribution
- See if the number of releases of shows/movies is increasing or decreasing with the years proceeds
- Understanding what content is available in different countries
- Understand the different trends of Movie and TV shows over years
- The most observed rating categories in TV shows and Movies
- The cast number differs among the country
- How much content does its release year differ from its year added
- The duration of Movie and TV shows fluctuation with the years added (Movie was calculated by - Minutes while TV shows were estimated by their Seasons)

https://www.kaggle.com/code/ezzaldin6/eda-of-netflix-contents/notebook

## Result & Limitation
It seems that most of the valid data reside between 2016-2019, and 2016 - 2019 was the years when Netflix expanded and gained more subscribers (See Reference from [demandsage](https://www.demandsage.com/netflix-subscribers/)).

![Netflix_subscribers_over_yrs](https://github.com/lantisseverus/EDA_NetFlix/assets/66398727/f3d461eb-2714-4992-ba07-bca3614bd603)


The data analysis has some limitations on the contents which were

aired in multiple countries, and this requires advanced text-extracting skills on the entries with multiple country names in one cell.

limited to 2016 to 2019, when the period is too short to be representative.

Had had more information like the content genre, subscribers over years, views data, budget, etc. more insightful data analysis and statistics hypothesis could have been applied to this dataset.
