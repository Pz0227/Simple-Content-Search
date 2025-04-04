# AI/Machine Learning Intern Challenge: Simple Content-Based Recommendation

**Deadline**: Sunday, Feb 23rd, 11:59 PM PST

---

## 🌟 Overview

This project is a **content-based movie recommendation system** that suggests the top 5 most relevant movies based on a short user input description. Using **TF-IDF vectorization** and **cosine similarity**, the system compares a user's preferences with movie descriptions and returns the closest matches from a curated dataset of 100 movies.

---

## 📊 Dataset

- **Source**: [IMDb Top 100 Movies](https://www.imdb.com/list/ls053251213/)
- **Content**: Titles, genres, and plot summaries of 100 popular movies.
- The dataset is provided directly in the repository as a CSV file.

---

## 🧠 Approach

1. **Load Dataset**: Import the movie data from CSV.
2. **Text Preprocessing**:
   - Convert to lowercase
   - Remove special characters
   - Tokenize and remove stopwords
3. **Vectorization**:
   - Use **TF-IDF** to convert movie descriptions into feature vectors.
4. **Similarity Calculation**:
   - Compute **cosine similarity** between user input and each movie.
5. **Recommendation Output**:
   - Return the top 5 most similar movie titles along with their IMDb links.

---

## ⚙️ Setup & Running Instructions

1. **Install Jupyter Notebook** (if not already installed):
   ```bash
   pip install jupyterlab
   ```
2. **Open the Notebook**:
   - Run `jupyter lab` or `jupyter notebook` in your terminal.
   - Open the file `Movie_Recommendation.ipynb`.
3. **Run the Notebook**:
   - Execute each cell in order.
   - When prompted, enter a user query describing your movie preferences.

---

## 🎬 Example Query & Output

**User Input**:  
`I love horror movies!`

**Top 5 Recommended Movies**:
- *Dawn of the Dead* — [IMDb](https://www.imdb.com/title/tt0363547/)
- *Tucker and Dale vs Evil* — [IMDb](https://www.imdb.com/title/tt1465522/)
- *Shaun of the Dead* — [IMDb](https://www.imdb.com/title/tt0365748/)
- *Insidious* — [IMDb](https://www.imdb.com/title/tt1591095/)
- *The Mothman Prophecies* — [IMDb](https://www.imdb.com/title/tt0265349/)

---

## 📹 Demo Video

Watch the demo [here](https://youtu.be/0F_FnaNtMWQ) to see how the system works from input to recommendation.
