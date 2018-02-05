# Django Login form in Bootstrap 4 modal

Djanog login form rendering and updating in Bootstrap 4 modal via Ajax.

## Running Locally

### 1. Setup

```bash
git clone https://github.com/trco/django-bs4-modal-login.git
```

Create virtual environment and install requirements.

```bash
pip install -r requirements.txt
```

```bash
python manage.py migrate
```

### 2. Testing Login modal

```bash
python manage.py runserver
```
#### Login credentials

| User role     | Username     | Password     |
| :-------------|:-------------|:-------------|
| User          | user1234     | demo1234     |
| Admin         | admin1234    | demoadmin    |



After you are logged in as Admin you can create new Users at http://127.0.0.1:8000/admin/.
