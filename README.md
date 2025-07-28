
# 📰 Info Sphere – News Search Web Application

Info Sphere is a responsive and dynamic full-stack web application that allows users to search and read the latest news articles from around the world. It fetches real-time news from [NewsAPI.org](https://newsapi.org) and stores user search queries in a MySQL database for analytics and tracking purposes.

---

## 🚀 Features

- 🔍 Search news by keyword
- 🧠 Real-time articles using NewsAPI
- 💾 Store search history in MySQL database
- 🎨 Responsive UI with clean design
- 🔌 Full-stack integration (Frontend + Backend + Database)

---

## 💻 Tech Stack

| Layer       | Technology             |
|-------------|------------------------|
| Frontend    | HTML, CSS, JavaScript  |
| Backend     | Node.js, Express.js    |
| Database    | MySQL                  |
| API         | [NewsAPI](https://newsapi.org) |
| Dev Server  | Live Server (VS Code)  |

---

## 📁 Project Structure

```
NEWS_WEBSITE/
├── frontend/
│   ├── index.html
│   ├── script1.js
│   ├── style.css
│   └── assets/
│       └── logo.png
├── backend/
│   └── server.js
├── package.json
└── README.md
```

---

## ⚙️ Setup Instructions

### 📦 Backend Setup

1. Go to backend folder:
   ```bash
   cd backend
   ```

2. Install dependencies:
   ```bash
   npm install express mysql cors body-parser
   ```

3. Run the backend server:
   ```bash
   node server.js
   ```

---

### 🗃️ MySQL Database Setup

1. Open MySQL Workbench or terminal
2. Create database and table:
   ```sql
   CREATE DATABASE news_db;

   USE news_db;

   CREATE TABLE searches (
       id INT AUTO_INCREMENT PRIMARY KEY,
       query VARCHAR(255),
       searched_at TIMESTAMP DEFAULT CURRENT_TIMESTAMP
   );
   ```

---

### 🌐 Frontend Setup

1. Open the `frontend/index.html` file in **VS Code**
2. Right-click and select **"Open with Live Server"**

Now visit:
```
http://127.0.0.1:5500/NEWS_WEBSITE/frontend/index.html
```

---

## 📱 Mobile Access (Optional)

1. Get your PC's IP using:
   ```bash
   ipconfig
   ```

2. Open the site from your mobile browser:
   ```
   http://<your-ip>:5500/NEWS_WEBSITE/frontend/index.html
   ```

✅ Ensure mobile and PC are connected to the same Wi-Fi network.

---

## 📈 Future Improvements

- 🔐 Add user login/register
- ⭐ Save and view favorite articles
- 📊 View search history on frontend
- 🌙 Add dark/light mode toggle
- 🌍 Deploy project to Netlify + Render

---

## 🙋‍♂️ Author

**Jagadesh L**  
Final Year Student  
Full-Stack Developer | 2025

---

## 📄 License

This project is licensed for educational use.
