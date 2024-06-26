# Docker Compose Проект: Веб-приложение с PostgreSQL

Этот проект представляет собой использование Docker Compose для запуска двух сервисов: веб-приложения на Flask и базы данных PostgreSQL. Веб-приложение представляет собой простое "Hello, World!", а база данных PostgreSQL используется для хранения данных.

## Структура проекта

- **app.py**: Основной файл веб-приложения на Flask.
- **requirements.txt**: Список зависимостей Python для веб-приложения.
- **Dockerfile_web**: Dockerfile для веб-приложения.
- **Dockerfile_db**: Dockerfile для базы данных PostgreSQL.
- **docker-compose.yml**: Файл Docker Compose для управления обоими сервисами.
- **README.md**: Этот файл, содержащий описание проекта и инструкции по запуску.

## Использование

1. **Сборка и запуск контейнеров**:

   ```bash
   docker-compose up -d
   ```

2. **Остановка и удаление контейнеров**:

   ```bash
   docker-compose down
   ```

3. **Доступ к веб-приложению**:

   После запуска контейнеров откройте браузер и перейдите по адресу `http://localhost` или `https://localhost` (если используется HTTPS).

4. **Доступ к базе данных**:

   Для подключения к базе данных PostgreSQL используйте следующие параметры:
   - **Хост**: localhost
   - **Порт**: 5432
   - **Имя пользователя**: postgres
   - **Пароль**: secretpassword


