# Добрый день, уважаемые студенты! 
  При выполнении данной работы от вас требуется дополнить мой репозиторий, добавив в него свой файл с инструкцией по работе с git. Помните, что добавление файла - такой же процесс изменения репозитория, как и изменения внутри конкретных файлов и не пугайтесь этого :)

  P.S. Называйте добавляемые файлы своими фамилиями(только на английской раскладке), чтобы мне было проще их идентифицировать. И не забудьте сделать скрин окна с pullrequest, на сайт GB необходимо отослать именно этот скрин, чтобы работа была окончательно завершена.

  P.P.S. Не забывайте, что отправляем на pullrequest мы побочные ветки!

# Конспект с первого семенара
## Алгоритм сохранения изменений
* Внести изменения
* Shift + s
* git add 'название файла'
* git commit -m 'комментарий'
## Значение команд
* **git init** - *Инициализация репозитория.*
* **git log** - *Просмотр истории commit с комментариями.*
* **git status** - *Описывает тикущее состояние репозитория.*
* **git log --oneline** - *Просмотр истории commit с комментариями в кратком виде .*
* **git add** -  *Добавление отдельных файлов в область подготовленных файлов.*
* **git checkout** - *Переход на другой commit.*
* **git commit -m**- *команда для записи индексированных изменений в репозиторий.*
## Создание ветак 

* Для того чтобы создать ветку нужно ввести команду git branch "Название ветки".

* Для того чтобы перейти в ветку нужно ввести команду git checkout "Название ветки".

* Для удаления ветки нужно ввести команду git branch -d "Название ветки ".

* Для просмотра всех имеющихся веток нужно ввести команду git branch.

## Слияние ветак 

* Слияние ветак позволяет перенести всю информацию с побочного файла в основной.

* Для слияния веток нужно находится в ветке **master** и ввести команду git merge "Название ветки которую с которой хотите произвести слияние".

## Разрешение конфликтов 

![](%D0%9F%D1%80%D0%B8%D0%BC%D0%B5%D1%80%20%D0%BA%D0%BE%D0%BD%D1%84%D0%BB%D0%B8%D0%BA%D1%82%D0%B0.jpg) (Пример конфликта)

* Accept Current Change - сохранить только первую часть.

* Accept Incoming Change - сохранить только вторую часть.

* Accept Both Changes - сохранить обе части.

## Новые команды 

* git checkout "название ветки " - Позволяет перейти на другую ветку.
* git branch - Позволяет посмотреть кокие ветки у вас есть и на какой вы находитесь.
* git branch "Название" - Позволяет создать новую ветку.
* git merge - Позволяет объединить две ветки.
* git log --graph - отоброжает график всех веток.

## Связь локального сервера с сервисом GitHub
1. Для связи нужно саздать репозиторий на сервеси GitHub.
2. Связать локальный сервер с сервисом GitHub
  
   Инструкция
   
   1. git remote add origin "сылка"
   2. git branch -M main или master
   3. git push -u origin main
## Как выводить изменения с локального сервера в GitHab и наоборот
1. Для вывода данных из локального сервера на GitHub нужно команда git push.
2. Для того чтобы добавить новые изменения с GitHub на локальный сервер нужна команда git pull.
## Новые команда
* git pull - команда переносит с GitHub на локальный сервер новые изменения.
* git push - команда выводит данные с локального сервера на GitHub.
* git clone "ссылка" - команда позволяющия скопировать репозиторий на локальный сервер.


  