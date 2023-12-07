#  EE 541 – Computational Introduction to Deep Learning Project
## CineLit Recommender: Elevating Entertainment Discovery
The project seeks to deliver a cross-platform recommendation engine as a customized solution for content discovery, specifically designed to address the growing difficulty of traversing the huge and constantly developing landscape of both literary and cinematic content. By making movies and books more closely match personal tastes and inclinations, this effort aims to improve the user experience. A good example would be Amazon's Prime Video recommending books from Amazon Kindle once a given movie has been finished by the user, thus increasing the number of impressions and ad revenue for their alternative subplatforms or other websites. The project utlizies the following datasets:<br />
[The Movie Dataset](https://www.kaggle.com/datasets/rounakbanik/the-movies-dataset/data)<br />
[Goodreads Dataset](https://www.kaggle.com/datasets/yehyachali/top2k-books-with-descriptions)

### Requirements 
```
tensorflow
tensorflow_recommenders

pandas
numpy
scikit-learn

seaborn
matplotlib

wordcloud

stringcase
re
astroid
```
These libraries are essential for building a recommendation system. TensorFlow provides a powerful framework for machine learning, and TensorFlow Recommenders simplifies building recommendation models. Pandas, NumPy, and scikit-learn enable efficient data manipulation and analysis. Seaborn and Matplotlib facilitate data visualization. Wordcloud aids in textual data exploration, while string and regular expression handling (re) are crucial for text processing in recommendation systems.

## How to run the project?

1. Install all the libraries mentioned in the [requirements.txt](https://https://github.com/Otto-Octavius/EE541-CineLit/blob/main/requirements.txt) file.
2. Clone this repository in your local system.
3. Pass a title from the movie dataset to `hybrid.py` file. Two functions take for movie and then book recommendation.
4. Perform the same for `deep.py` file, but pass the UserID and Movie name. Two functions are present to predict the rating of the user on a unseen content and recommended movies
5. Book recommendation is done via content based filtering as the available data consists of only primarily textual data.

### To install dependencies
```
pip install -r requirements.txt
```
