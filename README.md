# 💻 Laptop Price Prediction - Data Modeling Project

This project explores a dataset of laptops to model and predict pricing based on various specifications (e.g., screen resolution, processor, RAM). The notebook includes data preprocessing, exploratory visualizations, and machine learning using a Random Forest Regressor.

## 📂 Dataset
The dataset used (`laptop-clean.csv`) contains attributes like:
- Brand
- Processor
- RAM
- Screen Resolution
- Screen Type
- GPU/Storage
- Price (Target)

## 🔧 Features & Processing
- Extracted numeric screen resolution and screen type from combined text
- Handled categorical and continuous variables
- Created plots (boxplots, histograms, linear regression) to visualize trends

## 🧠 Model
- Used **RandomForestRegressor** from `sklearn.ensemble`
- Trained and evaluated using **Mean Squared Error**
- Feature importance analysis could be added (future improvement)

## 🖥️ Tools Used
- Python
- Pandas, NumPy
- Seaborn, Matplotlib
- scikit-learn

## 📈 Results
Model trained on preprocessed features; specific metrics and insights are shown in the notebook.


## ✍️ Author
**Tonie Enriquez Caponpon**  
[LinkedIn](https://www.linkedin.com/in/tonie-caponpon-95131b235/) | [GitHub](https://github.com/ToniEnriquez)
