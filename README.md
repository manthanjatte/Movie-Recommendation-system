🎬 Movie Recommendation System – Content-Based Filtering using NLP and Python
This project builds a recommendation engine that suggests movies based on content similarity using natural language processing techniques.
Key features include:

Dataset: Utilized a Kaggle movie dataset with metadata including titles, genres, keywords, overview, and cast.

Technologies Used: Python, Pandas, Scikit-learn, NLTK, Jupyter Notebook

Approach:

Combined multiple features (title, overview, genre, keywords, cast, crew) into a single textual format.

Applied TF-IDF Vectorization and CountVectorizer to convert textual data into numerical format.

Calculated cosine similarity to recommend top 5–10 similar movies based on the user’s input.

NLP Techniques: Implemented text preprocessing like stemming, tokenization, and stop-word removal using NLTK.

Outcome: Accurately provides movie suggestions that are content-wise similar to the selected movie, enhancing the user’s movie-watching experience.

📁 Developed and tested in Jupyter Notebook; easy to integrate into a Flask or Streamlit-based web app for deployment.

