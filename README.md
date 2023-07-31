#Первый комит

##Сделать папку репозиторием — git init
Чтобы Git начал отслеживать изменения в проекте, папку с файлами этого проекта нужно сделать Git-репозиторием (от англ. repository — «хранилище»). Для этого следует переместиться в неё и ввести команду git init (от англ. initialize — «инициализировать»).

##Добавляем файлы в репозиторий
Вы инициализировали Git-репозиторий, но в нём пока ничего нет. В этом уроке разберём, как добавить туда файлы.
Подготовить файлы к сохранению — git add

##Делаем первый коммит
Коммит — это одна из основных сущностей в Git (и в других системах контроля версий). Коммит гарантирует, что изменения будут сохранены в истории и при необходимости к ним можно будет «откатиться». Это как если бы вы могли выполнить операцию Ctrl+Z для целой папки (репозитория).
В этом уроке вы сделаете свой первый коммит.
Выполнить коммит — git commit
Сделать коммит можно командой git commit c ключом -m (от англ. message — «сообщение»), который присваивает коммиту сообщение.

##Просматриваем историю коммитов
В этом уроке разберём, как вывести историю коммитов, — это понадобится для отслеживания того, что происходит в репозитории.
Просмотреть историю коммитов — git log