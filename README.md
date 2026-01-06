# Portfolio — Django · Wagtail

A production-grade personal portfolio built on **Django** and **Wagtail CMS**.  
Designed to showcase systems thinking, clean architecture, and content-driven presentation without frontend bloat.

---

## Stack

- **Backend:** Django 5.x  
- **CMS:** Wagtail  
- **Database:** SQLite (dev) / PostgreSQL-ready  
- **Frontend:** Django templates, modern CSS  
- **Content Model:** Page-based, editor-friendly, extensible  

---

## Features

- Modular Wagtail page architecture
- Custom page models for portfolio content
- Image handling via Wagtail image chooser
- Clean separation of content, layout, and logic
- Admin-first content control (no hardcoded data)
- Ready for deployment and scaling

---

## Local Setup

### 1. Clone the repository
```bash
git clone https://github.com/jESsEY7/portfolio.git
cd portfolio
2. Create and activate a virtual environment
bash
Copy code
python -m venv venv
# Windows
.\venv\Scripts\activate
# Linux / macOS
source venv/bin/activate
3. Install dependencies
bash
Copy code
pip install -r requirements.txt
4. Run database migrations
bash
Copy code
python manage.py migrate
5. Create an admin user
bash
Copy code
python manage.py createsuperuser
6. Start the development server
bash
Copy code
python manage.py runserver
