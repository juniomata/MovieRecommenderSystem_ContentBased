# Movie Recommender System (ContentBased)
This project is initiated by [DQLab Academy](https://academy.dqlab.id), an Online Data Science Course Platform. However, the content of this project is not completely the same as the project of DQLab Academy, but have several modifications.

In this project, I made a recommender system using Content/feature from the movies/entities, then calculates the similarities to one another, so that when we go to a movie, we will get movies recommendations that have similarities to the movies we chose. We call this **`Content-Based Recommender System`**. By comparing the plot and genre similarities, the audience who watch Narnia will be recommended another movie such as Harry Potter or Lord of The Rings which have similar genres. 

The data of this project can be accessed through:
- [Rating dataset](https://dqlab-dataset.s3-ap-southeast-1.amazonaws.com/movie_rating_df.csv)
- [Actors dataset](https://dqlab-dataset.s3-ap-southeast-1.amazonaws.com/actor_name.csv)
- [Directors/Writers dataset](https://dqlab-dataset.s3-ap-southeast-1.amazonaws.com/directors_writers.csv)

Here we can see the result of the recommender system. For instance, we want to see what movies will be recommended if we watch Iron Man. As we can see, Black Panther, X-Men: Apocalypse, and Start Trek will be the top 3 as they have strong similarity to Iron Man.
![pic1](https://github.com/juniomata/MovieRecommenderSystem_ContentBased/blob/main/Recommender%20System%20Ironman.JPG)
