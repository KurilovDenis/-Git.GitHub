Задание по GitHub_1 - github_HW_1

Задание по GitHub_2 - github_HW_2

Задание по GitHub_1

JSON

Создать внешний репозиторий c названием JSON.
New

Create repository

Клонировать репозиторий JSON на локальный компьютер.
git clone git@github.com:AndreiHeranok/JSON.git

Внутри локального JSON создать файл “new.json”. touch new.json

Добавить файл под гит. git add . new.json

Закоммитить файл. git commit -m "add json"

Отправить файл на внешний GitHub репозиторий. git push

Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON.

Вносим изменения: vim new.json

нажать клавишу "i" ввести текст

{
 "FIO": "Heranok Andrei Vladimirovich",
 "age": 29,
 "number of pets": "1",
 "Future desired salary": "500"
}
Cохранить и выйти: "esc" ":wq"

Отправить изменения на внешний репозиторий. git commit -am "add edit json" git push

Создать файл preferences.json touch preferences.json

В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON.

Вносим изменения: vim preferences.json

нажать клавишу "i" ввести текст

{
 "Favorite movie": "The Big Lebowski",
 "Favorite series": "La casa de papel",
 "favorite food": "Potato",
 "favorite time of year": "Summer",
 "country you'd like to visit": "Canada"
}
Cохранить и выйти: "esc" ":wq"

Создать файл skills.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON
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

Отправить сразу 2 файла на внешний репозиторий.
git add .

git commit -m "add skills and preference"

git push

На веб интерфейсе создать файл bug_report.json. -
Add file

- Create new file

- Commit new file

Сделать Commit changes (сохранить) изменения на веб интерфейсе.
-edit this file

в строке Commit changes пишем новый Commit

Commit changes

На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON.
-edit this file

{
	"ID": 1,
        "Version": "Windows 10",
	"Summary": "Не отображаеться предупреждающие окно в приложении при деление на ноль",
	"Req id": "22.3",
	"Steps": "Открыть приложение, Ввести число, Нажать кнопку '/', вссети другое число, нажать кнопку '='",
	"Actual result": "в полле ввода число 0,предупреждающего окна нету",
	"Expected result": "Появляется окно ошибки с текстом,'вы не можете делить на 0'",
	"Severity": "Minor",
	"Priority": "Low",
        "Attachments": "Скриншот"
}
Сделать Commit changes (сохранить) изменения на веб интерфейсе. в строке Commit changes пишем новый Commit Commit changes

Синхронизировать внешний и локальный репозиторий JSON git pull

XML

Создать внешний репозиторий c названием XML.
New

Create repository

Клонировать репозиторий XML на локальный компьютер.
git clone git@github.com:AndreiHeranok/XML.git

Внутри локального XML создать файл “new.xml”. touch new.xml

Добавить файл под гит. git add . new.xml

Закоммитить файл. git commit -m "add xml"

Отправить файл на внешний GitHub репозиторий. git push

Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML.

Вносим изменения: vim new.xml

нажать клавишу "i" ввести текст

<info>
 <FIO>Heranok Andrei Vladimirovich</FIO>
 <AGE>29</AGE>
 <number_of_pets>1</number_of_pets>
 <Future_desired_salary>500</Future_desired_salary>
</info>
Cохранить и выйти: "esc" ":wq"

Отправить изменения на внешний репозиторий.
git commit -am "edit xml"

git push

Создать файл preferences.xml touch preferences.xml

В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате XML.

Вносим изменения: vim preferences.xml

нажать клавишу "i" ввести текст

<Favorite>
 <Favorite_movie>The Big Lebowski</Favorite_movie>
 <Favorite_series>La casa de papel</Favorite_series>
 <favorite_food>Potato</favorite_food>
 <favorite_time_of_year>Summer</favorite_time_of_year>
 <country_you_like_to_visit>Canada</country_you_like_to_visit>
</Favorite>
Cохранить и выйти: "esc" ":wq"

Создать файл skills.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML
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

