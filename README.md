# Flask Register/Login Dashboard App

A simple Flask web application with user registration, login, and dashboard functionality.

## Features

- User registration with email and username validation
- Secure login with password hashing
- Session management
- Beautiful, responsive UI
- SQLite database for user storage

## Installation

1. Create a virtual environment:
```bash
python -m venv venv
```

2. Activate the virtual environment:
```bash
# On Windows:
.\venv\Scripts\activate

# On macOS/Linux:
source venv/bin/activate
```

3. Install the required dependencies:
```bash
pip install -r requirements.txt
```

4. Run the application:
```bash
python app.py
```

5. Open your browser and go to `http://localhost:5000`

## Usage

1. **Register**: Create a new account with username, email, and password
2. **Login**: Sign in with your username and password
3. **Dashboard**: Access your personal dashboard after successful login
4. **Logout**: Sign out from your account

## File Structure

- `app.py` - Main Flask application
- `templates/` - HTML templates
  - `base.html` - Base template with styling
  - `login.html` - Login page
  - `register.html` - Registration page
  - `dashboard.html` - Dashboard page
- `requirements.txt` - Python dependencies
- `users.db` - SQLite database (created automatically)

## Security Features

- Password hashing using Werkzeug
- Session management
- Input validation
- SQL injection protection
- CSRF protection through Flask sessions
