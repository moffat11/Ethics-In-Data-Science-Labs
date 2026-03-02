# Applied Machine Learning & Data Ethics (CMPUT 200)

## 📌 Overview
This repository contains a collection of data science and machine learning labs completed as part of **CMPUT 200: Ethics in Data Science and AI** at the **University of Alberta**. 

The goal of this project is to demonstrate a strong foundational understanding of data manipulation, exploratory data analysis (EDA), statistical probability, and predictive modeling. Beyond just technical implementation, these labs emphasize analyzing real-world datasets (such as global demographics and child mortality) to better understand the ethical implications and societal impacts of data.

## 🛠️ Technical Skills & Tools Stack
* **Languages:** Python 3
* **Data Manipulation:** `pandas`, `numpy`
* **Data Visualization:** `matplotlib.pyplot`, `seaborn`
* **Machine Learning:** `scikit-learn` (Pipelines, Logistic Regression, Linear Regression, Data Scaling)
* **Model Evaluation:** Confusion Matrices, Precision/Recall, F1-Scores
* **Environment:** Jupyter Notebooks (Syzygy)

---

## 🔬 Lab Breakdown & Highlights

### [Lab 1 & 2: Data Science Foundations & Probability](./Labs/L2/L2.ipynb/)
* **Concepts Explored:** Data manipulation, filtering, and aggregation. Simulated probabilities and analyzed statistical distributions (Uniform, Normal, Binomial) using Python logic and arrays.
* **Technical Highlights:** Generated histograms to analyze skewed data and compared metric distributions across different demographic groups.

### [Lab 3: Applied Socio-Economic Analysis](./Labs/L3/L3.ipynb/)
* **Concepts Explored:** Merged multiple real-world datasets (UN Population, Fertility, and Child Mortality) to identify macro-trends. 
* **Technical Highlights:** Built custom functions to visualize longitudinal data and generated scatter plots to analyze the correlation between global fertility rates and child mortality over a 50-year span.

### [Lab 4: Linear Regression](./Labs/L4/L4.ipynb/)
* **Concepts Explored:** Predictive modeling using historical family height data (Galton's dataset). 
* **Technical Highlights:** Instead of using black-box libraries, I implemented functions to calculate standard deviation, means, correlation coefficients ($r$), and standard units (SU) from scratch. Used these mathematical foundations to manually calculate the slope and y-intercept for a linear regression line to predict continuous outcomes.
* **Visuals:**
* <img width="1137" height="449" alt="image" src="https://github.com/user-attachments/assets/3829d61e-5b20-4664-a555-d487aa4df192" />


### [Lab 5: Logistic Regression & ML Pipelines](./Labs/L5/L5.ipynb/)
* **Concepts Explored:** Categorical classification using the Iris dataset. 
* **Technical Highlights:** Split data into training and testing sets to prevent model overfitting. Built a `scikit-learn` **Pipeline** integrating `StandardScaler` for feature normalization and `LogisticRegression` for classification. Evaluated model performance using a Confusion Matrix and a comprehensive Classification Report (Precision, Recall, F1-score).
* **Visuals:**
* <img width="641" height="545" alt="image" src="https://github.com/user-attachments/assets/8b378e95-bcee-4630-a908-c5621a4212df" />
* <img width="440" height="185" alt="image" src="https://github.com/user-attachments/assets/ad73bf28-8b74-4e8a-bffa-7dfaae56085e" />



---

## 🚀 How to Run the Notebooks
1) To run these notebooks locally, ensure you have Python installed along with the following libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

2) Clone the repository.

3) Ensure the associated .csv datasets are in the same root directory.

4) Launch Jupyter Notebook or JupyterLab and run the cells sequentially.

⚖️ Academic Integrity Disclaimer

These notebooks represent my personal coursework and solutions for CMPUT 200 at the University of Alberta. They are provided here strictly for portfolio and demonstration purposes. Current students should not copy or use this code for their own assignments, as doing so violates the University's Code of Student Behaviour.
