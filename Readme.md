# 🎬 Movie Recommendation System

A **Content-Based Movie Recommendation System** built using **Python** and **Natural Language Processing (NLP)** techniques.  
This project analyzes movie metadata and recommends similar movies based on their genres and descriptions.

---

## 🚀 Features

- 📊 **Data Analysis**  
  Exploratory analysis of movie and rating datasets.

- 📈 **Data Visualization**  
  Word Clouds to highlight popular genres and frequently occurring movie terms.

- 🤖 **Recommendation Engine**  
  Recommends movies using **TF-IDF Vectorization** and **Cosine Similarity**.

---

## 🛠️ Technologies Used

- **Python** – Core programming language  
- **Pandas** – Data manipulation and analysis  
- **Matplotlib** – Data visualization  
- **WordCloud** – Text-based visualizations  
- **Scikit-learn**
  - `TfidfVectorizer` for feature extraction  
  - `linear_kernel` for similarity computation  

---

## 📊 Dataset

The project uses two datasets:

### 📁 movies.csv
Contains:
- `movieId`
- `title`
- `genres`  
  *(Example: Adventure | Animation | Comedy)*

### 📁 ratings.csv
Contains:
- `userId`
- `movieId`
- `rating`
- `timestamp`

---

## ⚙️ How It Works

### 1️⃣ Data Preprocessing
- Cleans movie titles  
- Splits genres into readable text format  
- Prepares metadata for NLP processing  

### 2️⃣ Feature Extraction
- Builds a **TF-IDF matrix** using movie genres and titles  
- Converts text data into numerical vectors  

### 3️⃣ Similarity Calculation
- Uses **Cosine Similarity** to measure closeness between movies  

### 4️⃣ Recommendation
- Given a movie title, returns the **Top-N most similar movies**

---

## 💻 Usage

### Prerequisites
Ensure `movies.csv` and `ratings.csv` are present in the project directory.

### Install Required Libraries
```bash
pip install pandas matplotlib wordcloud scikit-learn

