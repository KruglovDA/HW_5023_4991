# руководство пользователя по работе с Git
## 1.Основные команды
* git init- инициализирует репозиторий
* git add - добавляет файл в репозиторий
## 2.Работа с ветками
* git branch показывает список веток
* git branch_name создает ветку с именем branch_name
* git checkout branch_name переключается на ветку с branch_name
* git checkout -b branch name создает ветку с именем branch_name и переключается на нее
* git merge branch_name сливает ветку branch_name с текущей на которой находимся 
* git brange -d branch_name удаляет ветку branch_name
* git log --graph наглядно показывает ветки
* git commit --amend -m name изменяет название последнего коммента на name
## 3.Работа с удаленными репозиториями
* git pull - получение данных из удаленного репозитория
* git push - отправка данных с локального в удаленный репозиторий
конец