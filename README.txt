docker-compose up -d --build
http://localhost
docker-compose down

📂 Структура проекта
app.py — основная логика Flask.
nginx.conf — конфиг прокси-сервера (80 порт -> 8080 внутри).
Dockerfile — инструкции по сборке образа (Python 3.10-slim + Gunicorn).
docker-compose.yml — связка Flask и Nginx сервисов.
static/ — CSS, JS и изображения.
templates/ — HTML шаблоны.
🛠 Технологии
Backend: Flask, Gunicorn
Proxy: Nginx
Infrastructure: Docker, Docker Compose
добавил сжатие видео
нужен домен и ssl
сделал фавикон
сделал общую локальную сеть докер на сервере установил ngnix для обработки
утсановил сертификаты ssl certbot
настроил CI/CD