# 🌾 LLM-Based Agriculture Chatbot

An AI-powered **Agriculture Chatbot** built using the **Mistral API** that answers **only agriculture-related questions**.  
The system is designed to assist farmers, students, and researchers by providing accurate information about crops, soil nutrients, fertilizers, irrigation, pests, and farming practices.

Unlike general chatbots, this system is **domain-restricted**, meaning it only responds to agriculture-related queries and avoids answering unrelated questions.

---

## 🚀 Features

- 🌱 Answers **only agriculture-related questions**
- 🤖 Powered by **Mistral Large Language Model API**
- 💬 Natural language conversation interface
- 📚 Provides guidance on:
  - Crop cultivation
  - Soil nutrients
  - Fertilizers
  - Irrigation
  - Pest control
  - Weather impact on crops
- ⚡ Fast responses using modern LLM technology
- 🧠 Prompt-based filtering to prevent non-agriculture responses

---

## 🛠️ Technologies Used

- Python
- Mistral AI API
- Streamlit
- Large Language Model (LLM)
- LLM Prompt Engineering

---

## 📂 Project Structure

```
LLM-Agriculture-Chatbot
│
├── app.py
├── requirements.txt
├── README.md
└── .env
```

---

## ⚙️ Installation

Clone the repository

```bash
git clone https://github.com/Avins-VR/LLM-Agriculture-Chatbot.git
cd LLM-Agriculture-Chatbot
```

Create a virtual environment

```bash
python -m venv venv
```

Activate the environment

Windows

```bash
venv\Scripts\activate
```

Install dependencies

```bash
pip install -r requirements.txt
```

---

## 🔑 Setup API Key

Create a `.env` file and add your **Mistral API Key**

```
MISTRAL_API_KEY=your_api_key_here
```

---

## ▶️ Run the Application

```bash
streamlit run app.py
```

The chatbot interface will open in your browser.

---

## 💡 Example Questions

- What fertilizer is best for rice crops?
- How to control pests in tomato plants?
- What soil pH is suitable for coffee plants?
- How often should crops be irrigated?

If the user asks **non-agriculture questions**, the chatbot will refuse to answer.

---

## 🎯 Use Cases

- Farmer assistance systems
- Smart farming platforms
- Agricultural advisory services
- Agricultural research support

---

## 👨‍💻 Author

**Avins V R**  
AI & Data Science Student  
AI & ML Developer

GitHub: https://github.com/Avins-VR
