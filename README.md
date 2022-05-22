1.Задание по GitHub_1.    
2.Задание по GitHub_2.
-------------------------------------------------------------------------------------------------------------------------------------------------------
-------------------------------------------------------------------------------------------------------------------------------------------------------
Задание по GitHub_1.

JSON
 4. Создать внешний репозиторий c названием JSON.      New
                                                       Create repository

 5. Клонировать репозиторий JSON на локальный компьютер.   git clone https://github.com/KurilovDenis/-json.git

 6. Внутри локального JSON создать файл “new.json”.        touch  new.json

 7. Добавить файл под гит.          git add . new.json

 8. Закоммитить файл.               git commit -m "add json"

 9. Отправить файл на внешний GitHub репозиторий.  git push

 10. Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON.
 
Вносим изменения: vim new.json
нажать клавишу "i" ввести текст

{
     "FIO":"Kurilov Denis Aleksandrovich",
     "number of pets": "1",
     "Age": 29,
     "Future desired salary":"700"
}

Cохранить и выйти: "esc" ":wq"

 11. Отправить изменения на внешний репозиторий.  git commit -am "add edit json"
                                                  git push

 12. Создать файл preferences.json    touch preferences.json

 13. В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON.

Вносим изменения: vim preferences.json
нажать клавишу "i" ввести текст

{
 "Favorite movie": "Inception",
 "Favorite series": "The queen gambit",
 "favorite food": "Steak",
 "favorite time of year": "Summer",
 "country you'd like to visit": "USA"
}

Cохранить и выйти: "esc" ":wq"

 14. Создать файл skills.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON

Создаём файл: touch skills.json
Вносим изменения: vim skills.json
нажать клавишу "i" ввести текст

{
    "Базовая теория": "Что такое тестирование, багрепорты, документация, виды, методы, направления тестирования, SDLC, STLC.",
    "клиент-сервер": "клиент-серверная архитектура",
    "Методы запросов на сервер": "HTTP",
    "Коды ответов": "HTTP сервера",
    "Структуры": "HTTP запросов и ответов",
    "Структура": "JSON, XML",
    "Тестирование API": "через Postman (JS, автотесты API)",
    "Снятие и чтение логов": "c внешнего сервера",
    "Снифинг": " http web трафика через Charles и Fiddler",
    "Dev Tools веб браузеров": "Google Chrome, FireFox",
    "VPN": "Как работает, зачем нужен, как использовать, варианты инструментов",
    "тестирование": "Мобильное",
    "гайдлайны": "Особенность iOS, Android",
    "Сборка": "iOS приложений на XCode.",
    "Сборка": "Androidприложений на Android Studio.",
    "ADB": "управление андройд девайсами",
    "Настройка": " прокси и vpn на iOS и Android",
    "Перехват (сниффинг) мобильного трафика": "через Charles и Fiddler на iOS и Android",
    "Командная строка (terminal) Linux": "копирование, создание, просмотр, перемещение файлов на серверах без графического интерфейса",
    "Основы bash скриптинг": "автоматизация рутинных задач на сервере",
    "Доступ": "к удалённым серверам",
    "Основы SQL": "Create, Delete, Drop, Insert Into, Select, From, Where, Join",
    "База данных": "Postgres, установка, настройка и использование",
    "Нереляционная база данных": " Redis установка, настройка и использование",
    "Нагрузочное тестирование": "в Jmeter",
    "Методология разработки": "Scrum",
    "Python": "Изучение основ. Создание клиент серверного приложения"
}

Cохранить и выйти: "esc" ":wq"

 15. Отправить сразу 2 файла на внешний репозиторий.   git add .
                                                       git commit -m "add skills and preference"
                                                       git push

 16. На веб интерфейсе создать файл bug_report.json.        - Add file
							    - Create new file
							    - Commit new file
 
17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.  -edit this file
                                                                     в строке Commit changes пишем новый Commit
                                                                     Commit changes

 18. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON.

-edit this file

{
	"ID": 1,
        "Version": "macOS Monterey calculator",
	"Summary": "Не отображаеться предупреждающие окно в приложении при деление на ноль",
	"Req id": "2",
	"Steps": "Открыть приложение, Ввести число, Нажать кнопку '/', ввести другое число, нажать кнопку '='",
	"Actual result": "в поле ввода число 0,нет предупреждения 'Деление на ноль запрещено' ",
	"Expected result": "Появляется окно ошибки с текстом,'Деление на ноль запрещено'",
	"Severity": "Minor",
	"Priority": "Low",
        "Attachments": "Скриншот"
}

