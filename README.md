# SigmaValue — Mini Real Estate Analysis Chatbot (React + Django)

This archive contains a ready-to-save project skeleton for the SigmaValue Full Stack assignment.
It includes example backend (Django) and frontend (React) source files, a sample CSV dataset, and instructions.

## Structure
- backend/ : Django project skeleton with API app and utilities
- frontend/: React app skeleton (create-react-app style)
- demo_script.txt : Video demo script
- README.md : This file

## How to use
1. Extract the archive.
2. Backend:
   - Create a Python virtual environment.
   - Install requirements: `pip install -r backend/requirements.txt`
   - Run migrations: `python manage.py migrate`
   - Run the server: `python manage.py runserver 8000`
   - The API endpoints are mounted under `/api/`.
3. Frontend:
   - `cd frontend && npm install && npm start`
   - The frontend expects the backend at `http://localhost:8000` (set `package.json` proxy or adjust fetch URLs).

## Notes
- The sample dataset is `backend/data/sample_realestate.csv` (small example). You can replace it with the provided Google Sheets export or your own Excel file.
- The OpenAI integration is optional; add `OPENAI_API_KEY` to the backend environment and enable the LLM view if needed.