Сделать коммит в одну строку. git commit -ma "add new xml"

Отправить сразу 2 файла на внешний репозиторий.

git add .

git commit -m "edit new xml"

git push

На веб интерфейсе создать файл bug_report.xml.
- Add file

- Create new file

- Commit new file

Сделать Commit changes (сохранить) изменения на веб интерфейсе.
-edit this file

в строке Commit changes пишем новый Commit

Commit changes

На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML.
<bug>
    <ID>1</ID>,
    <Version>Windows 10</Version>,
    <Summary>Не отображаеться предупреждающие окно в приложении при деление на ноль</Summary>,
    <Req_id>22.3</Req_id>,
    <Steps>ткрыть приложение, Ввести число, Нажать кнопку '/', вссети другое число, нажать кнопку '='</Steps>,
    <Actual_result>в полле ввода число 0,предупреждающего окна нету</Actual_result>,
    <Expected_result>Появляется окно ошибки с текстом,'вы не можете делить на 0'</Expected_result>,
    <Severity>Minor</Severity>,
    <Priority>Low</Priority>,
    <Attachments>screenshot</Attachments>
</bug>
Сделать Commit changes (сохранить) изменения на веб интерфейсе.
в строке Commit changes пишем новый Commit

Commit changes

Синхронизировать внешний и локальный репозиторий XML git pull
TXT

Создать внешний репозиторий c названием TXT.
New

Create repository

Клонировать репозиторий TXT на локальный компьютер.
git clone https://github.com/AndreiHeranok/TXT.git

Внутри локального TXT создать файл “new.txt”. touch new.txt

Добавить файл под гит. git add . new.txt

Закоммитить файл. git commit -m "add txt"

Отправить файл на внешний GitHub репозиторий. git push

Отредактировать содержание файла “new.txt” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате TXT.

Вносим изменения: vim new.txt

нажать клавишу "i" ввести текст

FIO - Heranok Andrei Vladimirovich
AGE - 29
Number of pets - 1
Future desired salary - 500
Cохранить и выйти: "esc" ":wq"

Отправить изменения на внешний репозиторий.
git commit -am "edit txt"

git push

Создать файл preferences.txt touch preferences.txt

В файл preferences.txt” добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате TXT.

Вносим изменения: vim preferences.txt

нажать клавишу "i" ввести текст

Favorite movie - The Big Lebowski,
Favorite series - La casa de papel,
favorite food - Potato,
favorite time of year - Summer,
country you'd like to visit - Canada.
Cохранить и выйти: "esc" ":wq"

Создать файл skills.txt добавить информацию о скиллах которые будут изучены на курсе в формате TXT
Создаём файл: touch skills.txt

Вносим изменения: vim skills.txt нажать клавишу "i" ввести текст

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

Сделать коммит в одну строку. git commit -am "add new txt"

Отправить сразу 2 файла на внешний репозиторий.

git add .

git commit -am "add new txt"

git push

На веб интерфейсе создать файл bug_report.txt.
Add file

- Create new file

- Commit new file

Сделать Commit changes (сохранить) изменения на веб интерфейсе.
-edit this file

в строке Commit changes пишем новый Commit

Commit changes

На веб интерфейсе модифицировать файл bug_report.txt, добавить баг репорт в формате TXT.
 ID - 1,
 Version - Windows 10,
 Summary - Не отображаеться предупреждающие окно в приложении при деление на ноль,
 Req id - 22.3,
 Steps - Открыть приложение, Ввести число, Нажать кнопку '/', вссети другое число, нажать кнопку '=',
 Actual result - в полле ввода число 0,предупреждающего окна нету,
 Expected result - Появляется окно ошибки с текстом,'вы не можете делить на 0',
 Severity - Minor,
 Priority - Low,
 Attachments - Скриншот.
Сделать Commit changes (сохранить) изменения на веб интерфейсе.
edit this file

в строке Commit changes пишем новый Commit

Commit changes

Синхронизировать внешний и локальный репозиторий TXT git pull

