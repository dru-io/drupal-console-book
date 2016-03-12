# config:export:view
The **config:export:view** command Export a view in YAML format inside a provided module to reuse in other website.

**Использование:**
```
$ drupal config:export:view [arguments] [options]
$ cev  
```

## Доступные опции
Опция | Описание
-------|-------------
--module | The Module name.
--optional-config | Export view as an optional YAML configuration in your module
--include-module-dependencies | Include module dependencies in module info YAML file

## Доступные аргументы
Аргумент | Описание
---------|-------------
view-id | View ID
