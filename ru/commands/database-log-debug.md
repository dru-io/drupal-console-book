# database:log:debug
The **database:log:debug** command Display current log events for the application

**Использование:**
```
$ drupal database:log:debug [arguments] [options] 
```

## Доступные опции
Опция | Описание
-------|-------------
--type | Filter events by a specific type
--severity | Filter events by a specific level of severity
--user-id | Filter events by a specific user id
--reverse | Reverse the order of events
--limit | Limit results to a specific number
--offset | Starting point of a limit

## Доступные аргументы
Аргумент | Описание
---------|-------------
event-id | DBLog event ID
