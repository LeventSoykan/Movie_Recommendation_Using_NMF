Movie Recommendation Using NMF
==============================

This project provides a recommendation system for movies based on Non-negative Matrix Factorization (NMF). It uses a dataset of movie ratings from the [MovieLens](https://grouplens.org/datasets/movielens/) website.
The processing steps are:
* Text preprocessing (Using spacy, nltk)
* Vectorization (Using Tf-Idf Vectorization)
* Non Negative Matrix Multiplication
* Calculation of movie similarity from final feature matrix

Installation
------------

To install the required libraries, you can use pip:

Copy code

`pip install numpy pandas scikit-learn`

You will also need to download the data files from the `data` folder in this repository.

Usage
-----

The main entry point for the project is the `movie_recommendation.py` script. You can run it from the command line:

Copy code

`python movie_recommendation.py`

This will load the data, perform NMF on the ratings matrix, and generate movie recommendations for a given user. You can customize the behavior of the script by modifying the parameters in the `config.json` file.

Features
--------

The project includes several features to recommend movies to users:

*   **NMF-based recommendation**: The script uses Non-negative Matrix Factorization (NMF) to factorize the ratings matrix into user and movie latent factors. These factors can be used to generate personalized movie recommendations for a given user.
    
*   **Movie similarity analysis**: The script also calculates the similarity between movies based on their latent factors. This can be used to recommend similar movies to a given user, or to analyze the relationships between different movies.
    
*   **User-based recommendation**: The script can also generate recommendations based on the ratings of similar users. This approach can be useful when there are not enough ratings for a given user.
    

License
-------

This project is licensed under the MIT License. See the LICENSE file for more details.

Contributing
------------

Contributions are welcome! If you want to contribute to this project, please fork the repository and submit a pull request with your changes.
