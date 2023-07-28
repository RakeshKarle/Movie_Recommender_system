# Movie_Recommender_system

The project involved merging datasets, preprocessing data, and extracting features.Text processing techniques, such as lowercase conversion and stemming, were applied to the 'tags' column to standardize textual data.Using Count Vectorization and cosine similarity, developed a recommendation system for personalized movie suggestions.Tools & Skills Demonstrated - Data analysis, Visualization, and Machine Learning(Recommender system , NLP libraries).

# Detailed description of the project:

1. Objective: The project aims to perform customer segmentation for a movies dataset to identify distinct groups of movies based on their characteristics and create a recommendation system.

2. Data Collection: Two datasets are used - "tmdb_5000_movies.csv" containing movie information and "tmdb_5000_credits.csv" containing cast and crew details.

3. Data Preprocessing:
Merging Data: The two datasets are merged on the movie title to create a consolidated dataset.
Handling Missing Data: Null values in the 'overview' column are dropped to ensure data completeness.
Data Cleaning: Text data in 'genres,' 'keywords,' 'cast,' and 'crew' columns are converted from JSON-like strings to Python lists for easier processing.

4. Feature Engineering:
Genres, Keywords, Cast, Crew: Extracted relevant information from nested JSON-like strings and converted them into lists of features.
Concatenation: Created a new column 'tags' by combining 'overview,' 'genres,' 'keywords,' 'cast,' and 'crew' to represent each movie with its key characteristics.

5. Text Preprocessing:
Lowercasing: Converted all text in the 'tags' column to lowercase for standardization.
Stemming: Applied Porter Stemming to reduce words to their base or root form, improving text analysis.

6. Feature Extraction:
Count Vectorization: Used CountVectorizer from scikit-learn to convert the text data into numerical vectors.
Cosine Similarity: Calculated cosine similarity between movie vectors to find similar movies.

7. Recommendation System:
Function: Developed a 'recommend' function to provide movie recommendations based on cosine similarity scores.
Input: The function takes a movie title as input.
Output: It suggests the top five most similar movies based on the provided movie title.

8. Skills Demonstrated:
Data Handling: Loading, cleaning, and merging datasets to prepare data for analysis.
Feature Engineering: Extracting useful information from nested JSON-like strings.
Text Preprocessing: Converting text to lowercase and applying stemming to improve text analysis.
Feature Extraction: Using Count Vectorization to convert text data into numerical vectors.
Recommendation System: Implementing a movie recommendation system based on cosine similarity.

The project demonstrates proficiency in data analysis, text preprocessing, and recommendation systems, making it a valuable addition to a resume for showcasing data science and machine learning skills.
