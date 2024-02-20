### Django Debug Toolbar bug reproduction

#### Setup

```
pip install -r requirements.txt
python manage.py runserver
```

#### Bug

- GET http://127.0.0.1:8000/movies/ => djdt works
- OPTIONS http://127.0.0.1:8000/movies/ => no djdt
