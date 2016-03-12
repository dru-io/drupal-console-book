# config:override
The **config:override** command Override config value in active configuration.

**Использование:**
```
$ drupal config:override [arguments] 
```

## Доступные аргументы
Аргумент | Описание
---------|-------------
config-name | Configuration name.
key | Key
value | Value

## Examples
* Set the Contact module flood limit to 10.
```
$ drupal config:override contact.settings flood.limit 10
```
