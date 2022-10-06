# Movies-ETL

Amazing Prime would like to create an automated pipeline that takes in new data and loads it into the existing tables, once appropriate transformations have been done on it.  

There are 4 parts to this ask:  
  ### 1. The ETL Function Test: 
  
  #### This function should read in three data files: 
  - The Wikipedia json file
  - The Kaggle metadata
  - The MovieLens ratings data
  
  This is what they will each look like:
  
  Wikipedia json file
  
  ![Wiki_json](https://github.com/SoumyaAbraham/Movies--ETL/blob/main/Screenshots/del1wikiMovies.png)  
  
  Kaggle metadata
  
  ![Kaggle_meta](https://github.com/SoumyaAbraham/Movies--ETL/blob/main/Screenshots/del1kaggleMeta.png)
  
  MovieLens Ratings
  
  ![MovieLens_rate](https://github.com/SoumyaAbraham/Movies--ETL/blob/main/Screenshots/del1ratings.png)
  
  ### 2. In the second part, we are going to transform our Wikipedia data to merge it with kaggle metadata. 
  
 #### This is what the final dataframe will look like:
  
  wiki_movies_df
  
  ![wiki_movies_df](https://github.com/SoumyaAbraham/Movies--ETL/blob/main/Screenshots/del2wiki_movies.png)
  
  ### 3. In this step, we first extract and transform the kaggle metadata and the Movielens rating data, creating separate dataframes for each transformed data.  
  
 #### This is what each dataframe will look like:
  
  wiki_movies_df  
  
  ![wiki_movies_df](https://github.com/SoumyaAbraham/Movies--ETL/blob/main/Screenshots/del3wikimovies_df.png)
  
  movies_with_ratings_df
  
  ![movies_with_ratings_df](https://github.com/SoumyaAbraham/Movies--ETL/blob/main/Screenshots/del3wikimovies_rating_df.png)
  
  movies_df
  
  ![movies_df](https://github.com/SoumyaAbraham/Movies--ETL/blob/main/Screenshots/del3movies_df.png)
  
  ### 4. In this final step, we are going to attempt to add the movies_df dataframe and MovieLens rating csv data to an SQL database.  
  
 #### You can find each of the codes here:  
  
  * [ETL_function_test](https://github.com/SoumyaAbraham/Movies--ETL/blob/main/ETL_function_test.ipynb)  
  * [ETL_clean_wiki_movies](https://github.com/SoumyaAbraham/Movies--ETL/blob/main/ETL_clean_wiki_movies.ipynb)  
  * [ETL_clean_kaggle_data](https://github.com/SoumyaAbraham/Movies--ETL/blob/main/ETL_clean_kaggle_data.ipynb)  
  * [ETL_create_database](https://github.com/SoumyaAbraham/Movies--ETL/blob/main/ETL_Create_Database.ipynb)  
  
  --
  
  
  

