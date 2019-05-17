## Basic template for a Flask app in a Docker container

### Running application
```
docker-compose up -d
```

### Visit in browser:
http://localhost:5000

### Updating app after making changes:
```
docker-compose build
```
then
```
docker-compose up -d
```

### Issues with app updating:
```
docker-compose build --no-cache
```