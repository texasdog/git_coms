# Git commands

1. git show - позволяет просмотреть, какие именно изменения произошли в указанном коммите.
2. git status - вывод всех изменений и добавленных файлов.
3. git clone [ссылка на репозиторий] - клонирование репозитория.
4. git log - просмотр истории изменений.
5. git rm - удаление файлов из индекса рабочей директории.
6. git blame [название файла] - просмотреть, кто, что и когда изменил в файле.
7. git clean -n — удаление неотслеживаемых файлов в локальной рабочей директории. -n — флаг для пробного запуска, ничего не удаляется. -f — флаг для удаления файлов. -d — флаг для удаления неотслеживаемых директорий. 
8. it branch -d <имя_ветки> - удаление ветки.
9. git revert my_commit — отмена последствий изменений в my_commit. revert выполняет новый коммит после отмены изменений. 
10. git add [filename] [filename] - добавления нескольких файлов по имени. 
11. git checkout -b branch-name создаст ветку с указанным именем и автоматически переключится на неё.
12. git reset, которая отменяет все незафиксированные изменения. По умолчанию, эта команда удаляет только из индекса. 
13. git diff используется для вычисления разницы между любыми двумя Git деревьями.
14. git config —global user.name «Andrew A» git config —global user.email anisimovA@gmail.com - задание имени пользователя и электронной почты для всех проектов.
15. git remote add origin [ссылка на репозиторий] - связывание локального и удалённого репозитория
