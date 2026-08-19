NEUROSENSE PYTHON WEBSITE
==========================

Stack:
- Frontend: HTML + CSS + JavaScript
- Backend: Python Flask
- Database: SQLite

Run locally:
1. Open a terminal in this folder.
2. Create a virtual environment (optional but recommended):
   python -m venv venv
3. Activate it:
   Windows: venv\Scripts\activate
   macOS/Linux: source venv/bin/activate
4. Install Flask:
   pip install -r requirements.txt
5. Start:
   python app.py
6. Open:
   http://127.0.0.1:5000

Backend:
- POST /api/enquiries stores contact-form submissions in neurosense.db
- GET /health checks the backend

Important:
The contact form stores enquiries in SQLite. It does not automatically send emails through Gmail because Gmail SMTP credentials/app configuration should not be placed in the website source. The website provides a direct mailto link to:
neurosense.wearable@gmail.com

Social links included:
Instagram:
https://www.instagram.com/neuro_sense_wearable/?utm_source=qr

LinkedIn:
https://www.linkedin.com/company/neurosense-wearables/
