# Phase 5 — Project Development
The complete runnable implementation is in the project root.
Run:
```bash
pip install -r requirements.txt
uvicorn app:app --reload
```
Open `http://127.0.0.1:8000`.
Set `GEMINI_API_KEY` in `.env` to enable Gemini-generated responses; without it the local recommendation engine runs.
