# GrothLink_ML_Projects
 
# 📩 SMS Spam Detection

## 🔍 Project Overview
This project is a **Machine Learning-based SMS Spam Detection System** that classifies messages as **Spam** or **Ham (Not Spam)** using Natural Language Processing (NLP) techniques. It utilizes **NLTK for text preprocessing** and **ML algorithms for classification**.

## 🚀 Features
- Detects whether an SMS is **spam or legitimate**
- Uses **TF-IDF vectorization** for text representation
- Implements **Random Forest / Naïve Bayes / SVM and many Machine Learning Algorithms** for classification
- **Streamlit UI** for easy user interaction
- **Deployed on Localhost / Cloud**

## 📂 Dataset
- The dataset used is a labeled SMS dataset containing **spam and ham messages**.
- Source: [UCI Machine Learning Repository](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset)

## 🛠 Installation
### 1️⃣ **Clone the Repository**
```sh
git clone https://github.com/vishwakarma9470/sms-spam-detection.git
cd sms-spam-detection
```

### 2️⃣ **Create & Activate Virtual Environment**
```sh
python -m venv myenv
source myenv/bin/activate  # Mac/Linux
myenv\Scripts\activate  # Windows
```

### 3️⃣ **Install Dependencies**
```sh
pip install -r requirements.txt
```

### 4️⃣ **Run the Application**
```sh
streamlit run app.py
```

## 🧑‍💻 Technologies Used
- **Python** 🐍
- **NLTK** (Natural Language Toolkit) 📖
- **Scikit-Learn** 🤖
- **Pandas & NumPy** 📊
- **Streamlit** (for UI) 🖥

## 📊 Model & Evaluation
|Algorithm |Accuracy |Precision|
|----------|---------|----------|
|NB 	| 0.970986 | 1.000000 |
|RF     | 0.973888 | 0.98260 |
|SVC    | 0.975822 | 0.974576 |
|xgb    | 0.965184 | 0.939655 |
|GBDT    | 0.950677 | 0.930693 |
|BgC 	| 0.958414 | 0.868217 |
|DT 	| 0.930368 |  0.830000 |
|AdaBoost | 0.921663 | 0.820225 |
 
## 🏆 Results
- Achieved **high accuracy (>98%)** in detecting spam messages
- Optimized model to **reduce false positives**

## 📝 Future Enhancements
- Deploy on **Heroku / AWS**
- Add support for **multilingual spam detection**
- Improve accuracy using **Deep Learning (LSTM / Transformers)**

## 📜 License
This project is licensed under the **MIT License**.

---
✉ **For any queries, contact:** [mv947027@gmail.com] | GitHub: [https://github.com/vishwakarma9470/sms-spam-detection.git]



