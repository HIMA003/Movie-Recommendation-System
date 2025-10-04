
# 🎬 Movie Recommendation System  

This project implements a **Movie Recommendation System** using **Collaborative Filtering techniques** on the [MovieLens 100k Dataset](https://www.kaggle.com/datasets/prajitdatta/movielens-100k-dataset). The system predicts user preferences and provides personalized movie suggestions based on their historical ratings.  

---

## 📌 Project Overview  
Recommender systems are widely used by streaming platforms (e.g., Netflix, YouTube, Spotify) to improve user experience.  
In this project, we:  
- Built a **User–Item Rating Matrix**.  
- Applied **Collaborative Filtering algorithms** (SVD, KNN).  
- Evaluated models using **RMSE** and **MAE**.  
- Generated **personalized recommendations** for users.  

---

## ⚙️ Tech Stack  
- **Programming Language:** Python 🐍  
- **Libraries & Tools:**  
  - Pandas, NumPy (Data Handling)  
  - Matplotlib, Seaborn (Visualization)  
  - Scikit-learn (Model Support)  
  - Surprise (Recommendation Algorithms)  

---

## 📊 Dataset  
**MovieLens 100k** dataset contains:  
- `ratings.csv`: User ratings (userId, movieId, rating, timestamp)  
- `movies.csv`: Movie details (movieId, title, genres)  

**Stats:**  
- 100,000 ratings  
- 943 users  
- 1,682 movies  

---

## 🚀 Implementation Steps  
1. **Data Loading & Exploration**  
   - Loaded ratings and movies dataset.  
   - Explored data distribution and rating frequencies.  

2. **User–Item Matrix Creation**  
   - Constructed a sparse matrix (users × movies).  
   - Visualized sparsity.  

3. **Collaborative Filtering Models**  
   - **SVD (Singular Value Decomposition)**  
   - **KNN (User-based & Item-based)**  

4. **Evaluation**  
   - Metrics: RMSE, MAE.  
   - Compared algorithms and selected the best-performing one.  

5. **Recommendation Generation**  
   - Predicted unseen ratings for each user.  
   - Recommended **Top-N movies** tailored to user preferences.  

---

## 📈 Results  
- **SVD** achieved the best accuracy (lowest RMSE & MAE).  
- System successfully recommended movies such as:  
  - *Star Wars (1977)*  
  - *The Godfather (1972)*  
  - *Toy Story (1995)*  
- Demonstrated effectiveness of collaborative filtering on sparse datasets.  

---

## 📷 Visualizations (in notebook)  
- Sparsity heatmap of User–Item Matrix.  
- Rating distribution histogram.  
- Model performance comparison chart.  
- Sample user recommendations table.  

---

## 🙏 Acknowledgment  
Special thanks to **[Company Name]** for supporting me in exploring and building this project.  

---

## 🔮 Future Improvements  
- Add **content-based filtering** to enrich recommendations.  
- Deploy the system as a **web app** (Streamlit/Flask).  
- Experiment with **hybrid recommendation systems**.  

---

## 🏁 How to Run  
1. Clone this repository:  
   ```bash
   git clone https://github.com/your-username/movie-recommendation-system.git
   cd movie-recommendation-system
   ```
2. Install dependencies:  
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook:  
   ```bash
   jupyter notebook movie_recommendation_system.ipynb
   ```

---

✨ This project showcases the power of recommender systems and their role in enhancing personalized user experiences.  
