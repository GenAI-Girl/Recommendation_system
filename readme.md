## Recommendation System 

Def : Model that is intelligent enough to understand user preference and recommend the set of new items for that corresponding user.

Types: Four types of recommender system

1. Popular recommender system : Youtube trending videos recommendation, imdb top 250 movies (this doesn’t consider user preferences to recommend something) - top/best items in the platform. Example: Top 10 movies in India on netflix.
2. Content based recommender system: If a user buys one branded system, then the same branded items will be recommended so that user may like it. (movie - actor, genre, director, production house). Example: beca u watched this so you might like this in netflix, ; in ecom with TV, recommendation Accessroies, mobile - Accessories.
3. Collaborative filtering based recommender system: Based on users liked/preferred recommendation. - recommendation based on user ratings (consider 5 movies available in the platform, take two user ratings for all movies (you can find the similarity search in between two movies and decide to recommend the movies ). Example: Main Difference: Collaborative relies on community preferences, while content-based uses item similarity. What other users are liking in action movies.

4. Hybrid recommender system: Based on above three recommender systems (Merge all recommender systems at one place with individual weightages) - find various approaches for hybrid recommender systems 

Dataset: https://www.kaggle.com/datasets/arashnic/book-recommendation-dataset (download three csv files - books, users, ratings)
Note : I have used Popular and collaborative recommendation types in the code file.