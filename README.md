## Проект на django
В текущей директории выполнить команды
```
docker build --tag django_docker_project ./
docker run -p 8000:8000 -d --name django_docker django_docker_project
```
перейти в http://localhost:8000/api/v1/ - если проект разворачивается локально
перейти в http://IP-сервера:8000/api/v1/ - если проект разворачивается на сервере

