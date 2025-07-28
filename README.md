# Triviaverso

**Triviaverso** is a geek-themed trivia game where questions are generated dynamically using OpenAI's API. Built with **JavaScript**, **HTML**, **CSS**, and **Bootstrap**, it features a modular architecture with both frontend and backend components powered by **Express.js (Node.js)**.

## Features

- Dynamic trivia question generation using OpenAI API
- Modular frontend-backend architecture
- Stylish and responsive UI with Bootstrap
- Easy to run locally using Node.js

## Topics

Triviaverso is centered around geek culture — covering categories such as video Gears of War, League of legends, Dragon ball, and more.

---

## Technologies Used

- **Frontend:** HTML, CSS, JavaScript, Bootstrap
- **Backend:** Node.js, Express.js
- **AI Integration:** OpenAI API
- **Database** MongoDB

---

## Installation & Running Locally

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/Triviaverso.git
cd Triviaverso/BACKEND
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Add Your OpenAI API Key

Edit the file:

```
BACKEND/controllers/questions_api_controller.js
```

At line 7, replace the empty string with your own API key:

```js
const openAIClient = new openAI({ apiKey: "YOUR_API_KEY_HERE" });
```

### 4. Run the Server

```bash
node server.js
```

The app will be available at:\
[http://localhost:3000](http://localhost:3000)

---

## Notes

- Ensure your OpenAI API key is active and has available usage quota.
- This project is intended for educational and entertainment purposes.

