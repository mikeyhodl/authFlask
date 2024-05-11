# Flask Basic User Authentication

Use these commands to run the project

python -m venv env
source env/bin/activate
export FLASK_APP=app.py
pip instal-r requirements.txt
pip install email_validator
source .env
flask db init
flask db migrate
flask db upgrade
python manage.py run
