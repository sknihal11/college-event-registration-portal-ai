git clone https://github.com/sknihal11/college-event-registration-portal-ai.git
cd college-event-registration-portal-ai

python --version

python -m venv venv
venv\Scripts\activate

pip install -r requirements.txt

python manage.py makemigrations
python manage.py migrate

python manage.py runserver

App: http://127.0.0.1:8000/

Admin: http://127.0.0.1:8000/admin/
