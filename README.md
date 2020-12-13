# LR6
Елизавета Азаретова 4916 Лабораторная работа№6
Цель работы:изучение базовых возможностей системы

управления версиями, опыт работы с Git Api, опыт работы с локальным и

удаленным репозиторием.

Ход работы:

На сайте GitHub сделала копию https://github.com/Kurtyanik/LR6/

![Копированный репозиторий](скриншоты/1.png)

С помощью команды _cd laba6_ в консоли Git Bash перешёл в созданную папку laba6

Использовал команду _git init_ чтобы инициализировать гит в данной папке

![](скрип/s2.png)

Командой _git cjnfing —global user.name/email_ внес свои данные.

![](скрип/s3.png)

Командой _git remote add origin_ связал папку с удалённым репозиторием на сайте GitHub

![](скрип/s4.png)

Затем через графический интерфейс GitHub добавил новый файл _file.txt_ в удалённый репозиторий в ветку __master__

![](скрип/s21.png)

![](скрип/s22.png)

![](скрип/s20.png)

Пользуясь командой _git pull origin master_ загрузил изменения из удалённого репозитория в локальный

![](скрип/s4.png)

Командой _git log_ получил список операций/коммитов

![](скрип/s5.png)

Используя _git show_ получил более подробную информацию по последнему изменению

![](скрип/s6.png)

Командой _git checkout —track branch1_ переключился на другую ветку **branch1**

Попытался выполнить слияние веток **master** и **branch1** командой _git merge branch1_ и получил конфликт в файле mergefile.txt

![](скрип/s7.png)

Вручную изменил файл mergefile.txt, вызвавший ошибку слияния и выполнил коммит и выполнил слияние веток **master** и **branch1**

![](скрип/s8.png)

Затем удалил ветку **branch1** командой _git branch -d_ и запушил всё в удалённый репозиторий командой _git push origin master_

![](скрип/s9.png)

Затем сделал несколько изменений, добавив новые файлы

![](скрип/s10.png)

![](скрип/s11.png)

Командой _git reset —hard HEAD~1_ выполнил откат последнего коммита - добавления файла **Новый файл**

![](скрип/s12.png)

Пользуясь командой _git checkout -b otchet_ создал новую ветку **otchet**

![](скрип/s13.png)

Текущая история _git log —graph_ . Аргумент —graph позволяет графически изобразить ветки и коммиты на них

![](скрип/s14.png)

С помощью команды _git add ._ подготовил все новые файлы в папке **lab6** к пушу

![](скрип/s15.png)

Запушил файлы скриншотов в удалённый репозиторий

Оформляю отчёт в файле **README.md**

![](скрип/s30.png)

Все файлы скриншотов лежат в папке **скрип**

Вывод:изучил базовые возможности системы
управления версиями, получил опыт работы с Git Api и опыт работы с локальным и
удаленным репозиторием.
