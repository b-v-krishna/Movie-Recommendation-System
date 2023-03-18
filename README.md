# Movie-Recommendation-System

<h3>Introduction</h3>
This project involves building a movie recommendation system using the cosine similarity metric. The dataset contains 4803 rows and 24 columns, and we have extracted five relevant features: genres, keywords, tagline, cast, and director. We have used the TF-IDF vectorization method to convert the textual data into numerical values.


<h3>Functionality</h3>
The recommendation system takes a movie name as input and suggests movies similar to it based on their similarity score. The similarity score is calculated using the cosine similarity metric.
The system also has a feature to correct spelling mistakes in the user's input. It uses the difflib library to get the closest match from the list of all movie titles.

<h4>!! Finally, The system will suggest the top 20 similar movies based on the cosine similarity metric.</h4>