19. Сделать Commit changes (сохранить) изменения на веб интерфейсе.    в строке Commit changes пишем новый Commit
                                                                       Commit changes

20. Синхронизировать внешний и локальный репозиторий JSON       git pull


XML

 21. Создать внешний репозиторий c названием XML.     New
                                                      Create repository

 22. Клонировать репозиторий XML на локальный компьютер.   git clone https://github.com/KurilovDenis/xml.git

 23. Внутри локального XML создать файл “new.xml”.  touch new.xml

 24. Добавить файл под гит.    git add . new.xml
 25. Закоммитить файл.       git commit -m "add xml"

 26. Отправить файл на внешний GitHub репозиторий.  git push
 
 27. Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML.

Вносим изменения: vim new.xml
нажать клавишу "i" ввести текст

<info>
<FIO>Kurilov Denis Aleksandrovich</FIO>
<AGE>29</AGE>
 <number_of_pets>1</number_of_pets>
 <Future_desired_salary>700</Future_desired_salary>
</info>

Cохранить и выйти: "esc" ":wq"

28. Отправить изменения на внешний репозиторий.   git commit -am "edit xml"
                                                  git push
 
29. Создать файл preferences.xml       touch preferences.xml

30. В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате XML.
  
Вносим изменения: vim preferences.xml
нажать клавишу "i" ввести текст

<Favorite>
 <Favorite_movie>Inception</Favorite_movie>
 <Favorite_series>The queen gambit</Favorite_series>
 <favorite_food>Steak</favorite_food>
 <favorite_time_of_year>Summer</favorite_time_of_year>
 <country_you_like_to_visit>USA</country_you_like_to_visit>
</Favorite>

Cохранить и выйти: "esc" ":wq"

 31. Создать файл skills.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML 

Создаём файл: touch skills.xml
Вносим изменения: vim skills.xml
нажать клавишу "i" ввести текст

<skills>
    <Базовая_теория>Что такое тестирование, багрепорты, документация, виды, методы, направления тестирования, SDLC, STLC</Базовая_теория>,
    <клиент_сервер>клиент-серверная архитектура</клиент_сервер>,
    <Методы_запросов_на_сервер>HTTP<Методы_запросов_на_сервер>,
    <Коды_ответов>HTTP сервера</Коды_ответов>,
    <Структуры>HTTP запросов и ответов</Структуры>,
    <Структура>JSON, XML</Структуры>,
    <Тестирование_API>через Postman (JS, автотесты API)</Тестирование_API>,
    <Снятие_и_чтение_логов>c внешнего сервера</Снятие_и_чтение_логов>,
    <Снифинг>http web трафика через Charles и Fiddler</Снифинг>,
    <Dev_Tools_веб_браузеров>Google Chrome, FireFox</Dev_Tools_веб_браузеров>,
    <VPN>Как работает, зачем нужен, как использовать, варианты инструментов</VPN>,
    <тестирование>Мобильное</тестирование>,
    <гайдлайны>Особенность iOS, Android</гайдлайны>,
    <Сборка>iOS приложений на XCode</Сборка>,
    <Сборка>Androidприложений на Android Studio</Сборка>,
    <ADB>управление андройд девайсами</ADB>,
    <Настройка>прокси и vpn на iOS и Android</Настройка>,
    <Перехват_(сниффинг)_мобильного_трафика>через Charles и Fiddler на iOS и Android</Перехват_(сниффинг)_мобильного_трафика>,
    <Командная_строка_(terminal)_Linux>копирование, создание, просмотр, перемещение файлов на серверах без графического интерфейса</Командная_строка_(terminal)_Linux>,
    <Основы_bash_скриптинг>автоматизация рутинных задач на сервере</Основы_bash_скриптинг>,
    <Доступ>к удалённым серверам</Доступ>,
    <Основы_SQL>Create, Delete, Drop, Insert Into, Select, From, Where, Join</Основы_SQL>,
    <База_данных>Postgres, установка, настройка и использование</База_данных>,
    <Нереляционная_база_данных>Redis установка, настройка и использование</Нереляционная_база_данных>,
    <Нагрузочное_тестирование>Jmeter</Нагрузочное_тестирование>,
    <Методология_разработки>Scrum</Методология_разработки>,
    <Python>Изучение основ. Создание клиент серверного приложения</Python>
