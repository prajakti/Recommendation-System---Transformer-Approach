# Recommendation-System---Transformer-Approach

Recommendation systems are a subclass of information filtering system that seeks to predict the "preference" a user would give to an item.They are primarily used in commercial applications.In this paper,we approach the recommendation systems using the Transformers - firstly, we implement a Behaviour Sequential Transformer model which translates the user behavior into sequences and predicts a rating for each target item. For our second approach we leveraged the Matrix Factorization and enhanced it using BERT embeddings from the items, to create a hybrid approach by combining Content-based filtering with Collaborative filtering approach. Further, we built a K-Nearest Neighbor model to capture the change in item embeddings and used the newly generated embed

DATASETS:
We used two datasets, which capture the interactions between the items and users, as our approaches demanded the interaction data as well as feature data, but we also wanted to test two datasets with different features and dimensionality. The two datasets are :
1. Food.com Recipes [10] - this captures the information about different recipes, different users, and the interaction between them through ratings. It consists of different features for 230186 unique recipes like their tags, ingredients and description, along with 1125284 total interactions between the users and the recipes.
2. Restaurant Data with Consumer Ratings [11] - this captures the information about different restaurants and their features, along with the user ratings for each of the restaurants. It consists of different features like cuisine, payment methods, parkings for each restaurant, and 1161 interactions between users and restaurants.
 hyperparameters to recommendations.
generate test
2.2 K-Nearest Neighbours on Embeddings
After the training of the Hybrid model using BERT embeddings. We wanted to analyze the change in embeddings and make recommendations based on the newly generated embeddings of each item, as shown in the
