# JSON
#### Создать внешний репозиторий c названием JSON.
```sh
click new for creating repository
```
#### Клонировать репозиторий JSON на локальный компьютер.
```sh
git clone link  
cd JSON
```
#### Внутри локального JSON создать файл “new.json”.
```sh
touch new.json
```
#### Добавить файл под гит.
```sh
git add new.json
```
#### Закоммитить файл.
```sh
git commit -m "add JSON file"
```
#### Отправить файл на внешний GitHub репозиторий.
```sh
git push
```
#### Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON.
```sh
cat >> new.json
		{
			"First and Last name": "Pavlo Mandiuk",
			"Age": 36,
			"Number of pets": 0,
			"Salary": "400$"
		}
```
#### Отправить изменения на внешний репозиторий.
```sh
git add new.json
git commit -m "the second change"
git push
```
#### Создать файл preferences.json
```sh
touch preferences.json
```
#### В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON.
```sh
cat >> references.json
		{
		       "Film": "Star Wars",
 		       "Serial": "tar Treck",
 		       "Food": "Borsch",
		       "Season": "Summer",
 		       "Future country": "Canada"
		}
```
#### Создать файл sklls.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON
```sh
cat >> skills.json
		{
		        "Skill": "Bash",
		        "Skill": "Git",
 		        "Skill": "Postman",
			"Skill": "SQL",
			"Skill": "Manual testing"
		}
```
#### Отправить сразу 2 файла на внешний репозиторий.
```sh
git add preferences.json skills.json ; git commit -m "add two more files"
git push
```
#### На веб интерфейсе создать файл bug_report.json.
```sh
add file 
create new file
```
#### Сделать Commit changes (сохранить) изменения на веб интерфейсе.
```sh
Commit new file
```
#### На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON.
```sh
Edit this file
```
#### Сделать Commit changes (сохранить) изменения на веб интерфейсе.
```sh
Commit changes
```
#### Синхронизировать внешний и локальный репозиторий JSON
```sh
git fetch
git pull
```
