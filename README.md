# Student and Teacher Attendance Management System
<img width="1897" height="863" alt="attendance management" src="https://github.com/user-attachments/assets/919f6170-33fd-490c-be30-f7f3bb74a355" />


This project includes two parts:

- A polished Vite, React, and Tailwind UI prototype in `src/App.tsx`.
- A Django and Python attendance backend in `attendance/` and `school_attendance/`.

## Run the Django App

```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
python manage.py migrate
python manage.py seed_attendance
python manage.py runserver
```

Open `http://127.0.0.1:8000/` for the Django dashboard.

The SQLite database file `db.sqlite3` is created automatically when you run `python manage.py migrate`. The schema migration is included in `attendance/migrations/0001_initial.py`.

## Run the React UI

```bash
npm install
npm run dev
```

Open the local Vite URL shown in the terminal.
