# yaml:split
The **yaml:split** command Split a YAML file using indent as separator criteria

**Использование:**
```
$ drupal yaml:split [arguments] [options] 
$ ys  
```

## Доступные опции
Опция | Описание
-------|-------------
--indent-level | Split YAML file using a specific indent level
--file-output-prefix | commands.yaml.split.options.file-output-prefix
--file-output-suffix | commands.yaml.split.options.file-output-suffix
--starting-key | YAML Key from where start split - useful to extract partial elements
--exclude-parents-key | Exclude the "parents" key from the generated file

## Доступные аргументы
Аргумент | Описание
---------|-------------
yaml-file | commands.yaml.split.value.arguments.yaml-file
