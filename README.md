
# Movie-Recommendation-System

**Description:**

This repository implements a movie recommendation system designed to suggest personalized movie choices for users. It leverages the power of Jupyter Notebook, a popular data science environment, and employs Natural Language Processing (NLP) techniques to analyze movie descriptions.

**Key Features:**

**Jupyter Notebook Environment:** The entire system is built within a Jupyter Notebook, making it interactive and easy to understand. You can follow the code step-by-step and customize the analysis.

**NLP Preprocessing with TF-IDF:** The system utilizes TF-IDF (Term Frequency-Inverse Document Frequency) to transform textual movie descriptions into numerical representations. This process captures the importance of words within a movie description and across the entire dataset, leading to a more meaningful understanding of movie content.

**Inverse Cosine Similarity:** After preprocessing, the system calculates the similarity between movies using inverse cosine similarity. This method effectively measures the semantic relationships between movies based on their processed descriptions, going beyond simple keyword matching.

**Customizable Python Recommendation Function:** Within the Jupyter Notebook, a Python function takes user preferences (textual descriptions or keywords) and recommends similar movies using the calculated cosine similarities. You can easily modify this function to explore different recommendation strategies.

## Run Locally

Clone the project

```bash
  git clone https://github.com/Sohan411/Movie-Recommendation-System.git
```

Go to the project directory

```bash
  cd Movie-Recommendation-System
```

Install dependencies

```bash
  pip install pandas scikit-learn
```

**Running the Recommendation System:**

**Open the Jupyter Notebook:** Navigate to the directory containing the notebook file (e.g., movie_recommendation.ipynb) and open it in your preferred Jupyter Notebook environment.

**Run the Cells:** Execute the cells in the notebook sequentially using the "Run" menu or keyboard shortcuts. These cells will perform the data loading, preprocessing, similarity calculations, and recommendation generation.

**Provide User Preferences:** Follow the instructions within the notebook to specify your movie preferences in the designated cell (e.g., a text description of desired movie characteristics). The notebook will likely provide an example for reference.

**View Recommendations:** The notebook will display the recommended movies based on your preferences, along with their cosine similarity scores for transparency.


## Additional Information

The Jupyter Notebook might include visualizations of the TF-IDF results or the distribution of cosine similarity scores. These can provide insights into the system's behavior.

Consider mentioning any assumptions made about the movie data or potential limitations of the current system.
You might suggest potential future extensions, such as incorporating user ratings, genre information, or movie trailers into the recommendation process.

