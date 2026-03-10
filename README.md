# 🎬 Movie Recommendation System

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-lightgrey.svg)

## 📌 Overview
This project is a Machine Learning-based **Content-Based Movie Recommendation System**. By analyzing textual data such as movie genres, keywords, and plot overviews, the system calculates the similarity between different films and recommends a list of movies that closely match the user's input.

## ✨ Features
* **Content-Based Filtering:** Recommends movies based on their actual content (plot, genre, keywords) rather than user ratings.
* **TF-IDF Vectorization:** Converts raw text data into meaningful numerical representations.
* **Cosine Similarity:** Accurately calculates the closeness between different movie profiles to generate top recommendations.
* **Data Visualization:** Generates beautiful WordClouds to visualize the most prominent themes and words across the dataset.
* **Interactive Notebook:** Easy-to-follow Jupyter Notebook with step-by-step execution.

## 🛠️ Tech Stack & Libraries
* **Language:** Python 3
* **Data Manipulation:** `pandas`, `numpy`
* **Machine Learning:** `scikit-learn` (`TfidfVectorizer`, `cosine_similarity`)
* **Natural Language Processing (NLP):** `nltk`, `re`
* **Data Visualization:** `matplotlib`, `wordcloud`

## 📂 Dataset
The system uses a dataset named `movies.csv` (approx. 4,800 movies). 
The following columns are actively filtered and combined to train the model:
* `title`: The name of the movie.
* `genres`: The categories the movie falls under (e.g., Action, Sci-Fi).
* `keywords`: Tags describing the movie's themes.
* `overview`: A brief summary/synopsis of the plot.

## 🚀 Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/your-username/movie-recommendation-system.git](https://github.com/your-username/movie-recommendation-system.git)
   cd movie-recommendation-system

   Install the required dependencies:
Ensure you have Python installed. You can install the required libraries using pip:

Bash
pip install nltk scikit-learn numpy pandas matplotlib wordcloud
Run the Notebook:
Launch Jupyter Notebook in your terminal:

Bash
jupyter notebook
Open Movie_recommendation_system.ipynb and run the cells sequentially.

💡 Usage
Execute all the cells in the notebook to load the data, train the TF-IDF Vectorizer, and build the similarity matrix.

Scroll to the recommendation execution cell.

Enter your favorite movie title into the movie_name variable (e.g., movie_name = "Avatar").

Run the cell to get a ranked list of similar movie recommendations!

🤝 Contributing
Contributions, issues, and feature requests are welcome!
If you have any ideas to improve the accuracy (such as integrating a collaborative filtering approach to create a hybrid system), feel free to fork the repository and submit a pull request.