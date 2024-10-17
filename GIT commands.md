# Команды GIT
```bash
git init # Инициализация репозитория
git status # Статус GIT
git add FILE # Добавляет файл в GIT
git commit -m "Сообщение коммита" # Делает коммит текущих изменений
git restore FILE # Восстанавливает файл
git rm FILE # Удаляет файл и добавляет в коммит
git log # Лог коммитов
git log --stat # Лог коммитов + изменения
git log -p -2 # Разница между двумя последними коммитами
git log --pretty=oneline # Лог коммитов в одну строку
git log --oneline # Лог коммитов в одну строку
git log --since=2.weeks # Лог коммитов за 2 недели
git diff # Последние изменения (До индексации)
git diff HASH_COMMIT HASH_COMMIT # Разница между двумя коммитами
git diff --staged # Последние изменения (После индексации)
git clean -fd # Очистка неотслеживаемых файлов и директорий
git restore --staged # Убирает файл из индексации
git reset --hard HEAD~COUNT # Возвращает COUNT коммит (ОПАСНО)
git reset HEAD~COUNT # Возвращает COUNT коммит c изменениями не в индексации (БЕЗОПАСНЕЕ --hard)
git stash # Прячет текущую индексацию

# git show BRANCH # Показывает историю изменений ветки
```

# Системные команды GIT
```bash
git cat-file -p HASH # Показывает содержимое файла по его хешу в objects
git cat-file -p BRANCH^{tree} # Выводит содержимое дерева ветки
```
