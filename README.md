# 🤖 AI Agent with Tool Calling (Gemini API)

This project is a **command-line AI Agent** built using **Google Gemini API** that can dynamically decide whether to answer a query directly or invoke a specific tool based on the user's request.

---

## ✨ Features

The AI Agent can perform the following tasks:

- ➕ Calculate the sum of two numbers  
- 🔢 Check if a number is **prime**  
- 💰 Fetch real-time **cryptocurrency prices**  
- 🌤️ Get **current weather information** for any city  

The agent intelligently selects the appropriate tool using **function declarations**.

---

## 🧠 How It Works

1. User enters a query in the terminal  
2. The query is added to conversation history  
3. Gemini model analyzes the query  
4. If required, it calls the relevant function  
5. The function result is sent back to the model  
6. The final response is shown to the user  

---

## 🛠 Tech Stack

- Node.js  
- JavaScript  
- Google Gemini API (gemini-2.5-flash)  
- CoinGecko API  
- WeatherStack API  

---

## 📂 Available Tools

| Tool Name | Description |
|---------|-------------|
| sum | Adds two numbers |
| prime | Checks if a number is prime |
| getCryptoPrice | Fetches crypto price |
| getWeatherInfo | Fetches live weather data |

---

## 🚀 Installation & Usage

```bash
git clone https://github.com/your-username/ai-agent-tool-calling.git
cd ai-agent-tool-calling
npm install
node index.js

---

📌 Example Queries

Add 45 and 78
Is 17 a prime number?
Price of bitcoin
Weather in New Delhi

---

📈 Learning Outcome

Understanding AI Agents
Function Calling with LLMs
API Integration
Conversation Memory Handling

---

🙌 Future Improvements

Add more tools
Error handling
UI-based interface
Deployment as a web service

---

👨‍💻 Author

Aman Sharma
B.Tech Student | AI & Web Development Enthusiast
