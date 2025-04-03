# SudyBud

SudyBud is a Django MVT application inspired by Discord. It provides a platform for real-time communication, user management, and community interactions.

## Features
- User authentication and management
- Real-time messaging
- Role and permission system

## Technologies Used
- Django (MVT architecture)
- Django REST Framework
- SQLite (Database)

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/anitapajic/sudybud.git
   cd sudybud
   ```
2. Create and activate a virtual environment:
   ```sh
   python -m venv venv
   source venv/bin/activate  # On Windows use: venv\Scripts\activate
   ```
3. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
4. Apply migrations:
   ```sh
   python manage.py migrate
   ```
5. Run the development server:
   ```sh
   python manage.py runserver
   ```

## Usage
- Visit `http://127.0.0.1:8000/` in your browser.
- Create an account and start chatting.

---

