# 🍳 Recipe Chatbot

🚫 This project is for Reading only.  
❗ Cloning, copying, or using any part of the code without permission is not allowed.


A conversational recipe assistant built using the MERN stack and powered by Generative AI via the Gemini API.

---

## 📝 Overview

This project is a chatbot web application that helps users find, generate, and discuss recipes. Leveraging the power of GenAI (via Gemini API), the bot can suggest recipes based on ingredients, dietary preferences, cuisine types, and more!

- **Frontend:** React.js  
- **Backend:** Node.js & Express.js  
- **Database:** MongoDB  
- **AI Integration:** Gemini API (GenAI)

---

## 🚀 Features

- **Natural Recipe Conversations:** Chat with the bot to get recipe ideas, instructions, and tips.
- **Ingredient-Based Search:** Suggest recipes based on ingredients you have.
- **Personalized Recommendations:** Get recipes tailored to diet, cuisine, and allergies.
- **Save & Retrieve:** Save favorite recipes and view your history.
- **Modern UI:** Responsive and friendly chat interface.

---

## 🛠️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/Suhasygowda/masterChefRecipesBot.git
cd https://github.com/Suhasygowda/masterChefRecipesBot.git
```

### 2. Set Up Backend

```bash
cd backend
npm install
# Create a `.env` file with your environment variables
npm start
```

### 3. Set Up Frontend

```bash
cd ../frontend
npm install
npm start
```

### 4. Configure Environment

- **MONGO_URI:** MongoDB connection string
- **GEMINI_API_KEY:** Your Gemini API key

Add these to your backend `.env` file.

---

## 🤖 How It Works

1. **User Interaction:** Users chat with the bot in the React frontend.
2. **Server Processing:** Express.js backend handles chat logic and persists data in MongoDB.
3. **AI Response:** Backend sends recipe queries to the Gemini GenAI API and returns intelligent responses.

---

## 💡 Future Ideas

- Voice interaction
- Meal planning & grocery lists
- Multi-language support

---

## 👨‍💻 Author

- [Suhas y gowda](https://github.com/<your-username>)

---

> **Built with ❤️ using MERN & Gemini API**
