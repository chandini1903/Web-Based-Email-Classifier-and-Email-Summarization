# 📧 Web-Based Email Classifier and Email Summarization

This project is a full-stack web application built using the **MERN stack** that allows users to upload or fetch emails, automatically classify them into categories (e.g., Spam, Work, Social) using **Naive Bayes**, 
and generate concise summaries of their content using the **Hugging Face NLP API**.

---

## 🚀 Features

- 🔍 **Email Classification** using Machine Learning (Naive Bayes)
- ✂️ **Email Summarization** using Hugging Face Transformers API
- 💻 **MERN Stack** based: React frontend, Express.js & Node.js backend, MongoDB for storage
- 🔐 User authentication and email fetching integration (optional)
- 📱 Responsive and user-friendly UI

---

## 🛠️ Tech Stack

| Layer         | Technology                     |
|---------------|--------------------------------|
| Frontend      | React.js, HTML, CSS            |
| Backend       | Node.js, Express.js            |
| Database      | MongoDB (with Mongoose)        |
| Machine Learning | Python (Naive Bayes for classification) |
| NLP API       | Hugging Face Transformers (for summarization) |
| Others        | Axios, dotenv, CORS, etc.      |

---

## 🧠 ML & NLP Details

- **Email Classification:**  
  Implemented using the **Naive Bayes algorithm** to categorize emails into predefined classes like Work, Personal, Spam, etc.

- **Email Summarization:**  
  Integrated with the **Hugging Face API** to perform **abstractive summarization** using transformer models like `t5-small` or `bart-large-cnn`.

---

## 📦 Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/chandini1903/Web-Based-Email-Classifier-and-Email-Summarization.git
cd Web-Based-Email-Classifier-and-Email-Summarization
