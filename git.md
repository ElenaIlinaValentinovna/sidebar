Навигация по терминалу (терминалы git bush, ZSH) ** ls -- посмотреть список файлов в текущей директории ** ls -а -- посмотреть список файлов + скрытые файлы ** cd .. -- перейти на папку выше ** cd (имя папки) -- перейти в папку ** mkdir (имя папки) -- создать папку ** rm -rf (имя папки) -- удалить папку и все файлы в ней ** pwd -- посмотреть путь к текущей папке
** git init -- инициализирует пустой репозиторий(не git) ** git status -- проверить измененные файлы

Отправить код на github ** git add . -- добавить файлы в будущий комит ** git commit -m "first commit" -- создать коммит ** git push origin master -- отправить код на github
--> Перейти на сайт -> Создать пустой репозиторий на github.com (git push сработает)

Взять код с github --> сначала нужно зделать ** git init (инициализировать гит репозиторий) ** git pull {url(нужно скопировать ссылку с github.com)}

Удалить git init из папки --> перейти в папку с консоли(свериться командой pwd, ls) ** rm -rf .git -- удалить инициализацию гит из папки