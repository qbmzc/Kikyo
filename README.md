# Kikyo
___

_一个简单的博客系统_  

```bash
export FLASK_APP=flaskr
# flask init-d
flask init-db
# Initialized the database.
```

```pip
pip freeze >requirements.txt  
pip install -r requirements.txt
```

```md
uwsgi --socket 127.0.0.1:5000 --wsgi-file app.py --callable app --processes 4 --threads 2 --stats 127.0.0.1:9191
```