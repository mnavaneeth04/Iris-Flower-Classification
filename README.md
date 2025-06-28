# 🌸 Iris Flower Classification using Logistic Regression

This repository contains the code and workflow for a machine learning project that classifies Iris flower species using the classic Iris dataset. The model is built using **Logistic Regression**, a simple yet effective classification algorithm.

---

## 📝 Description

The goal of this project is to classify Iris flowers into one of three species:

- Setosa  
- Versicolor  
- Virginica  

based on four input features:

- Sepal Length  
- Sepal Width  
- Petal Length  
- Petal Width  

The project follows a standard machine learning pipeline including **data loading**, **exploratory data analysis**, **model training**, and **evaluation**.

The implementation is done in **Python** using a **Jupyter Notebook**, with help from the following libraries:

- **Pandas, NumPy** for data handling  
- **Seaborn, Matplotlib** for data visualization  
- **Scikit-learn** for model building and evaluation  

---

## 📊 Project Workflow

1. **Data Loading**  
   Load the Iris dataset from `sklearn.datasets`.

2. **Data Exploration**  
   Understand class distribution, view sample records, and use pair plots and histograms to visualize relationships.

3. **Preprocessing**  
   Split the data into training and testing sets.

4. **Modeling**  
   Train a **Logistic Regression** model using `sklearn.linear_model`.

5. **Evaluation**  
   Measure model performance using:
   - Accuracy score  
   - Confusion matrix  
   - Classification report  

---

## 🛠️ Technologies Used

- Python  
- Jupyter Notebook  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  

---

## 📈 Results

- **Model Used**: Logistic Regression  
- **Test Accuracy**: ~95–98% (varies slightly with split)  
- The model performs well in separating all three Iris species with high precision and recall.

---

## 🔮 Future Enhancements

- Test additional classifiers like Decision Tree, SVM, or KNN  
- Apply cross-validation for more robust accuracy  
- Deploy the model using **Streamlit** or **Flask** with a simple UI for user input

---

## 🙌 Acknowledgements

- [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/iris)  
- Scikit-learn developers and open-source contributors  
