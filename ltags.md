## **Легковесные теги**

Легковесный тег — это ещё один способ пометить коммит. По сути, это контрольная сумма коммита, сохранённая в файл — больше никакой информации не хранится. Для создания легковесного тега не передавайте опций *-a*, *-s* и *-m*, укажите только название при помощи команды `git tag <commit version> <tagname>`:

>`*git tag v1.4`
<br/>
git tag
<br/>
v0.1
<br/>
v1.3
<br/>
v1.4
<br/>
v1.4-lw
<br/>
v1.5*

На этот раз при выполнении `git show` для этого тега вы не увидите дополнительной информации. Команда просто покажет коммит:

>`*git show v1.4-lw`
<br/>
commit ca82a6dff817ec66f44342007202690a93763949
<br/>
Author: Scott Chacon <schacon@gee-mail.com>
<br/>
Date:   Mon Mar 17 21:52:11 2008 -0700
<br/>
Change version number*

[*Назад*](tags.md)

[*К оглавлению*](readme.md)