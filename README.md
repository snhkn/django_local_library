# Local Library 📚

This is a sample Django project built by following the [MDN Web Docs Local Library Tutorial](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django/Tutorial_local_library_website).

The application simulates a local library website where users can:
- Browse books and authors
- Log in to view borrowed books
- Renew borrowed books (if they have librarian permissions)
- View loan status and availability

## 🚀 Features

- Django-powered backend (Django 5.2)
- User authentication and permissions
- Book, author, genre, and book instance models
- Admin interface to manage records
- Bootstrap 5 styling
- Form handling with validation
- Pagination and messages framework integration

## 🛠️ Setup Instructions

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/local-library.git
   cd local-library
2. **Create and activate a virtual environment:**
   ```bash
   python -m venv env
   source env/bin/activate  # On Windows: env\Scripts\activate

3. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   
4. **Run migrations and create a superuser:**
   ```bash
   python manage.py migrate
   python manage.py createsuperuser 

5. **Run the development server:**
  ```bash
  python manage.py runserver
  ```

6. **Open your browser and visit:**
http://127.0.0.1:8000

## 🔐 Admin Access
Access the Django admin panel here:
http://127.0.0.1:8000/admin

Use the superuser credentials you created to log in.

## ✅ Credits

This project is based on the excellent tutorials provided by **MDN Web Docs**. You can explore the full tutorial series and learn more about web development at:

- 🌐 [MDN Web Development Tutorials](https://developer.mozilla.org/en-US/docs/Learn_web_development/)
- 📘 [Local Library Django Tutorial](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django/Tutorial_local_library_website)

## 📄 License
This project is intended for educational purposes. Please refer to MDN’s terms of use if you plan to reuse or distribute tutorial content.

