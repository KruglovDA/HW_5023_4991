# Git manual
 
 
 * 1. Как задать имя пользователя и адрес электронной почты
 
   git config --global user.name "Имя"
 
   git config --global user.email "электронная почта"


* 2. Проверка статуса репозитория
      
     git status

* 3. Создании коммита в репозитории 
 
   git commit  
 
   git commit -m

* 4 Переименование файлов

  git mv dir1/somefile.js dir2

* 5 Изменение последнего коммита

  git commit --amend -m "Updated message for the previous commit"

* 6 Откат последнего коммита

  git revert HEAD


