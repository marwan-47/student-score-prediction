#  Student Exam Score Prediction

This project builds and evaluates multiple machine learning models to predict students' final exam scores based on various academic, behavioral, and demographic features. The dataset includes factors like hours studied, sleep, attendance, parental involvement, school type, and more.

---

##  Problem Statement

Can we accurately predict a student’s **final exam score** using features like study habits, family background, and school environment?

---

##  Technologies Used

- Python 3.x  
- NumPy, Pandas  
- Matplotlib, Seaborn  
- Scikit-learn (LinearRegression, Ridge, Lasso, ElasticNet, SVR, GradientBoosting, etc.)   
- GridSearchCV for hyperparameter tuning  

---

##  Notebook Highlights

 **Data Preprocessing**
- Handled categorical data using Label Encoding  
- Splitting dataset into features (`X`) and target (`y`)  
- Train/test splitting and scaling  

 **Model Training & Evaluation**
- **Linear Regression**
- **Polynomial Regression**
- **Regularized Models**: Ridge
- Evaluated using RMSE and R² score  

 **Hyperparameter Tuning**
- Used `GridSearchCV` to find best parameters for all models  
- Compared performance and selected the best model  

 **Visualization**
- Scatter plots of predicted vs actual scores  
- Regression line and error plots  
- Model performance comparisons  

---

##  Performance Metrics

All models were evaluated using:

- **RMSE** (Root Mean Squared Error) – how far predictions are from actual scores  
- **R² Score** – how much variance in scores the model explains  

---

##  How to Run

1. Clone this repo or download the notebook.
2. Install required packages:
   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn 
   ```
3. Run the notebook:
   ```bash
   jupyter notebook student-score-prediction.ipynb
   ```

---

##  Contact

**Marwan Ahmed**  
 marwanhassen999@gmail.com  
 [LinkedIn](https://www.linkedin.com/in/marwan0/)

---

>  Built for learning. Tuned for performance. Designed to help predict academic success!
