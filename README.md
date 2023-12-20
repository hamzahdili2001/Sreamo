# Sreamo
A streaming website using Django

## Installation
1. Clone the repository:
```bash
git clone https://github.com/hamzahdili2001/Sreamo.git
```


2. Create and activate a virtual environment (optional but recommended):
```bash
python -m venv venv
```

On windows:
```bash
venv\Scripts\activate
```
On linux/Mac OS:
```bash
source venv/bin/activate
```


3. run `pip install -r requirements.txt`

## Run Django Server
1. Apply migrations:
```bash
python manage.py makemigrations
python manage.py migrate
```
2. Run the Development Server:
```bash
python manage.py runserver
```

Access the admin panel by visiting [http://127.0.0.1:8000/admin/] in your web browser. Log in with the superuser credentials you created earlier.


3. Login:
username: `admin`
password: `admin`
