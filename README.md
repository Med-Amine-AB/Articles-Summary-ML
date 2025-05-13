# 🧠 AutoTextSummarizer - AI-Based Text Summarization App

## 📌 Overview

In a world overwhelmed by digital content, reading long articles and blog posts can be time-consuming. This project presents a solution: an intelligent text summarization system based on Machine Learning that generates clear and concise summaries from long texts.

Developed entirely by me, this application combines powerful NLP models, data processing, and a modern user interface to help users digest information faster and more efficiently.

---

## 🚀 Features

- Summarizes long texts using extractive and abstractive techniques
- Models: TextRank, GRU (RNN), T5-small (Hugging Face Transformers)
- Web app with a simple, modern UI built using **Flutter** (not pushed)
- Fast and lightweight Flask backend (not pushed)
- Automatic preprocessing and text cleaning
- Supports user input or bulk text summarization from files

---

## 🛠️ Technologies Used

### 🧪 NumPy  
NumPy was used for numerical operations and handling multidimensional arrays during the data preprocessing and model training steps.

### 📊 Pandas  
Pandas allowed me to manipulate and clean tabular data efficiently, especially when organizing text sources into CSV format for training.

### 🤖 scikit-learn  
scikit-learn was used for model evaluation and utility functions such as splitting the dataset and calculating ROUGE scores.

### 🔥 Flask  
Flask served as the backend framework to deploy the summarization models via API and link them with the frontend.

### 🎯 Git & GitHub  
Version control was managed using Git, and the entire project is hosted on GitHub for transparency, collaboration, and version tracking.

### 💻 Google Colab  
I used Google Colab for training deep learning models, thanks to its free GPU access which helped speed up model training.

### 🧠 Hugging Face Transformers  
Used the pretrained T5-small model for abstractive summarization. Hugging Face's framework made it easy to load and fine-tune the model.

### 📱 Flutter  (not pushed)
Flutter was used to build the front-end interface, providing a responsive and user-friendly experience on both desktop and mobile.

---

## 📚 Project Workflow

1. **Data Collection & Cleaning**:  
   I gathered large text datasets from online sources and formatted them as CSV. The data was cleaned using Pandas and preprocessed to prepare it for model training.

2. **Model Development**:  
   I started with extractive summarization using TextRank, then implemented a GRU-based model. Finally, I fine-tuned a T5-small transformer for abstractive summarization, all evaluated using ROUGE metrics.

3. **Web Integration** (not pushed):  
   Once the models were ready, I integrated them into a Flask backend and connected it with a sleek Flutter UI, allowing real-time summarization for end users.

---

## 📈 Results & Future Improvements

The final app provides quick and coherent summaries, demonstrating the effectiveness of combining traditional and deep learning NLP techniques. Future improvements may include:

- Adding multilingual support
- Deploying the app to mobile via Flutter
- Using more advanced transformer models (e.g., T5-base, BART)
- Improving speed and scalability for real-world deployment

---

## About Me

I’m a solo developer passionate about AI, Data Science, and building tools that make life easier. This project marks a solid step forward in my journey into the world of Machine Learning and NLP.

---

## 📩 Contact

Feel free to reach out via GitHub if you have any questions or suggestions.

---

## 📄 License

This project is open-source under the MIT License.
