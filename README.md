# Python Hello Demo

Минимальное Python HTTP-приложение для проверки Python deployment template.

## Запуск приложения

- Port: `8080`
- HTML page: `/`
- Проверка состояния: `/health`
- Зависимости: нет

## Локальный запуск

```bash
python main.py
```

Необязательные переменные:

```bash
APP_NAME="Python Hello App" ENV_NAME=production PORT=8080 python main.py
```

## Настройки шаблона

Рекомендуемые значения deployment template:

- Base image: `python:3.12-alpine`
- Root directory: `.`
- Output directory: `.`
- Install command: пусто
- Build command: пусто
- Run command: `python main.py`
- Application port: `8080`
