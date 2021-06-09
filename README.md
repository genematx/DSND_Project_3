# Udacity DS Nanodegree -- Project 3

 # ETL and ML Pipelines for Processing Disaster Response Messages

 The repository contains the code used in Project 3 of Udacity Data Science Nanodegree. The main goal of the project is to develop a recommendation system for assets in the </a href="https://www.ibm.com/watson">IBM Watson platform</a>. The project explores the options of rank based, collaborative filtering, an finally, matrix factorization with SVD.

 ## Installation <a name="installation"></a>

 The code is written and tested in Python 3.5. Additional libraries to be installed beyond the standard Anaconda distribution are:

 - pandas 0.23.4 for handling the dataset
 - numpy 1.11.3 for performing linear operations on matrices
 - matplotlib 1.5.1 for visualizing the results

 The code has been developed and tested using the cited versions of the packages.

 ## File Descriptions <a name="files"></a>

  data/articles_community.csv - description of articles used in the project.

  data/user-item-interactions.csv - table containing records about each user reading any specific article.

  Recommendations_with_IBM.ipynb - main IPython notebook with the code of the project.

  Recommendations_with_IBM.html - the notebook with the code and results in html format.

  project_tests.py - tests to check the accuracy of the results (provided by Udacity).

  user_item_matrix.p - precomputed matrix of interactions making correspondence between users and articles (provided by Udacity).

  top_x.p - files containing references to top 5, 10, and 20 articles used for assessment of results (provided by Udacity).

  To run the project, please open the notebook and execute all commands by choosing Cell -> Run All in the main menu.


 ## Acknowledgements

 The dataset for this project was kindly provided by IBM.
