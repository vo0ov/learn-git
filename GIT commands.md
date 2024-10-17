# Команды GIT
```bash
git init # Инициализация репозитория
git status # Статус GIT
git add FILE # Добавляет файл в GIT
git commit -m "Сообщение коммита" # Делает коммит текущих изменений
git restore FILE # Восстанавливает файл
git rm FILE # Удаляет файл и добавляет в коммит
git log # Лог коммитов
```

# Системные команды GIT
```bash
git cat-file -p HASH # Показывает содержимое файла по его хешу в objects
git cat-file -p BRANCH^{tree} # Выводит содержимое дерева ветки
```
