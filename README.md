# OpenAI Chatbot (Node.js) 🤖💬

A simple yet powerful AI chatbot built using **Node.js**, **Express**, and the **OpenAI API**. This project allows users to interact with ChatGPT-like functionality through a clean, browser-based interface.

## 🚀 Features

- ⚡ Real-time interaction with OpenAI's GPT API  
- 🧠 Smart conversational AI assistant  
- 🖥️ Minimalistic and responsive frontend  
- 🔐 Secure API key management via environment variables  
- 🪶 Lightweight and easy to deploy

## 🛠️ Tech Stack

- **Backend**: Node.js, Express.js  
- **Frontend**: HTML, CSS, JavaScript  
- **AI Model**: OpenAI GPT (via API)

---

## 🧪 Getting Started

Follow these steps to run the chatbot locally:

### 1. Clone the Repository

```bash
git clone https://github.com/Coderxrohan/OpenAi-Chatbot-NodeJs
cd OpenAi-Chatbot-NodeJs
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Add Your OpenAI API Key

Create a `.env` file in the root directory and add:

```
OPENAI_API_KEY=your_openai_api_key_here
```

### 4. Run the Server

```bash
node index.js
```

### 5. Access the Chatbot

Open your browser and go to:  
👉 `http://localhost:3000`

---

## 📁 Project Structure

```
OpenAi-Chatbot-NodeJs/
│
├── public/
│   ├── style.css          # Frontend CSS
│   └── script.js          # Frontend JS
│
├── views/
│   └── index.html         # Main chatbot UI
│
├── .env                   # Environment variables (not committed)
├── index.js               # Express server and OpenAI API logic
├── package.json           # Project metadata and dependencies
└── README.md              # Project documentation
```

---

## 🧠 Future Plans

- Save chat history locally or to database  
- Add user authentication  
- Theme customization (dark/light mode)  
- Mobile-friendly improvements

---

## 🤝 Contributing

Contributions are welcome!  
Feel free to fork this repo and submit a pull request.

---

## 📜 License

This project is licensed under the **MIT License**.

---

## 🙋‍♂️ Author

Made with ❤️ by [Rohan Sarkar](https://github.com/Coderxrohan)

Have questions or suggestions? Open an issue or drop a star ⭐!
