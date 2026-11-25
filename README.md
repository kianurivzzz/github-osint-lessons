# github-osint

Утилита собирает открытую информацию о пользователе GitHub и присылает сводку в Telegram. В сводку попадают данные профиля, список публичных репозиториев и адреса почты из коммитов.

## Установка

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

## Запуск

Скопируй `.env.example` в `.env`, впиши свои токены и передай логин.

```bash
python main.py octocat
```

## Тесты

```bash
pytest -v
```

## Как предложить изменение

Порядок работы описан в [CONTRIBUTING.md](CONTRIBUTING.md). Об уязвимостях сообщай по [SECURITY.md](SECURITY.md).
