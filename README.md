# This is a test Flask application!

To run this directly on your machine:

```
# Create virtualenv and active
python3 -m venv venv
source venv/bin/activate

# Install requirements
pip install -r requirements.txt

# Run the application
FLASK_APP=app/main.py flask run

# You can view the webpage at http://127.0.0.1:5000/
```

To run this in a docker container:

```
docker build -t test-flask-app .
docker run --name test-flask-app -p 80:80 test-flask-app

# You can view the webpage at http://127.0.0.1/
```
