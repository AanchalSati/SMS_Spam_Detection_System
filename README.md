# 📩 SMS Spam Detection  

## Overview  
SMS Spam Detection is a machine learning model that takes an SMS as input and predicts whether the message is a **spam** or **not spam** message. The model is built using Python and deployed on the web using Streamlit.  

## 🛠️ Technology Used  
- 🐍 Python  
- 📊 Scikit-learn  
- 🗂️ Pandas  
- 🔢 NumPy  
- 🌐 Streamlit  

## 🌟 Features  
- 📥 Data collection  
- 🧹 Data cleaning and preprocessing  
- 📊 Exploratory Data Analysis  
- 🏗️ Model building and selection  
- 🌐 Web deployment using Streamlit  

### 📥 Data Collection  
The SMS Spam Collection dataset was collected from Kaggle, which contains over 5,500 SMS messages labeled as either spam or not spam.  
👉 You can access the dataset from [here](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset).  

### 🧹 Data Cleaning and Preprocessing  
The data was cleaned by handling null and duplicate values, and the "type" column was label-encoded. The data was then preprocessed by:  
- ✂️ Converting the text into tokens.  
- 🚫 Removing special characters, stopwords, and punctuation.  
- 🔄 Stemming the data.  
- 🔡 Converting the text to lowercase.  

### 📊 Exploratory Data Analysis  
Exploratory Data Analysis was performed to gain insights into the dataset.  
- 📝 The count of characters, words, and sentences was calculated for each message.  
- 🔗 The correlation between variables was calculated.  
- 📈 Visualizations included pyplots, bar charts, pie charts, 5-number summaries, and heatmaps.  
- ☁️ Word clouds were created for spam and non-spam messages.  
- 🔍 The most frequent words in spam texts were visualized.  

### 🏗️ Model Building and Selection  
Multiple classifier models were tried, including:  
- 🧠 Naive Bayes  
- 🌲 Random Forest  
- 🤖 KNN  
- 📏 Decision Tree  
- 🧮 Logistic Regression  
- 🌟 ExtraTreesClassifier  
- ✳️ SVC  

🎯 The best classifier was chosen based on **precision**, achieving **100% precision**!  

### 🌐 Web Deployment  
The model was deployed on the web using Streamlit.  
- 📱 The user interface features a simple input box for entering a message.  
- 📨 The model predicts whether the message is spam or not spam.  

## 🚀 Usage  
To use the SMS Spam Detection model on your own machine, follow these steps:  

1. 📂 Clone this repository.  
2. 📦 Install the required Python packages using:  
   ```bash  
   pip install -r requirements.txt  
3. ▶️ Run the model using:
   ```bash
   streamlit run app.py  
4. 🌐 Visit localhost:8501 on your web browser to access the web app.

### 🤝 Contributions
Contributions to this project are welcome!

- 🐛 If you find any issues or have any suggestions for improvement, please open an issue or a pull request on this repository.








