# ♟️ Chess Multiplayer App

Welcome to the **Chess Multiplayer App** – a real-time online chess game built using **Node.js**, **Socket.IO**, and **EJS**. Play chess with friends directly in your browser with smooth gameplay and room-based matchmaking.

## 🚀 Features

- 🔁 Real-time multiplayer gameplay  
- 🌐 WebSocket communication via Socket.IO  
- 🧠 Chess rules powered by `chess.js`  
- 💡 Clean UI with `chessboard.js`  
- 🛏️ Room creation & join system  
- 📃 PGN (Portable Game Notation) logging  
- 🕒 Optional game timer support  

## 🛠️ Tech Stack

Frontend: HTML, CSS, JavaScript  
Backend: Node.js, Express.js  
Templating: EJS  
Real-time: Socket.IO  
Chess Engine: `chess.js`  
UI Board: `chessboard.js`

## 📦 Installation

```
git clone https://github.com/ModiVanshN/chessapp.git
cd chessapp
npm install
```

### 🔄 Start the Server

```
node index.js
```

Then open your browser and go to:
```
http://localhost:3000
```

## 🧪 How to Play

1. Open the app in two different browser tabs or devices.  
2. Create a room with a unique ID.  
3. Share that ID with your opponent.  
4. Start playing chess in real-time!

## 📂 Project Structure

```
chessapp/
│
├── front/              # Static frontend files
│   ├── css/
│   └── js/
│
├── server/             # Server-side logic and socket handling
│
├── views/              # EJS templates
│
├── config.js           # Configuration file
├── index.js            # Entry point for Node.js server
├── package.json
└── .gitignore
```

## 🧑‍💻 Author

**Modi Vansh N**  
GitHub: https://github.com/ModiVanshN

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🌟 Star this repo

If you like this project, consider giving it a ⭐ on GitHub!
