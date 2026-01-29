# ReelWise – Intelligent movie recommendation system

### Overview  
This project builds a **Movie Recommendation System** using **Collaborative Filtering** based on **Cosine Similarity**. It analyzes user ratings to suggest personalized movie recommendations. 

### Key Steps  
**Data Loading & Preprocessing**  
   - Loaded **ratings.csv** & **movies.csv**  
   - Merged datasets based on `movieId`  
   - Created a **User-Movie rating matrix** 

**Similarity Calculation (Cosine Similarity)**  
   - Computed **User-User similarity** based on ratings  
   - Identified similar users for personalized recommendations  

**Recommendation Generation**  
   - Recommended movies based on similar users' preferences  
   - Suggested **Top 10 unseen movies** for a target user 🎯  

### Project Structure  
```
Movie-Recommendation-System/
│── README.md  # Documentation  
│── Recommendation System.py  # Python script for recommendation  
│── dataset/  
│   ├── ratings.csv  # User ratings dataset  
│   ├── movies.csv  # Movie metadata  
│── results/  
│   ├── user_recommendations.csv  # Generated recommendations  
```  

### Dataset  
**Dataset Source:** [kaggle]  

### Technologies Used  
Python  
Pandas & NumPy (Data Handling)  
Scikit-learn (Cosine Similarity)  

### How to Run the Project?  
#### 1️ Clone the Repository  
```bash
git clone https://github.com/Aishvariyaa/ReelWise.git
cd ReelWise
```  

#### 2️ Install Dependencies  
```bash
pip install -r requirements.txt
```  

#### 3️ Run the Script  
```bash
python Recommendation System.py
```  

### Sample Output  
**Recommended movies for User 5:**  
*Movie 1*  
*Movie 2*  
*Movie 3*  
*Movie 4*  
*Movie 5*  
*Movie 6*  
*Movie 7*  
*Movie 8*  
*Movie 9*  
*Movie 10*  

### Next Steps  
Enhance recommendations using **Matrix Factorization (SVD)**  
Implement a **Content-Based Filtering model**  
Deploy as a **Web App** using Flask or Streamlit  
