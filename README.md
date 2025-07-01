# 🧠 Task Manager App – Django + React Full Stack

This is a full-stack task management application using:

- ⚙️ **Backend**: Django REST Framework
- 🎨 **Frontend**: React + Tailwind CSS
- 🗄 **Database**: PostgreSQL
- 🔐 **Auth**: JWT-based login/register

## 🔧 Features

- User registration and login
- Create, view, edit, and delete tasks
- Filter tasks by status or due date
- Responsive UI
- RESTful API

## 📦 Folder Structure

```
TaskManager-FullStack/
│
├── backend/                # Django Backend
│   └── taskmanager/        # Project
│   └── taskmanager_app/    # App
│
├── frontend/               # React Frontend
│   └── src/components/     # UI Components
```

## 🚀 How to Run

1. Setup Python backend
```bash
cd backend
python -m venv env
source env/bin/activate
pip install -r requirements.txt
python manage.py runserver
```

2. Setup React frontend
```bash
cd frontend
npm install
npm start
```

3. Open `http://localhost:3000` to view the app.

## 🧪 Coming Soon

- Unit tests
- Dark mode
- Task priority and labels

