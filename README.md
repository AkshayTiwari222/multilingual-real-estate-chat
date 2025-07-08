# multilingual-real-estate-chat
# 🏠 Real Estate Multilingual Chat App

A multilingual real-time chat platform designed for real estate agents and clients to communicate seamlessly across different languages. It features AI-assisted responses, automatic chat summary generation, and a clean user interface built using Node.js, EJS, and SQLite.
## ✨ Features

- 🌐 Real-time multilingual translation using Translation API
- 🤖 AI-generated responses for common real estate queries
- 📝 Automatic chat summary generation with export to PDF
- 🔐 User authentication system (register/login)
- 📄 Agreement and contract templates for property transactions
- 💬 EJS templating for dynamic web pages
- 🗄️ SQLite database for efficient local data storage

- 
###Folder structure
real-estate-multilingual-chat/
├── public/ # Static assets (CSS, JS, images)
├── views/ # EJS templates for rendering pages
│ ├── agreement.ejs
│ ├── chat.ejs
│ ├── contract.ejs
│ ├── index.ejs
│ ├── login.ejs
│ ├── register.ejs
│ └── summary.ejs
├── database.sql # SQL schema or seed file
├── .env # Environment variables
├── server.js # Main Express server file
├── package.json # Project metadata and scripts
└── README.md # Project documentation


## 🚀 Getting Started

Follow these steps to set up and run the project locally.

### 1. Clone the repository
```bash
git clone https://github.com/yourusername/real-estate-multilingual-chat.git
cd real-estate-multilingual-chat
npm install
TRANSLATION_API_KEY=your_api_key_here
PORT=3000
npm start
http://localhost:3000

## 🛠 Tech Stack

- **Node.js + Express** – Backend server and routing
- **EJS** – Server-side templating engine for dynamic HTML rendering
- **SQLite** – Lightweight database for storing user data and chat history
- **HTML/CSS/JavaScript** – Frontend structure and interactivity
- **Translation API** – Real-time language translation (e.g., Google Translate or Gemini)
- **AI API (optional)** – Smart suggestions, chat summaries, or AI-assisted replies

## 📌 Use Cases

- 🏡 Real estate agents can communicate with clients who speak different languages.
- 💬 Chats are translated in real time to remove language barriers.
- 🧠 AI-generated replies help agents respond faster to common queries.
- 📄 Summary of chats can be generated and exported for record-keeping.
- 🤝 Agreement and contract pages simplify documentation during property transactions.
- 🌍 Ideal for international property dealings and multilingual customer service.

## 📃 License

This project is licensed under the [MIT License](LICENSE).

You are free to use, modify, and distribute this software with proper attribution.


## 🙋‍♂️ Author

**Akshay Tiwari**

- 📫 Email: akshay.tiwari.cs@gmail.com
- 💼 LinkedIn: [https://www.linkedin.com/in/akshay-tiwari-5b6198285/]
- 💻 GitHub: [https://github.com/yourusername](https://github.com/yourusername)

Feel free to reach out, contribute, or fork the project!
