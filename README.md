---

# 🎬 Movie Recommendation System

A **Machine Learning based Movie Recommendation System** that recommends movies similar to a selected movie using **TF-IDF and cosine similarity**.

The app is built with **Python and Streamlit**, and it uses movie metadata to generate recommendations.

---

## 🚀 Features

* 🎥 Search for a movie
* 🤖 Get similar movie recommendations
* 📊 Uses **TF-IDF vectorization** for text features
* ⚡ Fast recommendations using precomputed similarity
* 🖥️ Simple interactive UI with **Streamlit**

---

## 🛠️ Tech Stack

* **Python**
* **Streamlit**
* **Pandas**
* **Scikit-learn**
* **NumPy**

---

## 📂 Project Structure

```
movie-recommendation-system
│
├── app.py                 # Streamlit web app
├── main.py                # Recommendation logic
├── movies.ipynb           # Model building notebook
│
├── movies_metadata.csv    # Movie dataset
│
├── tfidf.pkl              # TF-IDF vectorizer
├── tfidf_matrix.pkl       # TF-IDF matrix
├── df.pkl                 # Processed dataframe
├── indices.pkl            # Movie indices
│
├── requirements.txt       # Dependencies
├── runtime.txt            # Runtime configuration
└── .gitignore
```

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/movie-recommendation-system.git
cd movie-recommendation-system
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the App

Start the Streamlit application:

```bash
streamlit run app.py
```

Open in browser:

```
http://localhost:8501
```

---

## 🧠 How It Works

1. Movie metadata is loaded from `movies_metadata.csv`
2. Text features are converted using **TF-IDF Vectorizer**
3. A **similarity matrix** is generated
4. When a movie is selected, the system recommends the **most similar movies**

---

## 📜 License

MIT License

---

If you want, I can also make a **much better GitHub README (with badges, screenshots, demo GIF, and architecture diagram)** which looks **very impressive for portfolio projects**.
