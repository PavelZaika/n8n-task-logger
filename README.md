# 📋 n8n Task Logger

Автоматическое логирование задач с помощью n8n.

## Что делает
- ⏰ Запускается по расписанию (каждую минуту)
- 📝 Генерирует запись: `Имя | Задача | Время`
- 💾 Сохраняет в файл `/files/task-log.txt`

## Быстрый старт

```bash
# Клонировать
git clone https://github.com/PavelZaika/n8n-task-logger.git
cd n8n-task-logger

# Запустить
docker compose up -d

# Открыть n8n
# http://localhost:5678
