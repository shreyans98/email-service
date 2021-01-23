Getting it running locally

git clone https://github.com/shreyans98/email-service.git
cd email-service/

# setup a virtual environment
python3 -m venv virtualenv

# prep the dev server
./virtualenv/bin/pip install -r requirements.txt

# start the dev server
./virtualenv/bin/python manage.py runserver
