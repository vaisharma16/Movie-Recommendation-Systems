# <b style="color:white;">Recommendation Systems</b>

In this repository, we shall take a look at the very basic algorithms used by Recommendation Systems.



## <u><b>Content Based</b></u>

They suggest similar items based on a particular item. This system uses item metadata, such as genre, director, description, actors, etc. for movies, to make these recommendations. The general idea behind these recommender systems is that if a person liked a particular item, he or she will also like an item that is similar to it.

<b>Advantages</b>

- The model doesn't need any data about other users, since the recommendations are specific to this user. This makes it easier to scale to a large number of users.
- The model can capture the specific interests of a user, and can recommend niche items that very few other users are interested in.

<b>Disadvantages</b>

- Since the feature representation of the items is hand-engineered to some extent, this technique requires a lot of domain knowledge. Therefore, the model can only be as good as the hand-engineered features.
- The model can only make recommendations based on the existing interests of the user. In other words, the model cannot expand on the users' existing interests.

## <u><b>Collaborative Filtering</b></u>

This system matches persons with similar interests and provides recommendations based on this matching. Collaborative filters do not require item metadata like their content-based counterparts.

<b>Advantages</b>

- No domain knowledge necessary: We don't need domain knowledge because the embeddings are automatically learned.
- Serendipity: The model can help users discover new interests. In isolation, the ML system may not know the user is interested in a given item. However, the model might still recommend it because similar users are interested in that item.
- Great starting point: To some extent, the system needs only the feedback matrix to train a matrix factorization model. In particular, the system doesn't need contextual features. In practice, this can be used as one of multiple candidate generators.

<b>Disadvantages</b>

- Cannot handle fresh items
- Hard to include side features for query/item

## <b style="color:white;">Tech Stack</b>

> Python<br />
> Pandas<br />
> Numpy<br />
> Matplotlib and Seaborn<br />
> Sklearn<br />

## <b style="color:white;">Resources</b>

> <a href="https://www.youtube.com/playlist?list=PLZoTAELRMXVN7QGpcuN-Vg35Hgjp3htvi">Krish Naik Recommendation System Playlist</a><br />



## <b style="color:white;">App Info</b>

### Author [Vaibhav Sharma](https://www.linkedin.com/in/vaibhavsharma16/)