</skills>

Cохранить и выйти: "esc" ":wq"

 32. Сделать коммит в одну строку.                   git commit -ma "add new xml"

 33. Отправить сразу 2 файла на внешний репозиторий.
                                                     git add . 
                                                     git commit -m "edit new xml"
                                                     git push

 34. На веб интерфейсе создать файл bug_report.xml.  - Add file
							    - Create new file
							    - Commit new file
 35. Сделать Commit changes (сохранить) изменения на веб интерфейсе. -edit this file
                                                                     в строке Commit changes пишем новый Commit
                                                                     Commit changes

 36. На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML.

<bug>
    <ID>1</ID>,
    <Version>MacOS Monterey calculator</Version>,
    <Summary>Не отображаеться предупреждающие окно в приложении при деление на ноль</Summary>,
    <Req_id>2</Req_id>,
    <Steps>ткрыть приложение, Ввести число, Нажать кнопку '/', вссети другое число, нажать кнопку '='</Steps>,
    <Actual_result>в полле ввода число 0,нет предупредения  'Деление на ноль запрещено'</Actual_result>,
    <Expected_result>Появляется окно ошибки с текстом,'Деление на ноль запрещено'</Expected_result>,
    <Severity>Minor</Severity>,
    <Priority>Low</Priority>,
    <Attachments>screenshot</Attachments>
</bug>

 37. Сделать Commit changes (сохранить) изменения на веб интерфейсе.    в строке Commit changes пишем новый Commit
                                                                     Commit changes
 38. Синхронизировать внешний и локальный репозиторий XML   git pull

TXT
 1. Создать внешний репозиторий c названием TXT.       New
                                                       Create repository

 2. Клонировать репозиторий TXT на локальный компьютер.     git clone https://github.com/KurilovDenis/txt.git

 3. Внутри локального TXT создать файл “new.txt”.      touch new.txt

 4. Добавить файл под гит.     git add . new.txt
       
 5. Закоммитить файл.         git commit -m "add txt"

 6. Отправить файл на внешний GitHub репозиторий.     git push

 7. Отредактировать содержание файла “new.txt” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате TXT.
 
Вносим изменения: vim new.txt 
нажать клавишу "i" ввести текст

FIO - Kurilov Denis Aleksandrovich
AGE - 29
Number of pets - 1
Future desired salary - 700

Cохранить и выйти: "esc" ":wq"

8. Отправить изменения на внешний репозиторий.   git commit -am "edit txt"
                                                 git push

 9. Создать файл preferences.txt          touch preferences.txt

 10. В файл preferences.txt” добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате TXT.

Вносим изменения: vim preferences.txt
нажать клавишу "i" ввести текст

Favorite movie - Inception,
Favorite series - The queen gambit,
favorite food - Steak,
favorite time of year - Summer,
country you'd like to visit - USA.

Cохранить и выйти: "esc" ":wq"

 11. Создать файл skills.txt добавить информацию о скиллах которые будут изучены на курсе в формате TXT

Создаём файл: touch skills.txt
Вносим изменения vim skills.txt
нажать клавишу "i" ввести текст

Базовая теория (Что такое тестирование, багрепорты, документация, виды, методы, направления тестирования и т.п.) SDLC, STLC.
Что такое клиент-серверная архитектура.
HTTP Методы запросов на сервер.
Коды ответов HTTP сервера.
Структуры HTTP запросов и ответов.
Что такое JSON, XML. Их структура.
Тестирование API через Postman (JS, автотесты API).
Снятие и чтение логов c внешнего сервера.
Снифинг http web трафика через Charles и Fiddler.
Dev Tools веб браузеров (Google Chrome, FireFox).
VPN. (Как работает, зачем нужен, как использовать, варианты инструментов)
Мобильное тестирование.
Особенность iOS, Android, гайдлайны.
Сборка iOS приложений на XCode. (У кого нет Mac компьютера, просто посмотрят)
Сборка Android приложений на Android Studio.
ADB (управление андройд девайсами).
Настройка прокси и vpn на iOS и Android.
Перехват (сниффинг) мобильного трафика через Charles и Fiddler на iOS и Android.
Командная строка (terminal) Linux (копирование, создание, просмотр, перемещение файлов на серверах без графического интерфейса)
Основы bash скриптинг, автоматизация рутинных задач на сервере.
Доступ к удалённым серверам.
Основы SQL (Create, Delete, Drop, Insert Into, Select, From, Where, Join).
База данных Postgres (установка, настройка и использование).
Нереляционная база данных Redis (установка, настройка и использование).
Нагрузочное тестирование в Jmeter.
Методология разработки Scrum.
Python. (Изучение основ. Создание клиент серверного приложения)

