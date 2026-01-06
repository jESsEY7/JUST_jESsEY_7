# Portfolio

This is a Django/Wagtail portfolio project.

## Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/jESsEY7/portfolio.git
   cd portfolio
   ```

2. **Create and activate a virtual environment:**
   ```bash
   python -m venv venv
   # Windows
   .\venv\Scripts\activate
   # Linux/MacOS
   source venv/bin/activate
   ```

3. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Run migrations:**
   ```bash
   python manage.py migrate
   ```

5. **Create a superuser:**
   ```bash
   python manage.py createsuperuser
   ```

6. **Run the server:**
   ```bash
   python manage.py runserver
   ```

Access the site at `http://127.0.0.1:8000` and the admin at `http://127.0.0.1:8000/admin`.