# ☕ Coffee Shop Chatbot

## 🌟 Overview

The **Coffee Shop Chatbot** is an AI-powered chatbot designed to assist customers by answering queries about menu items, payment options, and other coffee shop-related information. The chatbot is built using **PyTorch** for the backend AI model and **Flask** for API communication, while the frontend is developed in **HTML, CSS, and JavaScript**.

## 🚀 Features

- **Conversational AI**: Uses a trained neural network to process and respond to customer queries.
- **Speech Recognition**: Enables users to interact with the chatbot using voice input.
- **Interactive UI**: A visually appealing chat interface with smooth animations.
- **NGROK Integration**: Provides a public URL to expose the chatbot API.
- **Cross-Origin Support**: Enabled via Flask-CORS for seamless frontend-backend communication.

## 🛠️ Tech Stack

### 🔙 Backend:
- Python (Flask, PyTorch, NumPy, NLTK)
- Torch-based Neural Network
- NGROK (for exposing local API)
- Flask-CORS (to enable cross-origin requests)

### 🎨 Frontend:
- HTML, CSS, JavaScript
- Speech Recognition API (for voice commands)

## Installation and Setup

### 📌 Prerequisites

Ensure you have the following installed:
- Python **3.7+**
- Pip
- Ngrok
- Flask
- PyTorch

### 🔧 Backend Setup

Clone the repository:

```sh
git clone https://github.com/your-username/coffee-shop-chatbot.git
cd coffee-shop-chatbot
```

Install dependencies:

```sh
pip install flask flask-ngrok torch flask-cors numpy nltk
```

Train the AI model:

```sh
python train.py
```

Start the backend server:

```sh
python app.py
```

### 🌍 NGROK Setup (Optional)

```sh
ngrok http 5000
```

Copy the public URL generated and use it in the frontend.

### 🖥️ Frontend Setup

- Open `index.html` in a browser.
- Ensure the API endpoint is correctly pointing to the Flask server URL.

## 🎯 Usage

- ✍️ Type or 🎙️ speak to ask about coffee options, prices, and payment methods.
- 🤖 The chatbot will respond based on trained data from `intents.json`.

## 🔮 Future Enhancements

- 🛒 Integration with a real coffee shop ordering system
- 🌍 Support for multiple languages
- 🏆 Enhancing AI model with advanced NLP techniques

## 🤝 Contributing

1. 🍴 Fork the repository.
2. 🌱 Create a new branch (`feature-xyz`).
3. ✅ Commit changes and push to GitHub.
4. 🔄 Submit a pull request.

## 📜 License

This project is open-source and available under the **MIT License**.

## 📧 Contact

For queries and contributions, reach out via [vickyvikas463@gmail.com] or
LinkedIn [https://www.linkedin.com/in/laxman-vikas-kommireddi/]
