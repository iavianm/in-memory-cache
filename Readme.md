# Cache Library

## Описание
Этот пакет предоставляет in-memory кэш с методами:
- `Set(key string, value interface{})` — запись значения в кэш по ключу.
- `Get(key string)` — получение значения из кэша по ключу.
- `Delete(key string)` — удаление значения из кэша.

## Установка
Если у вас ещё нет файла go.mod в проекте, создайте его:
```bash
go mod init <module-name>
```

Установите пакет с помощью команды:
```bash
go get github.com/iavianm/in-memory-cache@v1.0.1
```