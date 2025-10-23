# Movie Recommendation System

An intelligent **content-based movie recommendation system** built using **Machine Learning** and **Python**.  
The system suggests similar movies based on user-selected titles by analyzing metadata features such as genres, cast, crew, and plot descriptions.

---

##  Project Overview
This project demonstrates the use of **Natural Language Processing (NLP)** and **similarity-based algorithms** to generate personalized recommendations.  
It implements **content-based filtering** using feature engineering, vectorization, and cosine similarity — forming the core of many modern recommendation engines like Netflix and IMDb.

---

##  Key Highlights
- Developed an end-to-end **recommendation pipeline** from data preprocessing to similarity computation  
- Engineered features combining text and categorical data for enhanced similarity accuracy  
- Implemented **TF-IDF / Count Vectorization** for text vector representation  
- Utilized **Cosine Similarity** to rank and recommend movies  
- Built an **interactive Streamlit web app** for real-time recommendations  
- Optimized runtime with caching and efficient data structures  

---

## Technologies Used
| Category | Tools & Libraries |
|-----------|-------------------|
| Programming Language | Python |
| Libraries | pandas, numpy, scikit-learn, nltk, streamlit |
| ML Techniques | TF-IDF / Count Vectorization, Cosine Similarity |
| Data Source | TMDB Movies Dataset |
| Visualization / Deployment | Streamlit |

---

## Workflow
1. **Data Preprocessing:** Handle missing values, clean text fields, and standardize movie metadata.  
2. **Feature Engineering:** Combine key features (overview, genres, keywords, cast, crew).  
3. **Vectorization:** Convert text data to numerical form using TF-IDF or Count Vectorizer.  
4. **Similarity Computation:** Calculate pairwise cosine similarity between all movies.  
5. **Recommendation Engine:** Retrieve top N most similar movies for any selected title.  
6. **Deployment:** Deployed a Streamlit-based web interface for easy interaction.  

---

##  How to Run
```bash
# Clone the repository
git clone https://github.com/UditHazoary/movie-recommendation-system.git
cd movie-recommendation-system

# Install dependencies
pip install -r requirements.txt

# Run the Streamlit app
streamlit run app.py
