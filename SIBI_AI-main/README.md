# 📘 SIBI AI – Smart Interactive Buddy for Intelligence

SIBI AI is a personalized AI-powered study assistant designed to help students with interactive learning, quizzes, study mode, and answer evaluation. It integrates backend logic (Python + FastAPI), a responsive frontend (HTML, CSS, JS), and AI APIs for smart assistance.

---

## 📁 Project Structure

```
SIBI_AI/
│
├── backend/
│   └── main.py              # FastAPI backend handling AI interactions and routes
│
├── frontend/
│   ├── scripts/             # JavaScript files for interactivity
│   ├── styles/              # CSS files for styling
│   ├── index.html           # Home page
│   ├── login.html           # Login form
│   ├── signup.html          # Signup form
│   ├── dashboard.html       # User dashboard
│   ├── quiz.html            # Quiz interface
│   ├── study_mode.html      # Study mode UI
│   ├── answer.html          # Answer submission and evaluation
│
└── requirements.txt         # Python dependencies
```

---

## 🚀 Features

- 📚 **Study Mode** – Guided learning with AI
- 🤖 **AI Answer Evaluation** – Get instant feedback on written answers
- 📊 **Quiz Module** – Interactive quizzes to test knowledge
- 🔐 **User Authentication** – Simple login/signup
- 🌐 **FastAPI Backend** – Lightweight and fast API server
- 💡 **Frontend UI** – Clean, responsive UI for a seamless experience

---

## ⚙️ Technologies Used

### Backend
- FastAPI
- Groq / Gemini API
- Python 3.10+
- Uvicorn (development server)

### Frontend
- HTML, CSS, JavaScript
- Bootstrap (optional)

---

## 🧪 Installation & Running Locally

### 1. Clone the Repository
```bash
git clone https://github.com/Sharavanakumar-Ramalingam/SIBI_AI.git
cd SIBI_AI
```

### 2. Backend Setup
```bash
cd backend
pip install -r ../requirements.txt
uvicorn main:app --reload
```

This will start the backend on `http://127.0.0.1:8000`

### 3. Frontend Usage
Open `frontend/index.html` or `frontend/login.html` directly in the browser.  
Make sure your backend server is running to handle the AI requests.

---

## 🧠 How It Works

- The **login/signup** system allows users to access personalized data.
- The **study mode** gives structured help with AI-generated explanations.
- The **answer page** connects with the backend to get AI evaluation and suggestions.
- The **quiz page** dynamically loads questions and evaluates them.
- All interactions with the AI model are routed through `FastAPI` backend.

---

## 📦 requirements.txt

```txt
fastapi
uvicorn
requests
python-dotenv
```

Make sure you also create a `.env` file with the following content:

```
GROQ_API_KEY=your_groq_api_key
```

---

## 🧑‍💻 Author

**Vishal Dhanapaul**  
> Developed as part of an educational AI initiative.
