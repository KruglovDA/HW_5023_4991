# Туториал
## Работа с удаленными репозиториями 
* git pull - Git вначале забирает изменения из указанного удалённого репозитория, а затем пытается слить их с текущей веткой.
* git push - используется для установления связи с удалённым репозиторием
* git clone - позволяет склонировать внешний репозиторий на наш ПК

# Основные команды
* git init - инициализирует репозиторий
* git status - получить информацию от git о его текущем состоянии
* git rm используется в Git для удаления файлов из индекса и рабочей копии
* git commit -m "message"
* git log - вывод на экран истории всех коммитов с их хеш-кодами
* git checkout - переход от одного коммита к другому 
* git checkout master - вернуться к актуальному состоянию и продолжить работу
* git diff - увидеть разницу между текущим файлом и закоммиченым файлом

# Работа с ветками
* git branch branch_name - создает ветку с именем branch_name
* git branch - показывает список веток
* git checkout branch_name - переключается на ветку branch_name
* git checkout -b branch_name - создает ветку brench_name и переключается на нее
--delete - сокращенный вариант записи удаления ветки
* git branch -d branch_name - удаляет ветку branch_name

# Синтаксис языка Markdown
1) `#` Заголовок - выделение заголовков. Количество символов `#` задает уровень заголовка (поддерживается 6 уровней) 
2) = или - – подчёркиванием этими символами (не менее 3 подряд) выделяют заголовки первого (“=”) и второго (“-”) уровней.
**Полужирное начертание** (**)
__Полужирное начертание__(__)
_Курсивное начертание_(_)
~~Зачёркнутый текст~~(~~)

