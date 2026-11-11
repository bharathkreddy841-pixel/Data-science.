# CAIAS Student Registration System

A mobile-friendly student registration web app built with **Python only** (Streamlit + SQLite).
Made by Bharath K.

## Features
- Name, college register number (format `CAUG26-0240`), 10-digit phone, Gmail ID
- BCA program dropdown: Full Stack, Data Science, AI & ML
- Fun feedback questions about the college
- Duplicate register numbers are blocked
- Thank-you screen with balloons
- Admin page (password protected) with a chart and CSV download

## Run locally
```bash
pip install -r requirements.txt
streamlit run app.py
```

## Get a link for your phone (free)
1. Upload this folder to a GitHub repository.
2. Go to https://share.streamlit.io and sign in with GitHub.
3. Click **Create app**, pick your repository, set the main file to `app.py`, and deploy.
4. Open **Settings > Secrets** for the app and add your admin password:
   ```
   ADMIN_PASSWORD = "choose-a-strong-password"
   ```
5. Open the `.streamlit.app` link on your phone.

Note: the default admin password is `admin123` if no secret is set. Change it before sharing.
Streamlit Cloud's storage can reset when the app restarts, so download the CSV from the Admin page regularly.
