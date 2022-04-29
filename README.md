# Homework GitHub_XML 
1. Создать внешний репозиторий c названием XML.
 
2. Клонировать репозиторий XML на локальный компьютер.
git clone и вставляем ссылку скопированую во внешнем репозитории
 
3. Внутри локального XML создать файл “new.xml”.
cd .. выходим из репозитория JSON на католог выше 
cd XML 
touch new.xml
 
4. Добавить файл под гит.
git add new.xml 
 
5. Закоммитить файл.
git commit -m "add file.xml"
 
6. Отправить файл на внешний GitHub репозиторий.
git push
 
7. Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML.

После внесения изменений нажимаем "ESC" для выхода в "командный режим", вводим ":" (двоеточие), вводим "wq" (write-quit) - для сохранения изменений и выхода; "q!" - для выхода без сохранения, и нажимаем "Enter".
Если измения вносились через Notepad нажимаем крестик и ок 

8. Отправить изменения на внешний репозиторий.
git add .

9. Создать файл preferences.xml
touch файл preferences.xml
 
10. В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате XML.

vim preferences.xml

11. Создать файл sklls.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML
touch skills.xml
vim skills.xml
 
12. Сделать коммит в одну строку.
git commit -am "add file skills and preferencec"
 
13. Отправить сразу 2 файла на внешний репозиторий.
git push preferencec.txt skills.txt
 
14. На веб интерфейсе создать файл bug_report.xml.
Заходим в репозиторий XML на против кнопки с выбором веток main нажимаем на кнопку с 3-мя вертикальными точками 
в выпавшем меню выбираем create new file 
присваеваем имя файлу bag_report 

15. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
скролим в низ нажимаем кнопку Commit new file

16. На wвеб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML.

17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
скролим в низ нажимаем кнопку Commit changes

18. Синхронизировать внешний и локальный репозиторий XML
git pull
