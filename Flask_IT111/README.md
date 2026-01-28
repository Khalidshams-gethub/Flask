# Flask Application

A modern Flask web application with database support, user authentication, and task automation capabilities.

## Project Description

This is a Flask-based web application designed to demonstrate best practices in Flask development. It includes features for:
- Routing and template rendering
- Database management with SQLAlchemy
- User authentication with Flask-Login
- Automated task scheduling with APScheduler
- Database migrations using Alembic

## Project Structure

```
Flask_IT111/
├── app.py              ← Entry point (root level)
├── requirements.txt
├── app/
│   ├── __init__.py     ← Contains create_app()
│   ├── routes.py
│   ├── models.py
│   └── ...
├── templates/
├── static/
└── migrations/
```

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Khalidshams-gethub/Flask.git
   cd Flask/Flask_IT111
   ```

2. **Create a virtual environment (optional but recommended):**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

## Running the Application

To start the Flask development server:

```bash
python app.py
```

The application will be available at `http://127.0.0.1:5000/`

### Notes
- The development server runs with debug mode enabled
- Hot reload is automatically enabled for development
- Do not use the development server in production

## Requirements

All dependencies are listed in `requirements.txt`:
- Flask 2.3.3
- Flask-SQLAlchemy 3.0.5
- Flask-Migrate 4.0.4
- Flask-Login 0.6.2
- python-dotenv 1.0.0
- APScheduler 3.10.4