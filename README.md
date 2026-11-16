# RecoMind 🎯

A web-based recommendation app that gives users personalized suggestions based on their reviews and activity history.

## 📖 Overview
RecoMind lets users sign up, leave reviews, and get recommendations based on [what it recommends, e.g. movies / books / products]. A Node.js server handles the backend logic and stores data in JSON files, and a simple HTML/CSS/JS frontend handles the interface.

## ✨ Features
- User accounts stored in `users.json`
- Review system stored in `reviews.json`
- Activity history tracking in `history.json`
- [Recommendation logic, e.g. based on ratings / similar users / past activity]
- Responsive, lightweight frontend

## 🛠️ Tech Stack
- **Frontend:** HTML, CSS, JavaScript
- **Backend:** Node.js [+ Express, if used]
- **Storage:** JSON files

## 📂 Project Structure
```
RecoMind/
├── index.html       # Main page
├── style.css        # Styling
├── app.js           # Frontend logic
├── server.js        # Backend server
├── users.json       # User data
├── reviews.json     # Reviews data
├── history.json     # User history
├── package.json
└── package-lock.json
```

## 🚀 Getting Started

### Prerequisites
- [Node.js](https://nodejs.org/) (v14 or higher)

### Installation
```bash
git clone https://github.com/prabalthakur07/RecoMind.git
cd RecoMind
npm install
```

### Run the app
```bash
node server.js
```
Then open `http://localhost:3000` in your browser. [Change the port if yours is different.]

## 🧠 How It Works
1. The user signs up or logs in
2. The user submits reviews, which are saved to `reviews.json`
3. Activity is logged in `history.json`
4. The server uses this data to generate recommendations
5. Results are shown on the frontend

## 🔮 Future Improvements
- Move from JSON files to a database (MongoDB / PostgreSQL)
- Add password hashing and authentication tokens
- Improve the recommendation algorithm

## 👤 Author
**Prabal Thakur**
GitHub: [@prabalthakur07](https://github.com/prabalthakur07)
