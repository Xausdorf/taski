# Как запустить
1. Чтобы собрать образ нужно ввести команду в этой директории
```bash
docker build -t taski_backend .
```
2. Чтобы запустить контейнер с собранным образом нужно ввести
```bash
docker run -p 8000:8000 taski_backend
```
3. После этих шагов бэкенд станет доступен на `http://localhost:8000`