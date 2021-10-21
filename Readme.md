# ДЗ в интересах 3 лекции ВКВ

## Задача 1.
1.	Создали аккаунт на Github.com  
2.	Создать локальный репозиторий (создать папку, вызвать команду git init, создать файл, внести изменения и создать хотя бы один коммит)  
3.	"Подружить" ваш локальный и удаленный репозитории. (Github при создании нового репозитория подскажет как это можно сделать)  
4.	Отправить (git push) ваш локальный репозиторий в удаленный (на Github), при этом вам, возможно, нужно будет авторизоваться на удаленном репозитории.  
5.	Провести изменения "с другого компьютера". (можно сделать все на Github)  
6.	Выкачать (git pull) актуальное состояние из удаленного репозитория.  
***

# Выполнение

### *Создание и открытие папки Lesson 3*  
    PS E:\Учеба\Разработчик\Введение в контроль версий\Lesson 3> git status   
        fatal: not a git repository (or any of the parent directories): .git  
### *Создание репозитория*  
    PS E:\Учеба\Разработчик\Введение в контроль версий\Lesson 3> git init  
        Initialized empty Git repository in E:/Учеба/Разработчик/Введение в контроль версий/Lesson 3/.git/  
### *Создание файла Readme.md, ввод и сохранение текста, добавка версионности*  
    PS E:\Учеба\Разработчик\Введение в контроль версий\Lesson 3> git add .\Readme.md  
### *Создание коммита*  
    PS E:\Учеба\Разработчик\Введение в контроль версий\Lesson 3> git commit -m "Cоздание рипозитория в целях задачи 1 лекции 3"  
        [master (root-commit) fa740a8] Cоздание рипозитория в целях задачи 1 лекции 3  
         1 file changed, 9 insertions(+)  
### *Указание удаленного репозитория*  
    PS E:\Учеба\Разработчик\Введение в контроль версий\Lesson 3> git remote add origin https://github.com/Yas-son/-3-.git  
### *Указание главной ветви*  
    PS E:\Учеба\Разработчик\Введение в контроль версий\Lesson 3> git branch -M main  
### *Отправка репозитория*  
    PS E:\Учеба\Разработчик\Введение в контроль версий\Lesson 3> git push -u origin main  
        Enumerating objects: 5, done.  
        Counting objects: 100% (5/5), done.  
        Delta compression using up to 8 threads  
        Compressing objects: 100% (2/2), done.  
        Writing objects: 100% (3/3), 786 bytes | 786.00 KiB/s, done.  
        Total 3 (delta 0), reused 0 (delta 0), pack-reused 0  
            To https://github.com/Yas-son/-3-.git  
            fa740a8..b43e32f  main -> main  
        Branch 'main' set up to track remote branch 'main' from 'origin'.  
### *Обновление страницы в GitHub и проверка, что файл сохранился*  
# Конец выполнения!  
***
