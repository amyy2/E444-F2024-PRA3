# ECE444 PRA3

TDD and deploying web applications

Start virtual environment:
```
python3 -m venv env
source env/bin/activate
```

Install requirements:
```
pip install -r requirements.txt
```

Run Flask app:
```
FLASK_APP=project/app.py python -m flask run -p 5001
```

Run tests:
```
python -m pytest
```