# Flask-uwsgi

## 起動

```
# make run
```

## 停止

```
# make stop
```

# 構成
```
.
├── Makefile
├── README.md
├── app
│   ├── Dockerfile
│   ├── requirements.txt
│   ├── src
│   │   ├── config
│   │   │   ├── __init__.py
│   │   │   └── default.py
│   │   ├── run.py
│   │   ├── server
│   │   │   ├── __init__.py
│   │   │   └── hoge
│   │   │       ├── __init__.py
│   │   │       └── hoge_api.py
│   │   └── tests
│   │       ├── __init__.py
│   │       └── test_hoge.py
│   └── uwsgi.ini
├── docker-compose.yml
```
