# ECE444 PRA3

TDD and deploying web applications

## Start virtual environment:
```
python3 -m venv env
```

Linux/MacOS:
```
source env/bin/activate
```

Windows:
```
env\Scripts\activate
```

## Install requirements:
```
pip install -r requirements.txt
```

## Run Flask app:

Linux/MacOS:
```
FLASK_APP=project/app.py python -m flask run -p 5001
```

Windows:
```
flask --app project/app run
```

## Run tests:
```
python -m pytest
```
