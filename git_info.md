# Работа с удалёнными репозиториями

git log –graph - показывает историю коммитов в виде дерева


git clone <url адрес удалённого репозитория> - копирует внешний репозиторий на локальный ПК.

git pull - Это составная команда. Она выгружает изменения из связанного удалённого репозитория и объединяет их с локальной версией.

git push - отправляет локальную версию репозитория на связанный внешний репозиторий.

git remote - показывает связанные репозитории

git remote add (name) (url) - связывает локальный репозиторий с внешним, если ранее они не были связаны.

git push --set-upstream (name) (branch-name) -связывает текущую ветку с удалённой.