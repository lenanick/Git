JSON 4. Создать внешний репозиторий c названием JSON

```
1. Зайти на сайт https://github.com/
2. Авторизоваться
3. Нажать раздел "Repositories"
4. Нажать кнопку "New"
5. В поле "Repository name" написать JSON
6. Нажать "Create repository"
```

5. Клонировать репозиторий JSON на локальный компьютер.

```bash
git clone https://github.com/lenanick/JSON.git
```

6. Внутри локального JSON создать файл “new.json”.

```bash
cd JSON
touch new.json
```

7. Добавить файл под гит.

```bash
git add new.json
```

8. Закоммитить файл.

```bash
git commit -m "add new file"
```

9. Отправить файл на внешний GitHub репозиторий.

```bash
git push
```

10. Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON.

```bash
vim new.json
Press the button "i"

{
 "Name":"Elena",
 "Age":"38",
 "Pets":"0",
 "Salary":"500$"
}
Esc
:wq
```

11. Отправить изменения на внешний репозиторий.

```bash
git commit -am "Edit file new.json"
git push
```

12. Создать файл preferences.json

```bash
touch preferences.json
```

13. В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, страну которую хотели бы посетить) в формате JSON.

```bash
vim preferences.json
Press the button "i"

{  "Favorite film":   "The girls",
   "Favorite serial": "No",
   "Favorite food":   "Vareniks" ,
   "Favorite season": "Spring" ,
   "Favorite coutry": "Holland"
}
Esc
:wq
```

14. Создать файл sklls.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON

```bash
touch skills.json
vim skills.json
Press the button "i"
{
"1.": "Базовая теория (Что такое тестирование, багрепорты, документация, виды, методы, направления тестирования и т.п.) SDLC, STLC",
"2.": "Что такое клиент-серверная архитектура",
"3.": "HTTP Методы запросов на сервер",
"4.": "Коды ответов HTTP сервера",
"5.": "Структуры HTTP запросов и ответов",
"6.": "Что такое JSON, XML. Их структура",
"7.": "Тестирование API через Postman (JS, автотесты API)",
"8.": "Снятие и чтение логов c внешнего сервера",
"9.": "Снифинг http web трафика через Charles и Fiddler",
"10.": "Dev Tools веб браузеров (Google Chrome, FireFox)",
"11.": "VPN. (Как работает, зачем нужен, как использовать, варианты инструментов)",
"12.": "Мобильное тестирование",
"13.": "Особенность iOS, Android, гайдлайны",
"14.": "Сборка iOS приложений на XCode. (У кого нет Mac компьютера, просто посмотрят)",
"15.": "Сборка Android приложений на Android Studio",
"16.": "ADB (управление андройд девайсами)",
"17.": "Настройка прокси и vpn на iOS и Android",
"18.": "Перехват (сниффинг) мобильного трафика через Charles и Fiddler на iOS и Android",
"19.": "Командная строка (terminal) Linux (копирование, создание, просмотр, перемещение файлов на серверах без графического интерфейса)",
"20.": "Основы bash скриптинг, автоматизация рутинных задач на сервере",
"21.": "Доступ к удалённым серверам",
"22.": "Основы SQL (Create, Delete, Drop, Insert Into, Select, From, Where, Join)",
"23.": "База данных Postgres (установка, настройка и использование)",
"24.": "Нереляционная база данных Redis (установка, настройка и использование)",
"25.": "Нагрузочное тестирование в Jmeter",
"26.": "Методология разработки Scrum",
"27.": "Python. (Изучение основ. Создание клиент серверного приложения)"
}
Esc
:wq

```

15. Отправить сразу 2 файла на внешний репозиторий.

```bash
git add skills.json preferences.json
git commit -m "add new files preferences.json skills.json"
git push

```

16. На веб интерфейсе создать файл bug_report.json.
17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.

```bash
Зайти на сайт github
Открыть репозиторий JSON
Нажать на кнопку Add file
Выбрать в меню Create new file
В поле name написать bug_report.json
В поле Commit new file написать Create bug_report.json
Нажать на кнопку Commit new file

```

18. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON.
19. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
    Нажать иконку "Карандаш"

```bash
{
   "ID": 1,
   "Title": "Краш приложения при отмене подтверждения входа" ,
   "Precondition": "Профиль авторизован в мобильном приложении",
   "STR": {
    "1.": "Открыть десктопное приложение winapp",
    "2.": "Авторизоваться под тем же аккаунтом, что и на мобильном устройстве",
    "3.": "Отклонить код-картинку на мобильном устройстве, нажать Decline",
    "4.": "Выбрать причину отмены ",
    "5.":" Нажать Send"
   }
   "Expected result": "Приложение продолжает работу" ,
   "Actual result":   "Приложение крашится",
   "Severity": "Hight",
   "Environment":"ZTE Blade A7",
   "Attachments":
   "Reproducibility":"Usually"
}

В поле Commit changes написать Update bug_report.json
Нажать на кнопку Commit changes
```

20. Синхронизировать внешний и локальный репозиторий JSON

```bash
git pull
```

XML 21. Создать внешний репозиторий c названием XML.

```
1. Зайти на сайт https://github.com/
2. Авторизоваться
3. Нажать раздел "Repositories"
4. Нажать кнопку New
5. В поле "Repository name" написать XML
6. Нажать "Create repository"
```

22. Клонировать репозиторий XML на локальный компьютер.

```bash
git clone https://github.com/lenanick/XML.git
```

23. Внутри локального XML создать файл “new.xml”.

```bash
cd XML
touch new.xml
```

24. Добавить файл под гит.

```bash
git add new.xml
```

25. Закоммитить файл.

```bash
git commit -m "add new file new.xml"
```

26. Отправить файл на внешний GitHub репозиторий.

```bash
git push
```

27. Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML.

```xml
vim new.xml
Press the button "i"

<name>Elena</name>
<age>38</age>
<pets>0</pets>
<salary>500$</salary>

Esc
:wq
```

28. Отправить изменения на внешний репозиторий.

```bash
git add
git commit -m "add new file new.xml"
git push
```

29. Создать файл preferences.xml

```bash
touch preferences.xml
```

30. В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате XML.

```xml
 vim preferences.xml
 Press button "i"

<Favorite_film> The girls </Favorite_film>
<Favorite_serial> No </Favorite_serial>
<Favorite_food> Vareniks </Favorite_food>
<Favorite_season> Spring </Favorite_season>
<Favorite_coutry> Holland </Favorite_coutry>

Esc
:wq
```

31. Создать файл sklls.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML

```bash
 touch skills.xml
 vim skills.xml
 Press buttion "i"
 <skills>
   <item_1>Базовая теория (Что такое тестирование, багрепорты, документация, виды, методы, направления тестирования и т.п.) SDLC, STLC> </item_1>
   <item_2>Что такое клиент-серверная архитектура</item_2>
   <item_3>HTTP Методы запросов на сервер</item_3>
   <item_4>Коды ответов HTTP сервера</item_4>
   <item_5>Структуры HTTP запросов и ответов</item_5>
   <item_6>Что такое JSON, XML. Их структура</item_6>
   <item_7>Тестирование API через Postman (JS, автотесты API)</item_7>
   <item_8>Снятие и чтение логов c внешнего сервера</item_8>
   <item_9>Снифинг http web трафика через Charles и Fiddler</item_9>
   <item_10>Dev Tools веб браузеров (Google Chrome, FireFox)</item_10>
   <item_11>VPN. (Как работает, зачем нужен, как использовать, варианты инструментов)</item_11>
   <item_12>Мобильное тестирование</item_12>
   <item_13>Особенность iOS, Android, гайдлайны</item_13>
   <item_14>Сборка iOS приложений на XCode. (У кого нет Mac компьютера, просто посмотрят)</item_14>
   <item_15>Сборка Android приложений на Android Studio</item_15>
   <item_16>ADB (управление андройд девайсами)</item_16>
   <item_17>Настройка прокси и vpn на iOS и Android</item_17>
   <item_18>Перехват (сниффинг) мобильного трафика через Charles и Fiddler на iOS и Android</item_18>
   <item_19>Командная строка (terminal) Linux (копирование, создание, просмотр, перемещение файлов на серверах без графического интерфейса)</item_19>
   <item_20>Основы bash скриптинг, автоматизация рутинных задач на сервере</item_20>
   <item_21>Доступ к удалённым серверам</item_21>
   <item_22>Основы SQL (Create, Delete, Drop, Insert Into, Select, From, Where, Join)</item_22>
   <item_23>База данных Postgres (установка, настройка и использование)</item_23>
   <item_24>Нереляционная база данных Redis (установка, настройка и использование)</item_24>
   <item_25>Нагрузочное тестирование в Jmeter</item_25>
   <item_26>Методология разработки Scrum</item_26>
   <item_27>Python. (Изучение основ. Создание клиент серверного приложения)</item_27>
 </skills>

Esc
:wq
```

