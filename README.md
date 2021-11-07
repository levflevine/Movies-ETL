# Movie Dataset Extract - Transform - Load (ETL)

## Overview of the analysis

Amazing Prime Video (APV), online platlform for streaming movies and TV shows, is developing an analytics tool to predict which low-budget movies that are being released will become popular. This will help to early identify the winners and acquire movie rights at a discount.

To engage with a student comunity, APV decided to sponsor a hackathon that will ask the participants to develop prediction models. A prerequisite for the hackathon is having a clean dataset to work with. There are several large data sources available that will need to extracted, cleaned, normalized, and loaded into a SQL database.

### Deliverables: 

1. Write an ETL function to read three data files
2. Extract and Transform the Wikipedia Data
3. Extract and Transform the Kaggle Data
4. Create the Movie Database

### Tools and Data Sources

#### Tools

- Python Scripts
- Pandas Library
- Jupyter Notebook
- PostgreSQL
- pgAdmin

#### Data Sources

- [Wikipedia JSON file](https://2u-data-curriculum-team.s3.amazonaws.com/dataviz-online/module_8/wikipedia-movies.json)
- [Kaggle metadata](https://www.kaggle.com/rounakbanik/the-movies-dataset/download)
- [The Movie Database (TMDb) Ratings](https://www.kaggle.com/rounakbanik/the-movies-dataset/download)

## Results

**1. Wrote an ETL function to read three data files**

***Wiki Movies DataFrame***

![Wiki Movies](/Resources/Del_1_wiki_movies_df.png)

***Kaggle Metadata DataFrame***

![Kaggle Metadata](/Resources/Del_1_kaggle_md_df.png)

***Ratings DataFrame***

![Ratings](/Resources/Del_1_ratings_df.png)

**2. Extracted and Transformed the Wikipedia Data**

***Cleaned Wiki Movies DataFrame***

![Clean Wiki Movies](/Resources/Del_2_clean_wiki_movies_df.png)

***Cleaned Wiki Movies Columns***

![Columns](/Resources/Del_2_clean_wiki_movies_columns.png)

**3. Extracted and Transform the Kaggle Data**

***Merged Wiki and Kaggle DataFrame***

![Merged Movies DF](/Resources/Del_3_movies_df.png)

***Movies DataFrame with Ratings***

![with Ratings](/Resources/Del_3_movies_with_ratings_df.png)

**4. Created the Movie Database**

***Movies SQL Table***

![Movies Table](/Resources/movies_query.png)

***Ratings SQL Table***

![Ratings Table](/Resources/ratings_query.png)