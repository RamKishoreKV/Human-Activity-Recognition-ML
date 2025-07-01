# Human Activity Recognition using Smartphones 📱🏃‍♂️

This project focuses on predicting human activities from smartphone sensor data (accelerometer & gyroscope) using machine learning techniques. The dataset consists of sensor measurements collected from 30 individuals performing various physical activities.

> 🔬 Lead: **Ram Kishore Karuppiah Nadar Venkateswaran**  
> 👥 Team Members: **Sai Pokuri**, **Krushal Shah**

---

## 📁 Dataset

- **Source**: [UCI HAR Dataset](https://archive.ics.uci.edu/ml/datasets/human+activity+recognition+using+smartphones)
- **Observations**: 10,299
- **Features**: 561
- **Classes**:  
  - WALKING  
  - WALKING_UPSTAIRS  
  - WALKING_DOWNSTAIRS  
  - SITTING  
  - STANDING  
  - LAYING

---

## 🧪 Objectives

- Preprocess the raw sensor data for modeling
- Perform exploratory data analysis (EDA)
- Build and compare multiple ML classifiers (Logistic Regression, SVM, k-NN)
- Evaluate models using accuracy and confusion matrix

---

## 📊 Exploratory Data Analysis (EDA)

### 📌 Sensor Importance
![Sensor Importance](./vis%20images/Sensor%20importance.png)

### 📌 Data Provided by Each User
![User Distribution](./vis%20images/Dataprovidedbyeachuser.png)

### 📌 Activity vs Body Angle
![Activity vs Body Angle](./vis%20images/activity%20vs%20body%20angle.png)

### 📌 Battery vs Activities (Proxy)
![Accelerometer Boxplots](./vis%20images/accelerometer%20bodyplots.png)

### 📌 Clustering of Activities
![Clustering](./vis%20images/clustering.png)

---

## 🧠 Models Used

| Algorithm              | Description                      | Performance         |
|------------------------|----------------------------------|---------------------|
| **Logistic Regression**| Baseline linear classifier       | ⭐ Best performer    |
| **Support Vector Machine (SVM)** | Handles complex margins     | Good                |
| **k-Nearest Neighbors (k-NN)**   | Distance-based non-parametric model | Moderate        |

---

## 📉 Confusion Matrix (Best Model – Logistic Regression)

![Confusion Matrix](./vis%20images/confusion%20matrix.png)

---

## ⚙️ Tools & Technologies

- **Python**: `Pandas`, `NumPy`, `Matplotlib`, `Scikit-learn`
- **Jupyter Notebook** (Colab)
- Git & GitHub for version control
- Manual data balancing and EDA scripting

---

## 🏆 Exceptional Contributions

- Created a clean end-to-end ML pipeline from scratch
- Implemented and compared 3 classical algorithms with insight-focused evaluation
- Handled missing values, class imbalance, and multivariate visualizations
- Led by Ram Kishore, including final integration and reporting

---

## 📂 Project Structure
├── main.ipynb  
├── train.csv  
├── test.csv  
├── DSCI631_ProjectReport.pdf  
├── vis images/                  # Contains EDA + Confusion Matrix images  
│   ├── Sensor importance.png  
│   ├── Dataprovidedbyeachuser.png  
│   ├── activity vs body angle.png  
│   ├── confusion matrix.png  
│   ├── accelerometer bodyplots.png  
│   └── clustering.png  
└── README.md  


## 🙌 Acknowledgements

- Thanks to [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/human+activity+recognition+using+smartphones) for the dataset.
- Special thanks to team members **Sai Pokuri** and **Krushal Shah** for contributing to model experimentation and documentation.
- Project led and fully implemented by **Ram Kishore KV**.

---

## 🚀 How to Run

1. Clone this repo:

```bash
git clone https://github.com/RamKishoreKV/Human-Activity-Recognition-ML.git