32. Сделать коммит в одну строку.

```bash
git add . && git commit -m "add 2 new XML files"
```

33. Отправить сразу 2 файла на внешний репозиторий.

```bash
git push
```

34. На веб интерфейсе создать файл bug_report.xml.
35. Сделать Commit changes (сохранить) изменения на веб интерфейсе.

```bash
    Зайти на сайт github
    Открыть репозиторий XML
    Нажать на кнопку Add file
    Выбрать в меню Create new file
    В поле name написать bug_report.xml
    В поле Commit new file написать Create bug_report.xml
    Нажать на кнопку Commit new file
```

36. На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML.
37. Сделать Commit changes (сохранить) изменения на веб интерфейсе.

```xml

 Нажать иконку "Карандаш"
 <Bug_report>

  <ID> 1 </ID>
  <Title> Краш приложения при отмене подтверждения входа </Title>
  <Precondition> Профиль авторизован в мобильном приложении </Precondition>
  <STR>
          <1> Открыть десктопное приложение winapp </1>
          <2> Авторизоваться под тем же аккаунтом, что и на мобильном устройстве </2>
          <3> Отклонить код-картинку на мобильном устройстве, нажать ""Decline"</3>
          <4> Выбрать причину отмены ""The code/picture doesn't matchv </4>
          <5> Нажать Send"</5>
  </STR>
  <Expected result> Приложение продолжает работу </Expected result>
  <Actual_result> Приложение крашится </Actual_result>
  <Severity> Hight </Severity>
  <Environment> ZTE blade A7 </Enviroment>
  <Reproducibility> Usually </Reproducibility>
  <Attachments></Attachments>
  </Bug_report>

 В поле Commit changes написать Update bug_report.xml
 Нажать на кнопку Commit changes

```

38. Синхронизировать внешний и локальный репозиторий XML

```bash
    git pull
```

TXT

1. Создать внешний репозиторий c названием TXT.

```
1. Зайти на сайт https://github.com/
2. Авторизоваться
3. Нажать раздел "Repositories"
4. Нажать кнопку New
5. В поле "Repository name" написать TXT
6. Нажать "Create repository"

```

2. Клонировать репозиторий TXT на локальный компьютер.

```bash
git clone https://github.com/lenanick/TXT.git

```

3. Внутри локального TXT создать файл “new.txt”.

```bash
cd TXT
touch new.txt
```

4. Добавить файл под гит.

```bash
git add new.txt
```

5. Закоммитить файл.

```bash
git commit -m "add new file new.txt"
```

6. Отправить файл на внешний GitHub репозиторий.

```bash
git push
```

7. Отредактировать содержание файла “new.txt” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате TXT.

```bash
vim new.txt
Push the button "i"

name:Elena,
age:38,
Pets:0,
salary:500$.

Esc
:wq
```

8. Отправить изменения на внешний репозиторий.

