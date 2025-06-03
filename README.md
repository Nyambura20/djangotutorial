# Django Polls Tutorial

This project follows the official Django tutorial for building a simple polls app. It demonstrates how to set up a Django project, create models, use the admin interface, and interact with the database.

## Getting Started

1. **Clone the repository:**

   ```sh
   git clone https://github.com/your-username/djangotutorial.git
   cd djangotutorial
   ```

2. **Install dependencies:**
   Ensure you have Python 3 and pip installed. Then run:

   ```sh
   pip install django
   ```

3. **Apply migrations:**

   ```sh
   python manage.py migrate
   ```

4. **Create a superuser:**

   ```sh
   python manage.py createsuperuser
   ```

5. **Run the development server:**

   ```sh
   python manage.py runserver
   ```

6. **Access the admin site:**
   Open [http://127.0.0.1:8000/admin/](http://127.0.0.1:8000/admin/) and log in with your superuser credentials.

## Features

- Polls app with Question and Choice models
- Admin interface for managing polls
- Database setup using SQLite (default)

## Time Zone

This project is set to the `Africa/Nairobi` time zone for Mombasa, Kenya.

## References

- [Django Documentation](https://docs.djangoproject.com/en/4.2/)
- [Django Tutorial Part 1 & 2](https://docs.djangoproject.com/en/4.2/intro/tutorial01/)

---

Feel free to continue with the next parts of the Django tutorial!
