# GitHub_HomeWork1

1. Создайте текстоовый файл как в первом ДЗ по Terminal - Done
2. Сценарий перенесите в этот файл - Done
3. На против каждого действия - напишите команду в GitBash - Done
`ДЛЯ РАБОТЫ С ГИТ сгенерировать SSH ключ`
 
[JSON]()

 1. Создать внешний репозиторий c названием JSON
 ```
 [Repositiries] > New > Name > Create repository
```
 1. Клонировать репозиторий JSON на локальный компьютер (Code - копировать ssh):
```
git clone <link>
```
 1. Внутри локального JSON создать файл “new.json” 
 ```
 cd JSON > touch new.json
```
 1. Добавить файл под гит  
 ```
 git add . (или имя файла)
```
 1. Закоммитить файл  
 ```
 git commit -m <message>
```
 1. Отправить файл на внешний GitHub репозиторий 
 ```
 git push
```
 1.  Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON.
```
vim new.json
i
(ввод данных в json формате)
esc
:wq
 1.  Отправить изменения на внешний репозиторий - 
git add new.json
git commit -m "info"
git push
```
 1.  Создать файл preferences.json 
```
touch preferences.json
```
 1.  В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, страна которую хотели бы посетить) в формате JSON (вместе) 
```
cat > preferences.json
(ввод данных в формате JSON)
Enter ctrl+D
```
 1.  Создать файл sklls.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON 
```
cat > sklls.json
(ввод данных в формате JSON)
Enter ctrl+D
```
1.  Отправить сразу 2 файла на внешний репозиторий 
```
git add preferences.json skills.json или git add .
git commit -m "2f prefer and skills"
git push
```
 1.  На веб интерфейсе создать файл bug_report.json 
```
[Add file] > [Create new file] > ввод Name file 
```
 1.  Сделать Commit changes (сохранить) изменения на веб интерфейсе 
 ```
 [Commit new file] <имя_файла>
 ``` 
 1.  На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON. 
```
Choose bug_report.json > [Edit this file] 
```
 1.  Сделать Commit changes (сохранить) изменения на веб интерфейсе
 ```
 [commit changes]
```
 1.  Синхронизировать внешний и локальный репозиторий JSON 
 ```
 git pull
 ```
 
 [XML]()

 1.  Создать внешний репозиторий c названием XML 
 ```
 [Repositiries] > New > Name > Create repository
```
 1.  Клонировать репозиторий XML на локальный компьютер 
 ``` 
 git clone git@github.com:Antipina-Anastasiia/XML.git
```
 1.  Внутри локального XML создать файл “new.xml” 
 ```
 cd XML > touch new.xml
```
 1.  Добавить файл под гит  
 ```
 git add new.xml
```
 1.  Закоммитить файл 
 ```
 git commit -m "add f xml" 
```
 1.  Отправить файл на внешний GitHub репозиторий 
 ```
 git push
```
 1.  Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML -
```
vim new.xml 
i
(add info xml format)
esc 
:wq
```
1.  Отправить изменения на внешний репозиторий 
```
 git add new.xml
 git commit -m "add info"
 git push
```
 1.  Создать файл preferences.xml 
 ```
 touch preferences.xml
 ```
 1.  В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате XML 
 ```
vim preferences.xml
i
add info esc 
enter ":wq"
```
 1.  Создать файл sklls.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML 
 ```
cat > skills.xml
add info
enter
ctrl+d
```

 1.  Сделать коммит в одну строку
 ```
git add . && git commit -m "add 2 file XML"
```
 1.  Отправить сразу 2 файла на внешний репозиторий 
 ```
 git push
```
 1.  На веб интерфейсе создать файл bug_report.xml. 
 ```
[Add file] > [Create new file] > Name: bug_report.xml
 ```
 1.  Сделать Commit changes (сохранить) изменения на веб интерфейсе. 
 ```
[Add file] > [Create new file] > ввод Name file > [Commit new file] 
```
 1.  На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML. 
 ```
 Choose bug_report.xml > [Edit this file]
 ```
 1.  Сделать Commit changes (сохранить) изменения на веб интерфейсе.
 ```
[Edit this file] > написать баг > [commit changes]
```
 1.  Синхронизировать внешний и локальный репозиторий XML 
 ```
 git pull
 ```


[TXT]()

 1. Создать внешний репозиторий c названием TXT 
 ```
 [Repositiries] > New > Name > Create repository
 ```
 1. Клонировать репозиторий TXT на локальный компьютер 
 ```
 git clone git@github.com:Antipina-Anastasiia/TXT.git
 ```
 1. Внутри локального TXT создать файл “new.txt” 
 ```
 touch new.txt
 ```
 1. Добавить файл под гит 
 ```
 git add new.txt
 ```
 1. Закоммитить файл 
  ```
  git commit -m "add f txt" 
  ```
 1. Отправить файл на внешний GitHub репозиторий 
 ```
 git push
```
 1. Отредактировать содержание файла “new.txt” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате TXT.
```
vim new.txt 
i
add info
esc 
:wq 
```
 1. Отправить изменения на внешний репозиторий 
```
git add new.xml
git commit -m "add info"
git push
```
 1. Создать файл preferences.txt 
 ```
touch preferences.txt
```
 1.  В файл preferences.txt” добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, страна которую хотели бы посетить) в формате TXT. 
```
cat > preferences.txt
info xml
enter
ctrl+d
```
 1.  Создать файл sklls.txt добавить информацию о скиллах которые будут изучены на курсе в формате TXT 
```
cat > skills.txt
(ввод данных в формате txt)
Enter ctrl+D
```
 1.  Сделать коммит в одну строку. 
 ```
git add . && git commit -m "add 2 file txt"
```
 1.  Отправить сразу 2 файла на внешний репозиторий 
 ```
 git push
```
 1.  На веб интерфейсе создать файл bug_report.txt. 
 ```
 [Add file] > [Create new file] > Name: bug_report.txt
 ```
 1.  Сделать Commit changes (сохранить) изменения на веб интерфейсе 
 ```
[Add file] > [Create new file] > ввод Name file > [Commit new file] 
```
 1.  На веб интерфейсе модифицировать файл bug_report.txt, добавить баг репорт в формате TXT
 ```
Choose bug_report.txt > [Edit this file]
```
 1.  Сделать Commit changes (сохранить) изменения на веб интерфейсе 
 ```
[Edit this file] > написать баг > [commit changes]
```
 1.  Синхронизировать внешний и локальный репозиторий TXT 
 ```
 git pull
```

