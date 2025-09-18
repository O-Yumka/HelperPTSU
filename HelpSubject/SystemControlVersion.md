## хранить и востанавливать код 

* репозиторий локальный/удаленый 
* отслеживает все изменения - коммиты
* сохраняет историю комитов
* обеспечивает работу в колективе

## хранение на сервере
* минусы
* всё храниться на одном сервере
* затруднена работа над одним файлом

## распределеный системы контроля версии
* у каждого есть копия репозитория
* одновременное взаимодействие с несколькими репозиториями

# основные команды гита 

* git help / git help <command>
* git init (пустой репозиторий)
* git status  (untract файл не отслеживается) (Added)
* git pull вытягивает (1 git fetch) (2 git merge)
* git push
* git add <file name/dir name>  ; git add all / git add * / git add .
* git reset <filename/dirname>
* git commit -m ""
* git diff <namefile> опказывает изменения
* git log лог комитов
* git blame <nameFile> лог изменений 

# начальная настройка 
Имя пользователя и почта 
* git config --global user.email "you@ex.com"
* git config --global user.name "OLEG"

# работа с удаленным репозитриям 
* git remote add <name> <emale> (url)
* git push <name/emal> [branch]
* git pull <имя удаленой дириктории> - получить все комиты из удаленого репозиториz и слить с рабочей веткой
* git clone <(URL)>
* git revert <индифектор комита> откат изменения комита
* git reset *СНОСИТ ИЗМЕНЕНИЯ БЕЗ ВОЗМОЖНОСТИ ОТКАТА* 

# работы с ветками 
* git branch <nameBranch> создаёт
* git checkout <main> переключается 
* git branch -l
* git push origin 
* git merge <mainName>