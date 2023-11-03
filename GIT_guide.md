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
Используется для просмотра истории коммитов, начиная с самого свежего и уходя к истокам проекта:
```sh
git log
```
Позволяет перемещаться между ветками, созданными командой git branch:
```sh
git checkout_<namber_version>
```
* Позволяет переключится на действующую ветку:
```sh 
    git checkout master
```

git diff
git config --global user.name "my name"
git config --global user.email "my email"
git config user.name 
git config user.email
cd 
dir
ls
cd C:\folder_name
pwd
rm <file>
dell <file>
git log --oneline
git restore --staged<file>
