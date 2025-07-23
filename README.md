# 📄 Google Docs Clone

A real-time collaborative document editing web application inspired by **Google Docs**. This project demonstrates the use of **Node.js**, **Socket.IO**, and **Quill.js** to enable multiple users to edit the same document simultaneously.

---

## 🚀 Features

- 📝 Rich text editing with Quill.js
- 🔄 Real-time collaboration using WebSockets (Socket.IO)
- 🗂️ Document persistence with MongoDB (optional)
- 🌐 Simple and responsive UI

---

## 🛠️ Tech Stack

- **Frontend**: HTML, CSS, JavaScript, Quill.js
- **Backend**: Node.js, Express.js, Socket.IO
- **Deployment**: Heroku (Procfile included)

---

## 📁 Project Structure

```
gdocsclone/
│
├── client/              # Frontend files
│   ├── index.html
│   └── script.js
│
├── server/              # Backend files
│   ├── server.js
│   └── socket.js
│
├── Procfile             # For Heroku deployment
└── README.md            # Project documentation
```

---

## 📦 Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/kamblesarvesh178/gdocsclone.git
   cd gdocsclone
   ```

2. **Install dependencies**:
   ```bash
   npm install
   ```

3. **Run the server**:
   ```bash
   node server/server.js
   ```

4. **Open in browser**:
   ```
   http://localhost:3000
   ```

---


## 📌 Future Improvements

- User authentication
- Document saving and loading from a database
- Version history
- Comments and suggestions

---

## 👨‍💻 Author

- @kamblesarvesh178
