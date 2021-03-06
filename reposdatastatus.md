## **Получение данных о состоянии репозитория**

---

**git status** Основной инструмент, используемый для определения, какие файлы в каком состоянии находятся — это команда `git status`. Если вы выполните эту команду сразу после клонирования, вы увидите что-то вроде этого:

> *`git status`
<br/>
On branch master
<br/>
Your branch is up-to-date with 'origin/master'.
<br/>
nothing to commit, working tree clean*

Это означает, что у вас чистый рабочий каталог, другими словами — в нем нет отслеживаемых измененных файлов. Git также не обнаружил неотслеживаемых файлов, в противном случае они бы были перечислены здесь. Наконец, команда сообщает вам на какой ветке вы находитесь и сообщает вам, что она не расходится с веткой на сервере..

**git diff** Если результат работы команды `git status` недостаточно информативен для вас — вам хочется знать, что конкретно поменялось, а не только какие файлы были изменены — вы можете использовать команду `git diff`, она показывает вам непосредственно добавленные и удалённые строки — патч как он есть.

[*На главную*](readme.md)