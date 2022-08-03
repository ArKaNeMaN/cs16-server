# [WIP] Counter Strike 1.6 Server

Докеризированный Counter Strike 1.6 сервер.

## Переменные среды

| Переменная            | По умолчанию          | Описание
| :---                  | :---                  | :---
| `CONTAINERS_NAME`     | `main`                | Префикс названий контейнеров
| `FORWARD_SERVER_PORT` | `27015`               | Внешний порт сервера
| `DB_ROOT_PASSWORD`    | `g4nfhk4hjgf4kfg4`    | Пароль root-пользователя БД
| `DB_DATABASE`         | `csserver`            | Название базы данных
| `DB_USERNAME`         | `csserver`            | Имя пользователя БД
| `DB_PASSWORD`         | `qwerty`              | Пароль пользователя БД
| `FORWARD_FASTDL_PORT` | `27115`               | Внешний порт сервера быстрой загрузки
