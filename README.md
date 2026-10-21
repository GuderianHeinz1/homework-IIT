# homework-IIT

Развёрнутое приложение: https://homework-iit-latest.onrender.com/

Каждый push в ветку master запускает GitHub Actions: образ собирается, затем через Deploy Hook запускается новый деплой на Render (.github/workflows/deploy.yml).

Статический HTML/CSS сайт, докеризованный с помощью nginx.

## Запуск

```bash
docker pull dmitriy2504/homework-iit
docker run -p 8080:80 dmitriy2504/homework-iit
```

Открой http://localhost:8080
