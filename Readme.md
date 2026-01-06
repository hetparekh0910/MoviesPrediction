**Movie Recommendation System**

This project implements a Content-Based Movie Recommendation System using Python. It leverages natural language processing (NLP) techniques to analyze movie metadata and suggest similar movies to users based on their interests.

**🚀 Features**

Data Analysis: Exploration of movie and rating datasets.

Visualization: Generation of Word Clouds to visualize the most prominent genres and movie titles.

Recommendation Engine: Uses TF-IDF Vectorization and Cosine Similarity to recommend movies based on genre and title descriptions.

**🛠️ Technologies Used**
Python: Core programming language.

Pandas: For data manipulation and analysis.

Matplotlib: For data visualization.

WordCloud: To create visual representations of text data.

Scikit-learn: For feature extraction (TfidfVectorizer) and computing similarity scores (linear_kernel).

**📊 Dataset**

The project uses two primary datasets:

movies.csv: Contains movieId, title, and genres (e.g., Adventure, Animation, Children, Comedy, Fantasy).

ratings.csv: Contains user ratings for various movies, including userId, movieId, rating, and timestamp.

**⚙️ How it Works**
Data Preprocessing: The project cleans movie titles and extracts individual genres from a pipe-separated string format.

Feature Extraction: A TF-IDF (Term Frequency-Inverse Document Frequency) matrix is built from the movie descriptions.

Similarity Calculation: Cosine Similarity is calculated between movies to determine how closely they relate to one another.

Recommendation: Given a movie title, the system identifies and returns the top similar movies from the dataset.

**💻 Usage**
Ensure you have movies.csv and ratings.csv in your project directory.

Install the required libraries:

_pip install pandas matplotlib wordcloud scikit-learn_

Run the Jupyter Notebook MoviesPrediction.ipynb to view the analysis and test the recommendation engine.
