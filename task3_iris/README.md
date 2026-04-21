# Task 3: Iris Flower Classification

## 📌 Project Overview
This project focuses on the classic **Iris Flower Dataset**, one of the most famous datasets in machine learning. The goal is to classify Iris flowers into three species (**Setosa**, **Versicolor**, and **Virginica**) based on their sepal and petal measurements.

To go beyond basic classification, this project implements a **Professional Analytics Dashboard** to visualize model decision-making and data clusters in a single, high-definition view.

## 🚀 Key Features
- **Machine Learning Model:** Utilizes a **Random Forest Classifier** for high accuracy and robust prediction.
- **Advanced Preprocessing:** Includes Label Encoding for species and Standard Scaling for feature normalization.
- **Unified Analytics Dashboard:** An interactive HTML-based command center containing:
    - **AI Confusion Matrix:** A heatmap showing the model's accuracy per species.
    - **Feature Importance Analysis:** A bar chart revealing which flower traits (e.g., Petal Width) are most significant.
    - **Species Clustering:** A scatter plot visualizing how species group together based on petal measurements.
    - **Detailed Performance Table:** A breakdown of Precision, Recall, and F1-Scores.

## 📊 Results
- **Model Accuracy:** ~93.3% to 100% (depending on data split).
- **Primary Driver:** Petal Width and Petal Length were identified as the strongest predictors for species identification.



---

## 🛠️ How to Run
1. Ensure you have the required libraries installed:
   ```bash
   pip install pandas numpy scikit-learn plotly
2.Place iris_classification.py and IRIS.csv in the same folder
3.Run the script:python iris_classification.py
4.The dashboard will automatically open in your default web browser as an interactive .html file.

📁 Repository Structure : 
├── Task3_Iris_Classification/
│   ├── iris_classification.py
│   ├── IRIS.csv
│   └── Task3_Final_Dashboard.html (generated after running)

👤 Author
Shyma A
Computer Science Student

---

### 🌟 Final Portfolio Step
Now that you have all 3 tasks finished:
1.  **Main README:** Go to your **main** repository README (the one in the `CodSoft_Internship` root folder).
2.  **Add Task 3:** Add a section for Task 3 so it looks like this:

```markdown
## 📁 Task 3: Iris Flower Classification
* **Goal:** Classify Iris species using Random Forest.
* **Key Features:** Unified Professional Dashboard with Heatmaps and Feature Importance.
* **Location:** `/Task3_Iris_Classification/`
