FROM python:3.13 

WORKDIR /app

# Устанавливаем зависимости
COPY ./backend/requirements.txt  /app/
RUN pip install --no-cache-dir --upgrade pip
RUN pip install --no-cache-dir -r requirements.txt

COPY ./backend/. /app/

# Открываем порт
EXPOSE 8000

# Запускаем сервер
CMD ["python", "manage.py", "runserver", "0.0.0.0:8000"]