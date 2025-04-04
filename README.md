# AI/Machine Learning Intern Challenge: Simple Content-Based Recommendation

**Deadline**: Sunday, Feb 23th 11:59 pm PST

---

## Overview

The current program is a **content-based movie recommendation system** that, given a **short text description** in **English** of a user’s preferences, suggests top 5 **similar items** from a small dataset which has 100 movies. The system uses **TF-IDF vectorization** and **cosine similarity** to compare the user's query with movie overviews and return the most relevant recommendations.

---

1. **About Dataset**  
The dataset used in this project is **Top 100 Movies Dataset** from [IMDB](https://www.imdb.com/list/ls053251213/). The dataset contains information about movies including their genres and titles, which will be used for similarity comparison.

2. **Approach**  
- ***Load the dataset*** - Read the movie data from a CSV file.
- ***Preprocess the text*** - Clean movie descriptions by converting text to lowercase, removing special characters, tokenize words, and remove stopwords.
- ***Convert text into numerical vectors*** - Use TF-IDF to transform text descriptions into numerical format.
- ***Compute similarity and Return top 5 recommendations*** - Calculate cosine similarity between the user query and all movie descriptions, and retrieve the most relevant movie titles.

3. **Setup Instruction**  
- Since this project is programed using Jupyter Notebook ```(.ipynb)```, install the required libraries directly using the following command: ```pip install jupyterlab```

- Open Jupyter Notebook.
- Load and run all cells sequentially.
- Enter a user input query about movie preference when prompted.

5. **Demonstrating video** 

Here is a short [video demo](https://youtu.be/0F_FnaNtMWQ) of how to run the program. 

6. **Example Output**

When typed a user movie preference:  I love horror movies! 

Outputs of top 5 recommended movies and links to get access to them will be printed as: 

- 'Dawn of the Dead', 'https://www.imdb.com/title/tt0363547/'
- 'Tucker and Dale vs Evil', 'https://www.imdb.com/title/tt1465522/'
- 'Shaun of the Dead', 'https://www.imdb.com/title/tt0365748/'
- 'Insidious', 'https://www.imdb.com/title/tt1591095/'
- 'The Mothman Prophecies', 'https://www.imdb.com/title/tt0265349/'

---
**Salary Expectation Per Hour**

15-30$/hr for the internship.