Cохранить и выйти: "esc" ":wq"

 12. Сделать коммит в одну строку.              git commit -am "add new txt"
 
13. Отправить сразу 2 файла на внешний репозиторий.        git add . 
                                                            git commit -am "add new txt"
                                                            git push
              
 14. На веб интерфейсе создать файл bug_report.txt.       Add file
							    - Create new file
							    - Commit new file
  
 15. Сделать Commit changes (сохранить) изменения на веб интерфейсе.   -edit this file
                                                                       в строке Commit changes пишем новый Commit
                                                                       Commit changes
 
 16. На веб интерфейсе модифицировать файл bug_report.txt, добавить баг репорт в формате TXT.
 
 ID - 1,
 Version - MacOS Monterey calculator,
 Summary - Не отображаеться предупреждающие окно в приложении при деление на ноль,
 Req id - 2,
 Steps - Открыть приложение, Ввести число, Нажать кнопку '/', ввести другое число, нажать кнопку '=',
 Actual result - в полле ввода число 0,нет предупреждения делить на 0 запрещено,
 Expected result - Появляется окно ошибки с текстом,'делить на 0 запрещено,
 Severity - Minor,
 Priority - Low,
 Attachments - Скриншот.

 17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.    edit this file
                                                                        в строке Commit changes пишем новый Commit
                                                                        Commit changes 
 
 18. Синхронизировать внешний и локальный репозиторий TXT       git pull

-------------------------------------------------------------------------------------------------------------------------------------------------------	    
Задание по GitHub_2

1. На локальном репозитории сделать ветки для:

- Postman      git branch Postman
- Jmeter        git branch Jmeter
- CheckLists      git branch CheckLists
- Bug Reports    git branch  Bug_Reports
- SQL          git branch  SQL
- Charles     git branch  Charles
- Mobile testing       git branch Mobile_testing                   
 
2. Запушить все ветки на внешний репозиторий     git push -u origin Postman Jmeter CheckLists Bug_Reports SQL Charles Mobile_testing  

3. В ветке Bag Reports сделать текстовый документ со структурой баг репорта  


Меняем ветку:   git checkout Bug_Reports

Создаём файл: touch Bug_reports.txt
Вносим изменения: vim Bug_reports.txt
нажать "i" вводим текст

"ID"
"Title(краткое описание)"    основной
"Description(Подробное описание)"
"Req id(id требованияя)"
"Steps To Rreproduce(шаги)"      основной
"Actual Results(фактический результат)"    основной
"Expected Results(ожидаемый результат)"    основной
"Severity(важность)"
"Priority(срочность)"
"Attachments(приложение,скриншот,видео,лог)"
"Workaround(возможность обойти баг)"
"Status"

Cохранить и выйти: "esc" ":wq"


4. Запушить структуру багрепорта на внешний репозиторий

git add . Bug_reports.txt
git commit -m "add bug_reports"
git push


5. Вмержить ветку Bag Reports в Main  

git checkout main
git merge Bug_Reports

6. Запушить main на внешний репозиторий.

git push -u origin main

7. В ветке CheckLists набросать структуру чек листа.

Меняем ветку: git checkout CheckLists
Создаём файл: touch CheckLists.txt
Вносим изменения: vim CheckLists.txt
нажать "i" вводить текст

ID 
Priority(приоретет)	
Req(ссылка на требование) 
Module(модуль) 
Title(название) 
Test steps(шаги) 
Expected Result(ожидаемый) 
Status 
Bug

Cохранить и выйти: "esc" ":wq"

8. Запушить структуру на внешний репозиторий 

git add CheckLists.txt
git commit -m "add CheckLists"
git push

9. На внешнем репозитории сделать Pull Request ветки CheckLists в main   

  На web-интерфейсе перейти в ветку Check-Lists 
  Нажать Compare & pull request - Сreate pull request

10. Синхронизировать Внешнюю и Локальную ветки Main    

git checkout main
git pull
