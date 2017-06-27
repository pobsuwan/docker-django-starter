# Development Django with Docker

### Descriptions
* Django => 1.11
* Postgres

### Prerequisites
* Python 2.7 or 3.x,
* docker
* docker-compose

### How to start django
```
docker-compose up
```

### How to execute command to web container 
```
docker-compose run web `command`
```

docker-compose run web python3 manage.py migrate
docker-compose run web python3 manage.py createsuperuser