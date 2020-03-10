# angular-docker-sample

## env
- Windows10
- Docker Desktop 2.2.0.3
- docker-compose
- visual studio code 1.42.1


## create folder
```
mkdir frontend/node_modules
```
## docker build
```
docker-compose build
```

## docker run
```
docker-compose up -d
```

## create angular project
```
# attach shell
cd ..
ng new frontend --skipGit=true
```

## start Angular
```
# attach shell
cd /frontend
ng serve --host=0.0.0.0
```

## docker stop
```
docker-compose down -v
```