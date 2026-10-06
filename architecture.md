# Phase 3 — Project Design
```text
Browser → FastAPI → Planner Routes → Recommendation Service
                                      ↙          ↘
                              Gemini API       Local Fallback
                                      ↓
                                  Result → History → Jinja2 UI
```
The root `app.py` is the entry point. `services/` contains authentication and recommendation logic. `templates/` is the frontend and `static/` contains styling.
