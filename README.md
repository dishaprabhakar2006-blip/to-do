# 📝 To-Do List Web App

A simple and clean To-Do List web application built using **Python Flask** and **HTML/CSS**.

---

## 🚀 Features

- Add new tasks
- Mark tasks as complete / undo completion
- Delete tasks
- Live task counter
- Clean responsive UI

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| Backend | Python, Flask |
| Frontend | HTML, CSS, Jinja2 |
| Deployment | Vercel |

---

## 📁 Project Structure

```
miniproject_6/
├── templates/
│   └── index.html      # Frontend UI
├── app.py              # Flask backend
├── requirements.txt    # Dependencies
└── vercel.json         # Vercel deployment config
```

---

## ⚙️ How to Run Locally

1. **Clone the repository**
```bash
git clone https://github.com/dishaprabhakar2006-blip/miniproject_6.git
cd miniproject_6
```

2. **Install dependencies**
```bash
pip install flask
```

3. **Run the app**
```bash
python app.py
```

4. **Open in browser**
```
http://127.0.0.1:5000
```

---

## 🌐 Deployment

This app is deployed on **Vercel**.

Live URL: `[to-do-iota-silk.vercel.app](https://to-do-iota-silk.vercel.app/)`

---

## 📌 API Routes

| Route | Method | Description |
|-------|--------|-------------|
| `/` | GET | Home page, displays all tasks |
| `/add` | POST | Adds a new task |
| `/complete/<index>` | GET | Toggles task completion |
| `/delete/<index>` | GET | Deletes a task |

---

## 👩‍💻 Author

**Disha Prabhakar**  
Internship Mini Project — 2026
