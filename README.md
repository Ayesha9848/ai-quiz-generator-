# DeepKlarity — AI Wiki Quiz Generator (Full Features)

This repository contains a full-stack project:
- Backend: FastAPI (Python) with Gemini integration (google-generativeai) and fallback.
- Frontend: React + Vite.

Quick local run (backend):
```
cd backend
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
cp .env.example .env
uvicorn backend.main:app --reload --port 8000
```

Quick local run (frontend):
```
cd frontend
npm install
npm run dev
```

In development the frontend uses relative paths (/api/...) and a proxy can be configured in Vite if needed.

