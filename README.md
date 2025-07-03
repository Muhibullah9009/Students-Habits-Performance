# 📚 Student Habits vs Academic Performance Prediction

This data science project explores how different student habits influence academic performance. It involves dataset cleaning, feature analysis, and building a machine learning model to predict student grades or performance levels based on lifestyle choices and study patterns.

## 📊 Dataset
- **Source:** Kaggle — `student-habits-vs-academic-performance`
- **Target Variable:** Student Academic Performance / Grades
- **Features:** Includes study time, sleep habits, internet usage, alcohol consumption, health status, family support, and more.

## 🔍 Key Steps
1. **Data Acquisition**
   - Dataset downloaded from Kaggle and extracted
   - Initial data inspection

2. **Data Preprocessing**
   - Handling missing/null values
   - Encoding categorical variables
   - Normalization or standardization of numerical features

3. **Model Building**
   - Regression or classification models (based on the target)
   - Example: Random Forest, Decision Tree, etc.
   - Train-Test Split (e.g., 80/20)

4. **Evaluation**
   - Metrics used: MAE, MSE, RMSE, R² Score
   - Visualization of prediction vs actual performance

## 🧠 Libraries Used
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn

## 📈 Model Performance
- The model was evaluated using regression metrics.
- Performance depends on the chosen algorithm and preprocessing strategy.

## 📌 How to Run
1. Download the `.ipynb` notebook file.
2. Make sure you have Kaggle CLI configured and authenticated.
3. Run the notebook in Jupyter Notebook or Google Colab.
4. Install dependencies:
   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn kaggle

🤝 Contributions
Feel free to fork this project, enhance visualizations, or try out other models like XGBoost, Linear Regression, or SVR.

⚠️ Disclaimer
This project is for educational purposes only. The dataset and model may not generalize to other student populations or academic systems.