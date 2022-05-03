# TXT
1. Создать внешний репозиторий c названием TXT.
2. Клонировать репозиторий TXT на локальный компьютер __git clone git@github.com:libre-afk/TXT.git__
3. Внутри локального TXT создать файл “new.txt” __touch new.txt__ 
4. Добавить файл под гит __git add new.txt__ 
5. Закоммитить файл __git commit new.txt -m "added file new.txt"__
6. Отправить файл на внешний GitHub репозиторий __git push__
7. Отредактировать содержание файла “new.txt” - написать информацию о себеа)  __vim new.txt__
8. Отправить изменения на внешний репозиторий __git add new.txt && git commit -am "Updated new.txt" && git push__
9. Создать файл preferences.txt __touch prefences.txt__
10. В файл preferences.txt” добавить информацию о своих предпочтениях в формате TXT __vim prefences.txt__
11. Создать файл sklls.txt добавить информацию о скиллах которые будут изучены на курсе в формате TXT __cat > skills.txt__
12. Сделать коммит в одну строку __git add . && git commit -am "comment"__
13. Отправить сразу 2 файла на внешний репозиторий __git push__
14. На веб интерфейсе создать файл bug_report.txt.
В веб-интерфейсе выбираем Add file, создаем его. Файл добавляется в репозиторий
15. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
Сохраняем изменения кнопкой commit changes
16. На веб интерфейсе модифицировать файл bug_report.txt, добавить баг репорт в формате TXT.
Редактируем файл bug_report.txt нажав на него ЛКМ и выбрав edit this file
17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
Сохраняем изменения кнопкой commit changes
18. Синхронизировать внешний и локальный репозиторий TXT __git pull__