```bash
git add new.txt | git commit -m "update file new.txt"
git push
```

9. Создать файл preferences.txt

```bash
touch preferences.txt
```

10. В файл preferences.txt” добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате TXT.

```bash
vim preferences.txt
Press button "i"

Favorite film: "The girls"
Favorite serial: No
Favorite food: Vareniks
Favorite season: Spring
Favorite coutry: Holland

Esc
:wq
```

11. Создать файл sklls.txt добавить информацию о скиллах которые будут изучены на курсе в формате TXT

```bash
touch skills.txt
vim skills.txt
Push button "i"

1. Базовая теория (Что такое тестирование, багрепорты, документация, виды, методы, направления тестирования и т.п.) SDLC, STLC.
2. Что такое клиент-серверная архитектура.
3. HTTP Методы запросов на сервер.
4. Коды ответов HTTP сервера.
5. Структуры HTTP запросов и ответов.
6. Что такое JSON, XML. Их структура.
7. Тестирование API через Postman (JS, автотесты API).
8. Снятие и чтение логов c внешнего сервера.
9. Снифинг http web трафика через Charles и Fiddler.
10. Dev Tools веб браузеров (Google Chrome, FireFox).
11. VPN. (Как работает, зачем нужен, как использовать, варианты инструментов)
12. Мобильное тестирование.
13. Особенность iOS, Android, гайдлайны.
14. Сборка iOS приложений на XCode. (У кого нет Mac компьютера, просто посмотрят)
15. Сборка Android приложений на Android Studio.
16. ADB (управление андройд девайсами).
17. Настройка прокси и vpn на iOS и Android.
18. Перехват (сниффинг) мобильного трафика через Charles и Fiddler на iOS и Android.
19. Командная строка (terminal) Linux (копирование, создание, просмотр, перемещение файлов на серверах без графического интерфейса)
20. Основы bash скриптинг, автоматизация рутинных задач на сервере.
21. Доступ к удалённым серверам.
22. Основы SQL (Create, Delete, Drop, Insert Into, Select, From, Where, Join).
23. База данных Postgres (установка, настройка и использование).
24. Нереляционная база данных Redis (установка, настройка и использование).
25. Нагрузочное тестирование в Jmeter.
26. Методология разработки Scrum.
27. Python. (Изучение основ. Создание клиент серверного приложения)

Esc
:wq
```

12. Сделать коммит в одну строку.

```bash
 git add . | git commit -am "add 2 files preferences.txt skills.txt"
```

13. Отправить сразу 2 файла на внешний репозиторий.

```bash
 git push
```

14. На веб интерфейсе создать файл bug_report.txt.
15. Сделать Commit changes (сохранить) изменения на веб интерфейсе.

```
Зайти на сайт github
Открыть репозиторий TXT
Нажать на кнопку Add file
Выбрать в меню Create new file
В поле name написать bug_report.txt
В поле Commit new file написать Create bug_report.txt
Нажать на кнопку Commit new file
```

16. На веб интерфейсе модифицировать файл bug_report.txt, добавить баг репорт в формате TXT.
17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
    Нажать иконку "Карандаш"

```
  ID: 1
  Title: "Краш приложения при отмене подтверждения входа"
  Precondition: "Профиль авторизован в мобильном приложении"
  STR:
      1. Открыть десктопное приложение winapp,
      2. Авторизоваться под тем же аккаунтом, что и на мобильном устройстве
      3. Отклонить код-картинку на мобильном устройстве, нажать ""Decline"
      4. Выбрать причину отмены "The code/picture doesn't matchv"
      5. Нажать "Send".

  Expected result: "Приложение продолжает работу"
  Actual_result: "Приложение крашится"
  Severity: "Hight"
  Environment: ZTE blade A7
  Attachments:
  Reproducibility: Usually


В поле Commit changes написать Update bug_report.xml
Нажать на кнопку Commit changes
```

18. Синхронизировать внешний и локальный репозиторий TXT

```bash
git pull
```
