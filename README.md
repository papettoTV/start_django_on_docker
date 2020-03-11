# start django on docker

## About

Build python3.8 and django environment on Ubuntu on docker

## Install & Run

```
docker-compose up --build
```

## Access

```
http://0.0.0.0:8000/polls/
```


## Console Debug

```
docker run -it -v ${PWD}:/app -p 8000:8000 django
python3.8 manage.py runserver 0.0.0.0:8000
```
