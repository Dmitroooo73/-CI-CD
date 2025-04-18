# ping to trigger CD
# FastAPI User API with CI/CD

Проект реализует REST API для управления пользователями на базе FastAPI.  
В рамках лабораторной работы настроен полный процесс CI/CD с использованием GitHub Actions и Docker.

Функциональность API

- Получение пользователя по email
- Создание пользователя
- Удаление пользователя
- Обработка ошибок (404, 409)

Технологии

- Python 3.12, FastAPI
- Docker, Docker Compose
- GitHub Actions (CI/CD)
- pytest

CI/CD

- CI: автоматический запуск тестов при push
- CD: сборка и публикация Docker-образа в Docker Hub при успешном CI в ветке main

Запуск проекта
uvicorn src.main:app --reload

Или через Docker:
docker compose up --build
