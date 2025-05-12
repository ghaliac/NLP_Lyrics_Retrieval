# 🎵 Lyrics Retrieval System

An intelligent lyrics retrieval engine developed as part of the AI Master's program at Télécom Paris.

## 📌 Objective

Build a system capable of retrieving the most similar paragraph of lyrics to a user query from a large dataset of over **2 million songs**.

## ⚙️ Methodology

1. **Text Preprocessing**
   - Removal of HTML tags and punctuation
   - Lowercasing, line normalization, and paragraph segmentation

2. **Efficient Candidate Filtering**
   - Fast filtering based on the number of words per line
   - Vector representations generated using **TF-IDF** and **Word2Vec**

3. **Similarity Search**
   - Distance metrics: Euclidean and Cosine
   - Configurable thresholding for optimal retrieval
   - Time-efficient nearest neighbor search

4. **Evaluation**
   - Quantitative analysis of retrieval performance
   - Distance comparisons between ground truth and retrieved lyrics

## 🛠️ Technologies

**Programming language:** Python 3.10
  - **Data manipulation:** Pandas, NumPy
  - **Machine learning & vectorization:** scikit-learn, Gensim
  - **Text processing:** BeautifulSoup, regular expressions
  - **Project management:** Poetry (dependency and environment management)


