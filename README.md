# Django Polls App

This is a simple web-based polling application built with Django, following the official Django tutorial. It demonstrates models, views, templates, forms, admin customization, static files, and integration with third-party packages like Django Debug Toolbar.

## Features

- Create and manage poll questions and choices
- Vote on polls and view results
- Admin interface with customizations
- Static files for custom styles and images
- Automated tests for models and views
- Debugging with Django Debug Toolbar

## Setup

1. **Clone the repository:**

   ```sh
   git clone https://github.com/your-username/djangotutorial.git
   cd djangotutorial
   ```

2. **Create and activate a virtual environment:**

   ```sh
   python3 -m venv venv
   source venv/bin/activate
   ```

3. **Install dependencies:**
   Ensure you have Python 3 and pip installed. Then run:

   ```sh
   pip install -r requirements.txt
   ```

   Or manually:

   ```sh
   pip install django django-debug-toolbar
   ```

4. **Apply migrations:**

   ```sh
   python manage.py migrate
   ```

5. **Create a superuser:**

   ```sh
   python manage.py createsuperuser
   ```

6. **Run the development server:**

   ```sh
   python manage.py runserver
   ```

## Usage

- Visit `http://127.0.0.1:8000/polls/` to use the polls app.
- Visit `http://127.0.0.1:8000/admin/` to access the admin interface.
- The Django Debug Toolbar will appear on the right side of the page in DEBUG mode.

## Project Structure

- `polls/` - Django app containing models, views, templates, static files, and tests
- `mysite/` - Project configuration
- `templates/` - Custom project-level templates (e.g., admin overrides)
- `static/` - Static files (CSS, images)

## Testing

Run all tests with:

```sh
python manage.py test polls
```

## License

This project is for educational purposes, based on the [Django tutorial](https://docs.djangoproject.com/en/stable/intro/tutorial01/).

---

Feel free to continue with the next parts of the Django tutorial!
