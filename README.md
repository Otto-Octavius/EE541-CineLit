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

### Results
1. Hybrid recommendation for both Book and Movie
![Screen Shot 2020-06-06 at 9 36 16 PM](https://github.com/Otto-Octavius/EE541-CineLit/blob/main/results/Screenshot%202023-12-07%20074925.png)
2. Deep learning recommendation for a given User and their predicted rating for a particular content
![Screen Shot 2020-06-06 at 9 36 16 PM](https://github.com/Otto-Octavius/EE541-CineLit/blob/main/results/Screenshot%202023-12-07%20080655.png)

### References
[1]. Pitiwat Arunruviwat, Veera Muangsin, “A Hybrid Book Recommendation System for University Library” 2022 26th International Computer Science and Engineering Conference (ICSEC) | IEEE | DOI: 10.1109/ICSEC56337.2022.10049318.

[2]. Sakina Salmani, Sarvesh Kulkarni, “Hybrid Movie Recommendation System Using Machine Learning”, 2021 International Conference on Communication Information and Computing Technology (ICCICT) | IEEE | DOI: 10.1109/ICCICT50803.2021.9510058

[3]. Yassine Afoudi, Mohamed Lazaar, Mohammed Al Achhab, “Hybrid recommendation system combined content-based filtering and collaborative prediction using artificial neural network,” Elsevier, Simulation Modelling Practice and Theory, Volume 113, December 2021, doi: 10.1016/102375.

[4]. N. Ifada, T. F. Rahman and M. K. Sophan, ”Comparing Collaborative Filtering and Hybrid based Approaches for Movie Recommendation,” 2020 6th Information Technology International Seminar (ITIS), 2020, pp. 219-223, doi: 10.1109/ITIS50118.2020.9321014.

[5]. Y. Xiong and H. Li, ”Collaborative Filtering Algorithm in Pictures Recommendation Based on SVD,” 2018 International Conference on Robots and Intelligent System (ICRIS), 2018, pp. 262-265, doi: 10.1109/ICRIS.2018.00074.

[6].  S. Agrawal and P. Jain, ”An improved approach for movie recommendation system,” 2017 International Conference on I-SMAC (IoT in Social, Mobile, Analytics and Cloud) (I-SMAC), 2017, pp. 336-342, doi: 10.1109/ISMAC. 2017.8058367.

[7].  Blog Post, “https://medium.com/analytics-vidhya/building-a-movie-recommendation-engine-in-python-53fb47547ace"


