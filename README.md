# 🎬 Movie Recommendation System  

A Python mini project that recommends movies based on similarity in genres, keywords, and descriptions using **content-based filtering**.  

## 🔹 Tech Stack  
- Python  
- Pandas, NumPy  
- Scikit-learn  

## 📌 Features
- Content-based movie recommendations
- TF-IDF Vectorization
- Cosine Similarity

## 🚀 How to Run  
1. **Clone the repository**  
```bash
git clone https://github.com/raajitha6/movie-recommendation-system.git
cd movie-recommendation-system
```
2. **Install required libraries**
```bash
pip install pandas numpy scikit-learn
```
3. **Run in Jupyter Notebook**
```bash
jupyter notebook movie-recommendation-system.ipynb
```
## 💡 How It Works  

1. Load and preprocess the dataset  
2. Combine features like genres, keywords, and descriptions  
3. Convert text data into numerical vectors using **TF-IDF**  
4. Calculate similarity between movies using **Cosine Similarity**  
5. Recommend the most similar movies to the user’s choice  
