# 📊 Sentiment Analysis System

## 📌 Overview
The **Sentiment Analysis System** is a full-stack application designed to analyze customer product reviews and classify them into **positive**, **negative**, or **neutral** sentiments.  
The goal of this project is to help companies understand customer emotions at scale, identify patterns in feedback, and improve product quality based on real user opinions.

This project was built using a provided dataset of customer reviews and applies **Natural Language Processing (NLP)** and **Machine Learning** techniques to perform sentiment classification.

---

## 🎯 Objectives
- Classify customer reviews into sentiment categories  
- Analyze the distribution of customer emotions  
- Help businesses make data-driven product improvements  
- Demonstrate practical application of NLP and ML concepts  

---

## ✨ Features
- Preprocessing of raw customer review data  
- Sentiment classification into **Positive / Negative / Neutral**  
- Backend logic for data processing and prediction  
- Frontend interface for displaying results  
- Dataset-driven analysis for real-world relevance  

---

## 🧠 Tech Stack

### Backend
- **Python**
- **Machine Learning & NLP**
  - Pandas
  - Scikit-learn
  - NLP preprocessing techniques

### Frontend
- **HTML**
- **CSS**
- **JavaScript**

### Data
- CSV dataset containing customer product reviews

---

## 📂 Project Structure
SentimentAnalysis/
├── back end/ # Backend ML & NLP logic
├── front-end/ # Frontend UI
├── redmi6.csv # Sample dataset (product reviews)
├── render.yaml # Deployment configuration
├── README.md # Project documentation


---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/VarshiniNeralla/SentimentAnalysis.git
cd SentimentAnalysis
2️⃣ Backend Setup
cd back\ end
python -m venv venv
.\venv\Scripts\activate     # Windows
pip install -r requirements.txt
3️⃣ Frontend Setup
cd ../front-end
npm install
4️⃣ Run the Application
Start the backend server

Run the frontend application

Access the application through the configured local host port

🔄 Workflow
Load customer review dataset (CSV)

Clean and preprocess textual data

Apply sentiment classification model

Categorize reviews as positive, negative, or neutral

Display sentiment insights through the frontend

📈 Use Cases
Product review analysis

Customer feedback monitoring

Market sentiment understanding

Business intelligence support
