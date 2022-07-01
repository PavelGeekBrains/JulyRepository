# My first remote repository

Эта строка добавлена в локальном репозитории

Эта строка добавлена в удаленном репозитории

Это строка добавлена Августом



# **GID инструкция по применению**

## **Первый семинар**

**Статус отслеживаемого файла**

* U - Untracked - *неотслеживаемые файлы*

* A - Added - *добавлен в index*

* M - Modified - *модифицированнный*

**Управление клавишами**

* вызов предыдущей команды - *стрелка вверх*

* вызов файла - *две первые буквы файла клавиша tab*

* сохранение - *command + S*

* посмотреть скрытые файлы - *[cmd]+[Shift]+[.]*

**Команды управления GID**

1. git init - *создание репозитория в текущей папке*

2. git status - *отражает текущее состояние репозитория*

3. git add имя файла - *добавление файла в отслеживание*

4. git add* - *добавить всех файлов папки*

5. git commit -m "комментарий" - *создание комментария*

6. git commit --amend -m "комментарий" - *внесение изменений в последний комментарий*

7. git log - *вызоз всех версий с изменениями*

8. git checkout имя версии 4 символа - *переход между версиями*

9. git checkout master - *возврат к текущей версии*

10. git rm --cached имя файла - *удалить файл из отслеживания, статус файла измениться на "U" - Untracked*
11. git clean -fd - *удаление неотслеживаемых файлов*

12. rm -rf .git - *отмена команды git init, удаляем файл .git из каталога (папки)*

**Алгоритм сохранения файла и комментария**

* Command + S - git add (имя файла) - git commit -m "Текст комментария"

**Полезные команды**

* clear - *очистить терминал*

* cd - *изменение директории*

* q - *выход из комментариев*

## **Второй семинар**

_Цель семинара - работа с ветками и разрешение конфликтов при слиянии._

**Команды управления ветками - branch**

1. git branch - _отображает список существющих ветвей, активная ветка выделена (*) и зеленым цветом_

2. git branch master - _главная ветвь файла_

3. git branch имя ветки - _создание новой ветви_

4. git checkout имя ветви - _переход на ветку с указаным именем_

5. git merge имя ветви - _слияние ветви с вышестоящей_

6. git branch -d имя ветви - _удаление ветви_

7. git log - _список комментариев по ветвям_

8. git log --graph - _графическое отображение ветвей_

**Способы разрешения конфликтов при слиянии веток**

1. Accept Current Change - *принять текущее изменение*

2. Accept Incoming Change - *принять входящее изменение*

3. Accept Both Changes - *принять оба изменения*

4. Compare Changes - *сравнить изменения*

Например: Accept Incoming Change

![branch!](branch.jpg)

Например: Accept Both Changes

![second_seminar!](second_seminar.jpg)

![second_01!](second_01.jpg)

![second_02!](second_02.jpg)

Например: Accept Current Change

![third_seminar!](third_seminar.jpg)

![third-01!](third-01.jpg)

## **Третий семинар**

_Цель семинара -_научиться обмениваться проектами с Git Hub и делать Fork и Request_

**Команды обмена данными с Git Hub**

1. git clone - _клонирование проекта_

2. git push - _загрузка проекта на облоко или компьютер_

3. git pull - _выкачивание проекта из облока или компьютера_

4. git checkout -b manual - _создание ветки с одновременным на неё переходом_

## **Способы создания репозитория "Test"**

**…or create a new repository on the command line**

echo "# Test" >> README.md

git init

git add README.md

git commit -m "first commit"

git branch -M main

git remote add origin https://github.com/Alexandr-Liza/Test.git

git push -u origin main

**…or push an existing repository from the command line**

git remote add origin https://github.com/Alexandr-Liza/Test.git

git branch -M main

git push -u origin main


