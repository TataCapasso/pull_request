# Гайд по GIT
Иницилизация **нового** репозитория GIT, начинает отслеживать существующий каталог:
```sh
git init
```
Добавляет изменение из рабочего каталога в раздел проиндексированных файлов:
```sh
git add <file>
```
Отображает состояние рабочего каталога и раздела проиндексированных файлов:
```sh
git status
```
Операция по добавлению всех проиндексированных файлов в репозиторий *(в кавычках пишем сообщение)*:
```sh
git commit -m "message" 
```
*чтобы изменить последний комментарий:* 
```sh
git commit --amend
```

Используется для просмотра истории коммитов, начиная с самого свежего и уходя к истокам проекта:
```sh
git log
```
Просмотр сокращенной версии коммитов:
```sh
git log --oneline
```
Переименование ветки
```sh
git branch -M name
```
Позволяет перемещаться между ветками, созданными командой git branch:
```sh
git checkout_<namber_version>
```
* Позволяет переключится на действующую ветку:
```sh 
    git checkout master
```
Команды для настройки значений конфигурации Git на глобальном и локальном уровнях проекта:
* на глобальном уровне присваивает имя и адрес пользователя:
```sh
1. git config --global user.name "my name"
2. git config --global user.email "my email"
```
* показывает имя и адрес пользователя:
```sh
1. git config user.name 
2. git config user.email
```
Вычисление разницы между любыми двумя Git деревьями:
```sh 
git diff
```
Узнать **директорию** файла:
* для Windows
```sh
   dir
```
* для Linux и MacOs
```sh
   ls
```
Команда командной строки для изменения рабочего каталога, путь к катологу:
* для Windows:
```sh
   cd C:\folder_name
```
* для Linux и MacOs:
```sh
   pwd
```
Удаление ненужных файлов:
* для Windows:
```sh
   dell <file>
```
* для Linux и MacOs:
```sh
   rm <file>
```
Сбросить изменени:
```sh
git restore --staged <file>
```
Копировать внешний репозиторий на свой ПК
```sh
git clone <web>
```
Cкачать все из текущего репозитория и автоматически сделать merge с нашей версией
```sh
git pull <web>
```
Отправить свою версию репозитория во внешний репозиторий
```sh
git push
```
Команда для предложения изменений, запрос на вливание изменений в репозиторий
```sh
pull request
```
Информация об удаленных репозиториях
```sh
git remote -v
git remote show
```
Выкачка и слияние с нашими текущими изменениями
```sh
git pull = -rebase
```
Создать новую папку в репозитории:
```sh
mkdir <name>
```
Подняться на уровень выше в репозитории:
```sh
cd..
```
Как сделать pull request:
```sh
* Делаем (ответвление) репозитория fork
* Делаем git clone версии репозитория СВОЕЙ
* Создаем новую ветку и в НЕЕ вносим свои изменения
* Фиксируем изменения (делаем коммиты)
* Отправляем свою версию в свой GitHub
* На сайте GitHub нажимаем кнопку pull request
```
Как настроить совместную работу:
```sh
1. Создать аккаунт на GitHub.com.
2. Создать локальный репозиторий.
3. “Подружить” ваш локальный и удалённый репозитории. GitHub при создании нового репозитория подскажет, как это можно сделать.
4. Отправить (push) ваш локальный репозиторий в удалённый (на GitHub), при этом, возможно, вам нужно будет авторизоваться на удалённом репозитории.
5. Провести изменения “с другого компьютера”.
6. Выкачать (pull) актуальное состояние из удалённого репозитория.
```