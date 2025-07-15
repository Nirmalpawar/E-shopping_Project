# E-shopping_Project

# 🛒 Window Shopping E-Cart Website

A modern, responsive, and dynamic E-Cart web application built with Django and powered by both SQLite and MySQL. This platform allows users to browse products, add them to the cart, and simulate a seamless window shopping experience — **without login barriers** or forced checkouts.

---

## 🌐 Live Demo

> 🔗 [Deployed Version (Optional)](https://your-live-link.com)

---

## 🚀 Tech Stack

| Frontend   | Backend | Database   | Others               |
|------------|---------|------------|----------------------|
| HTML5      | Python  | SQLite     | Django Templates     |
| CSS3       | Django  | MySQL      | Bootstrap 5          |
| JavaScript | Django ORM |        | AJAX, jQuery         |

---

## ✅ Key Features

- 🧭 **Guest Shopping:** Browse and add to cart without login.
- 🛍️ **Product Display:** Categories, images, dynamic pricing.
- 🧠 **Smart Cart System:** Real-time updates using AJAX.
- 💾 **Dual DB Support:** Development with SQLite, Production with MySQL.
- 📦 **Session-based Cart:** Cart persists until browser is closed.
- 📈 **Scalable Backend:** Modular Django architecture.
- 🔐 **Secure Forms:** CSRF protection and input validation.

---

## 🗂️ 🏗️ Project Folder Structure

```bash
Eshop-main/
├── db.sqlite3
├── manage.py
├── python
├── README.md
├── requirements.txt
├── .idea/
│   ├── Eshop.iml
│   ├── misc.xml
│   ├── modules.xml
│   ├── vcs.xml
│   └── inspectionProfiles/
│       ├── profiles_settings.xml
│       └── Project_Default.xml
├── env/
│   ├── pyvenv.cfg
│   └── Lib/
│       └── site-packages/
│           ├── (Python packages and cache folders...)




⚙️ Installation Guide

1. Clone the Repository
git clone https://github.com/Nirmalpawar/window-shopping-ecart.git
cd window-shopping-ecart

2. Create Virtual Environment
python -m venv env
source env/bin/activate   # On Windows: env\Scripts\activate

3. Install Dependencies
pip install -r requirements.txt

4. Configure Database
By default, it uses SQLite. To switch to MySQL:

Update DATABASES config in settings.py:
DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.mysql',
        'NAME': 'your_db_name',
        'USER': 'your_user',
        'PASSWORD': 'your_password',
        'HOST': 'localhost',
        'PORT': '3306',
    }
}

5. Run Migrations & Start Server
python manage.py makemigrations
python manage.py migrate
python manage.py runserver

🔮 Future Scope
✅ User Authentication (Optional Sign-Up)

✅ Checkout with Payment Gateway

✅ Admin Dashboard for Inventory

✅ Wishlist and Product Ratings

✅ REST API Integration

🤝 Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

🧑‍💻 Author
Mr. Nirmal Pawar
MCA Graduate | AI-ML Enthusiast | Web Developer
GitHub • LinkedIn

📄 License
This project is licensed under the MIT License - see the LICENSE file for details.



