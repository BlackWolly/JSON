# JSON
4. Создать внешний репозиторий c названием JSON.
click new for creating repository
 5. Клонировать репозиторий JSON на локальный компьютер.
git clone link  
cd JSON
 6. Внутри локального JSON создать файл “new.json”.
touch new.json
 7. Добавить файл под гит.
git add new.json
 8. Закоммитить файл.
git commit -m "add JSON file"
 9. Отправить файл на внешний GitHub репозиторий.
git push
 10. Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON.
cat >> new.json
{
	"First and Last name": "Pavlo Mandiuk",
	"Age": 36,
	"Number of pets": 0,
	"Salary": "400$"
}
 11. Отправить изменения на внешний репозиторий.
git add new.json
git commit -m "the second change"
git push
 12. Создать файл preferences.json
touch preferences.json
 13. В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON.
cat >> references.json
{
        "Film": "Star Wars",
        "Serial": "tar Treck",
        "Food": "Borsch",
        "Season": "Summer",
        "Future country": "Canada"
}
 14. Создать файл sklls.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON
cat >> skills.json
{
        "Skill": "Bash",
        "Skill": "Git",
        "Skill": "Postman",
        "Skill": "SQL",
        "Skill": "Manual testing"
}
 15. Отправить сразу 2 файла на внешний репозиторий.
git add preferences.json skills.json ; git commit -m "add two more files"
git push

 16. На веб интерфейсе создать файл bug_report.json.
add file 
create new file

 17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
Commit new file
 18. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON.
Edit this file
 19. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
Commit changes
 20. Синхронизировать внешний и локальный репозиторий JSON
git fetch
git pull
