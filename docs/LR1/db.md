# База данных

Модуль для настройки базы данных и создания сессий.

## Функции

### init_db()
Создает все таблицы в базе данных.

### get_session()
Создает сессию базы данных и управляет ее временем жизни.

## Конфигурация

Настройка подключения к базе данных происходит через переменную окружения `DB_URL`, определенную в файле `.env`:

```env
DB_URL = postgresql://postgres:postgres@localhost:5432/finances
```