# 📈 IPO Web App

A Django-based web application to explore, list, and manage IPOs (Initial Public Offerings). Users can view upcoming, ongoing, and listed IPOs with complete details, download official documents, and access an attractive dashboard UI.

---

## 🚀 Features

- Company-wise IPO listings (Upcoming, Ongoing, Listed)
- Upload and access RHP/DRHP documents
- View issue size, price band, lot size, and listing date
- Live counts and animated SVG charts on homepage
- Bootstrap-styled responsive UI
- Admin panel for managing IPOs
- Static and media file support using WhiteNoise

---

## 🛠 Tech Stack

- Django 5.2.3
- Python 3.12
- SQLite3 (default DB)
- HTML + CSS + Bootstrap Icons

---

## ⚙️ Project Setup

Follow the steps below to run the project locally:

```bash
# 1. Clone the repository
git clone https://github.com/yourusername/ipo-web-app.git
cd ipo-web-app

# 2. Create and activate virtual environment
python -m venv venv
venv\Scripts\activate   # For Windows

# 3. Install dependencies
pip install -r requirements.txt

# 4. Apply migrations
python manage.py makemigrations
python manage.py migrate

# 5. Create superuser for admin access
python manage.py createsuperuser

# 6. Run the development server
python manage.py runserver
```
## 🔐 Admin Panel

Access the Django admin panel to manage IPO listings and related data.

**URL:** [http://127.0.0.1:8000/admin](http://127.0.0.1:8000/admin)

### 👤 Login

Log in using your superuser credentials:

```bash
python manage.py createsuperuser
```

### ✅ Admin Capabilities

From the admin panel, you can:

- ➕ **Add new IPO listings**
- 📝 **Edit existing IPOs**
- ❌ **Delete IPO entries**
- 🖼️ **Upload company logos**
- 📄 **Upload RHP and DRHP documents**
- 🎯 **Set IPO status**: `upcoming`, `ongoing`, or `listed`
- 📅 **Manage important dates**: open date, close date, listing date
- 💵 **Set price band and lot size**


