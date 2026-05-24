
# Snapnest

A clean coral/white social-media inspired photo sharing platform

## Features
- User registration & authentication
- Public / private photo albums
- Bulk photo uploads
- Collaborator roles (viewer / contributor / admin)
- Full-text album search

## Quick Start

```bash
cd snapnest
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
python manage.py migrate
python manage.py createsuperuser
python manage.py runserver 8001
```

Open http://localhost:8001

## Deploy (Render / Railway)
Set env vars: `SECRET_KEY`, `DATABASE_URL`, `DEBUG=False`, `ALLOWED_HOSTS`

# album
45fdaec2affa29fe955ea953e5ca6458a9372b48
