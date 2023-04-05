Movie Recommendation Using NMF
==============================

This project provides a recommendation system for movies based on Non-negative Matrix Factorization (NMF). 
The processing steps are:
* Text preprocessing (Using spacy, nltk)
* Vectorization (Using Tf-Idf Vectorization)
* Non Negative Matrix Multiplication
* Calculation of movie similarity from final feature matrix

Analysis
--------
The project includes several analyses to recommend movies to users:

*   **NMF-based recommendation**: The script uses Non-negative Matrix Factorization (NMF) to factorize the ratings matrix into user and movie latent factors. These factors can be used to generate personalized movie recommendations for a given user.
    
*   **Movie similarity analysis**: The script also calculates the similarity between movies based on their latent factors. This can be used to recommend similar movies to a given user, or to analyze the relationships between different movies.
    

Dataset
-----------

Dataset is prepared from [CMU Movie Summary Corpus](http://www.cs.cmu.edu/~ark/personas/), a collection of 42,306 movie plot summaries

'movie.metadata.tsv': includes metadata on movies such as title, genre
'plot_summaries.txt': contains summaries of movie plots

License
-------

This project is licensed under the MIT License. See the LICENSE file for more details.

Contributing
------------

Contributions are welcome! If you want to contribute to this project, please fork the repository and submit a pull request with your changes.
