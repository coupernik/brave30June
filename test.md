# Знакомство с GitHub-ом 

Привет, мир
Я работаю в Github

Чтобы увидеть список всех имеющихся веток, мы
вводим команду:
> **git branch** - увидим, какие ветки есть в моем репозитории  

Чтобы добавить новую ветку, используем команду:
> **git branch branch_name** - добавляет новую ветку с именем **branch_name**  

Чтобы создать изменения и его коммит, используем команду:
> **git commit -am "text"** - add + commit с комментом **text**  

Чтобы создать новую ветку и перейти в нее, используем команду:
> **git checkout -b branch_name** - добавляет и переносит нас в новую ветку с именем **branch_name**  

Чтобы удалить ветку, используем команду:
> **git branch -d branch_name** - удаляет ветку с именем **branch_name** с проверкой на merge

Чтобы удалить ветку без проверки на merge, используем команду:
> **git branch -D branch_name** - безоговорочно удаляет ветку с именем **branch_name**

Чтобы клонировать внешний репозиторий на  локальный ПК, используем команду:
> **git clone <url-адрес репозитория>**

Чтобы полученить изменения и слить с локальной версией, используем команду:
> **git pull**

Чтобы отправить локальную версию репозитория на внешний, используем команду:
> **git push**

