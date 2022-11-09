# JSON

## Задание 
 1. Создайте текстовый файл как в первом ДЗ по Terminal.
 2. Сценарий перенесите в этот файл.
 3. На против каждого действия - напишите команду в GitBash
```bash
Command: cd Desktop/Тестирование/gitrepo/
Перемещаемся в папку, куда будем клонировать репозиторий, который мы только что создали.
```

4. Создать внешний репозиторий c названием JSON.

![](https://github.com/Ilya-Tsatsuro/Screenshot/blob/main/HW_1_Git/Create_repo.png?raw=true)

5. Клонировать репозиторий JSON на локальный компьютер.
```bash
Command: git clone git@github.com:Ilya-Tsatsuro/JSON.git    
```

6. Внутри локального JSON создать файл “new.json”.
```bash 
Command: touch new.json
```
7. Добавить файл под гит.
```bash
Command: git add 
```
8. Закоммитить файл.
```bash
Command: git commit -m "add new.json"  
```
9. Отправить файл на внешний GitHub репозиторий.
```bash
Command: git push
```
10. Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON.
```bash
Command: cat >> new.json
{
    "name": "Ilia",
    "age": 29,
    "pet": "dog",
    "desired_salary": 5000
}
```
11. Отправить изменения на внешний репозиторий.
```bash
Command: git commit -m "modify new.json"
Command: git push
```
12. Создать файл preferences.json
```bash 
Command: touch preferences.json
```
13. В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON.
```bash
Command: cat >> preferences.json
{
    "name": "Ilia",
    "age": 29,
    "pet": "dog",
    "desired_salary": 5000
}
```
14. Создать файл skills.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON
```bash 
Command: touch skills.json
```
```bash
Command: cat >> preferences.json
{
    "skills": ["SDLC", "STLC", "HTTP", "JSON", "XML", "API", "Postman", "Charles", "Fiddler", "DevTools", "VPN", "SQL", "Redis"]
}
```
15. Отправить сразу 2 файла на внешний репозиторий.
 ```bash 
Command: git add .
```
 ```bash 
Command: git commit -am "add 2 files"
```
 ```bash 
Command: git push
```
16. На веб интерфейсе создать файл bug_report.json.

![](https://github.com/Ilya-Tsatsuro/Screenshot/blob/main/HW_1_Git/Create_new_file.png?raw=true)

![](https://github.com/Ilya-Tsatsuro/Screenshot/blob/main/HW_1_Git/Create_bg.png?raw=true)

17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.

![](https://github.com/Ilya-Tsatsuro/Screenshot/blob/main/HW_1_Git/Commit_new_file.png?raw=true)

18. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON.

![](https://github.com/Ilya-Tsatsuro/Screenshot/blob/main/HW_1_Git/Edit_a_file.png?raw=true)

![](https://github.com/Ilya-Tsatsuro/Screenshot/blob/main/HW_1_Git/Edit_bg.png?raw=true)

19. Сделать Commit changes (сохранить) изменения на веб интерфейсе.

![](https://github.com/Ilya-Tsatsuro/Screenshot/blob/main/HW_1_Git/Commit_bg.png?raw=true)

20. Синхронизировать внешний и локальный репозиторий JSON
```bash
Command: git pull
```