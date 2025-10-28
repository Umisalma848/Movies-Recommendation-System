# 🎬 Movie Recommendation System

## 📘 Project Overview  
This project builds a **Movie Recommendation System** using the **TMDB 5000 Movies Dataset**.  
It recommends movies similar to a given title based on metadata such as **genres, keywords, cast, and crew**, using **content-based filtering** and **cosine similarity**.

---

## 📂 Dataset  
Dataset used: **The Movie Database (TMDB)**  
- `tmdb_5000_movies.csv`  
- `tmdb_5000_credits.csv`  

Contains details like movie titles, genres, keywords, cast, crew, budget, revenue, and popularity.

---

## 🧠 Objective  
To recommend similar movies by analyzing textual features from movie metadata.

---

## 🧩 Key Concepts and Steps  

1. **Data Preparation:** Load and merge movie and credit datasets, remove unnecessary columns, handle missing data.  
2. **Feature Selection:** Keep key fields — `title`, `overview`, `genres`, `keywords`, `cast`, `crew`.  
3. **Text Processing:** Combine these fields into a single `tags` column for each movie.  
4. **Vectorization:** Convert text to numerical vectors using `CountVectorizer`.  
5. **Similarity Measurement:** Use **cosine similarity** to find top 5 similar movies for any given title.  

---

## 🚀 Example Output  
Input: **“Avatar”**  
Output:
- Guardians of the Galaxy
- Star Trek
- Star Wars: The Force Awakens
- The Fifth Element
- John Carter
---

## 🛠️ Technologies Used  
- **Python** 🐍  
- **Pandas**, **NumPy**  
- **Scikit-learn**  
- **Matplotlib**, **Seaborn**  
- **Jupyter Lab**

---

## 🌟 Future Enhancements  
- Build an interactive **Streamlit** or **Flask** web app.  
- Add a **hybrid recommendation** system using ratings.  
- Use **TF-IDF** for better text weighting.  
- Apply **ANN** (Approximate Nearest Neighbors) for scalability.

---

## 👩‍💻 Author  
**Umi Salma**  
🔗 [Linkedin ](https://www.linkedin.com/in/umi-salma-a7066a353/) 
