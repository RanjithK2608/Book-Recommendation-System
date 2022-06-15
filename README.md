Book-Recomendation-Sytem

#Objective:
  The main objective is to create a book recommendation system for users. Recommender systems are really critical in some industries as they can generate a huge amount of income when they are efficient or also be a way to stand out significantly from competitors.

Methods Used:
Descriptive Statistics Data Visualization Machine Learning

Technologies:
Python Pandas Numpy Matplotlib Seaborn Scikit-learn Surprise

Algorithms Implemented:
Popularity Based Filtering
Corelation Based Recommendation System
KNN Based Recommendation System
SVD Based Recommendation System
Content Based Recommendation System
Data:
The Book-Crossing dataset comprises 3 files.

Users : Contains the users. Note that user IDs (User-ID) have been anonymized and map to integers. Demographic data is provided (Location, Age) if available. Otherwise, these fields contain NULL values.

Books : Books are identified by their respective ISBN. Invalid ISBNs have already been removed from the dataset. Moreover, some content-based information is given (Book-Title, Book-Author, Year-Of-Publication, Publisher), obtained from Amazon Web Services. Note that in the case of several authors, only the first is provided. URLs linking to cover images are also given, appearing in three different flavors (Image-URL-S, Image-URL-M, Image-URL-L), i.e., small, medium, large. These URLs point to the Amazon website.

Ratings : Contains the book rating information. Ratings (Book-Rating) are either explicit, expressed on a scale from 1-10 (higher values denoting higher appreciation), or implicit, expressed by 0.

CONCLUSION:
● Recommendation system is unturned to exist in the e-commerce businesses with the help of collaborative or content-based filtering to predict different items and yes, users are most satisfied with the products recommended to them.

● Books with publication years are somewhat between 1950 - 2005.

● Also the readers mostly give 8 ratings (on scale 1-10) to books followed by 10 and 7.

● There are more readers from locations London, England, United Kingdom, Toronto, ontar io, Canada compare to other locations.

● KNN model gives good recommendation for books.

● The best collaborative book recommender model is SVD(Singular value decomposition) with best accuracy on test data which give stronger recommendations. These results show that our proposed system can remove boring books from the recommendation list more efficiently
