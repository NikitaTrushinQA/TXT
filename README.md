# TXT
GIT Homework 1
1. Создать внешний репозиторий c названием TXT.

Repositories==>New==>Repositoty name:TXT==>Check "Add a README file"==>Press "Create repository"

2. Клонировать репозиторий TXT на локальный компьютер.
 
git clone <HTTPS repository>

 3. Внутри локального TXT создать файл “new.txt”.
 
touch new.txt

 4. Добавить файл под гит.
 
git add new.txt

 5. Закоммитить файл.
 
git commit -m "add txt file"

 6. Отправить файл на внешний GitHub репозиторий.
 
git push

 7. Отредактировать содержание файла “new.txt” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате TXT.
 
cat > new.txt
 
1.full name:Trushin Nikita Andreevich
 
2.age:29
 
3.number of pets:0
 
4.future desired salary:1000$
 
#ctrl+c

 8. Отправить изменения на внешний репозиторий.
 
git add new.txt
git commit -m "add name,age,number of pets,disired salary"
git push

 9. Создать файл preferences.txt
 
touch preferences.txt

 10. В файл preferences.txt” добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате TXT.
 
cat >preferences.txt
 
My preferences:
 
    1)favorite movie:"Saw"
    2)favorite serial:"Ozark"
    3)favorite food:kebab
    4)favorite time of a year:summer
    5)country i want to visit:Japan
#ctrl+c

 11. Создать файл sklls.txt добавить информацию о скиллах которые будут изучены на курсе в формате TXT

cat >skills.txt
 
    1)Базовая теория (Что такое тестирование,документация,техники тест дизайна,виды тестирования и т.д.)
 
    2)Клиент-серверная архитектрура.
 
    3)Статус коды ответов HTTP сервера.
 
    4)HTTP методы запросов на сервер.
 
    5)Структуры HTTP запросов и ответов.
 
    6)Что такое JSON,XML.Их структура.
 
    7)Тестирование API через Postman.
 
    8)Снятие и чтение логов с внешнего сервера.
 
    9)Снифинг http web трафика через Charles и Fiddler.
 
    10)Dev Tools веб браузеров (Google Chrome,FireFox)
 
    11)Мобильное тестирование.
 
    12)Особенность iOS,Android,гайдлайны.
 
    13)Сборка Android приложений на Android Studio.
 
    14)ADB(Управление андройд девайсами).
 
    15)Настройка прокси и vpn на ios и Android.
 
    16)Перехват(сниффинг) мобильного трафика через Charles и Fiddler на ios и android.
 
    17)Командная строка (terminal) Linux(копирование,создание,просмотр,перемещение файлов на серверах без графического интерфейса).
 
    18)Основы bash скриптинг,автоматизация рутинных задач на сервере.
 
    19)Доступ к удалённым серверам.
 
    20)Основы SQL (Create,Delete,Drop,Insert Into,Select,From,Where,Having,Join).
 
    21)База данных Postgres(установка,настройка и использование).
 
    22)Нагрузочное тестирование в Jmeter.
 
    23)Методология разработки Scrum.
 
    24)Python(Основы).


 12. Сделать коммит в одну строку.
 
git add --all && git commit -m "add preferences.txt and skills.txt"

 13. Отправить сразу 2 файла на внешний репозиторий.
 
git push

 14. На веб интерфейсе создать файл bug_report.txt.
 
Add file ==> Create new file ==> Name: bug_report.txt

 15. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
 
 Press "Commit changes"

 16. На веб интерфейсе модифицировать файл bug_report.txt, добавить баг репорт в формате TXT.
 
Choose bug_report.txt --> Edit this file

 17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
 
Press "Commit changes"

 18. Синхронизировать внешний и локальный репозиторий TXT
 
git pull
