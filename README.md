# Git команды

## Первым делом

1. *Скачать* [Git](https://git-scm.com/downloads)  
2. Настроить Git. 
```
git config user.name "Your name"
git config user.email 'email'
```
3. Зайти в папку, где будет или есть твой __Проект__
4. Прописать команду: 
```
git init
```
5. Создать файлы или папки (если их не было) и начать их отслеживать 
```
git add --all # Если нужно добавить все файлы
git add . # Если нужно добавить текущую папку
git add readme.txt # Если нужно добавить конкретный файл
```  
Теперь файлы и папки отслеживаются. Также это можно проверить с помощью команды: 
```
git status
```

## Вторым делом
1. Сделать коммит: 
```
git commit -m 'Изменения'
```
Он нужен для фиксации изменений, то есть он сохранит все что было сделано и в дальнейшем ты сможешь откатиться к этой версии своего проекта.
2. Также свой __Проект__ можно выкладывть на GitHub. Для этого нужно связать репозиторию на GitHub с локальной. Для этого 
```
git remote add origin 'SSH ссылка на репозиторий в GitHub'
git push origin master или main
```
