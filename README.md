# Recommender-System-ML
INTRODUCTION
In the era of digital content consumption, personalized recommendation
systems play a crucial role in enhancing user experience and engagement.  Leveraging the MovieLens dataset from the GroupLens research lab, we  aim to build an effective movie recommendation system. This system will  utilize collaborative filtering techniques to suggest movies based on user  ratings, thereby providing personalized movie recommendations.

PROBLEM STATEMENT
Develop a recommendation system that provides top 5 movie  recommendations to users based on their past ratings. The system should  address the challenge of sparsity in user ratings and the cold start problem  for new users.
![image](https://github.com/Njoroge-Mwaura/Recommender-System-ML/assets/31213983/d1e1d4cf-9c37-4d5d-b9d6-2d661526486c)

Purpose of the Study
Goal: Develop a robust and accurate movie recommendation system,  evaluate and optimize it.![image](https://github.com/Njoroge-Mwaura/Recommender-System-ML/assets/31213983/88db4913-dccd-4fbd-a1d5-8dec48ebcba7)
Importance: Enhance user experience and engagement by providing  personalized movie recommendations.
Objectives: Improve recommendation accuracy, understand user  behaviour, and explore model scalability![image](https://github.com/Njoroge-Mwaura/Recommender-System-ML/assets/31213983/28df0186-53b7-417c-b426-6a601b1aa255)

Scope of the Analysis
Dataset: MovieLens dataset (small)
url: https://grouplens.org/datasets/movielens/latest/
Columns: ‘movieId', 'imdbId', 'tmdbId', 'userId_x', 'rating', 'timestamp_x',  'title', 'genres', 'userId_y', 'tag', 'timestamp_y’
![image](https://github.com/Njoroge-Mwaura/Recommender-System-ML/assets/31213983/6f66b813-2f2d-448e-8de0-a10ed6072d09)

D A T A	P R E P A R A T I O N	A N D	C L E A N I N G![image](https://github.com/Njoroge-Mwaura/Recommender-System-ML/assets/31213983/099b2a28-e1b7-4522-89f7-fcf60b545ee1)
Data Cleaning
Handling Missing Values and Dropping Irrelevant  Data Transformation
Feature Engineering: Created new features such  as rating frequency, average user rating, and  genre popularity.
Normalization:
Scaled ratings between 0 and 1 using Min-Max  scaling to standardize input for model training.
![image](https://github.com/Njoroge-Mwaura/Recommender-System-ML/assets/31213983/cd547412-1aa0-46cc-ab8a-c61f2d7b7042)

E X P L O R A T O R Y	D A T A	A N A L Y S I S	( E D A )
Summary Statistics:  ![image](https://github.com/Njoroge-Mwaura/Recommender-System-ML/assets/31213983/9f079f6f-d960-4272-ab6d-89153f818695)
Mean rating: 3.84![image](https://github.com/Njoroge-Mwaura/Recommender-System-ML/assets/31213983/9755fc31-a612-46fc-8c39-45f3fbd8712c)
Standard deviation: 1.02  User and Movie Statistics:
'Pulp Fiction (1994)' is the most rated film of genre; Comedy|Crime|  Drama|Thriller and tagged as sci-fi
![image](https://github.com/Njoroge-Mwaura/Recommender-System-ML/assets/31213983/760adb97-e710-4eeb-ba48-3546eb55f55e)

![image](https://github.com/Njoroge-Mwaura/Recommender-System-ML/assets/31213983/0bfcef6f-c682-42bf-8c98-b6bf943a6bda)
