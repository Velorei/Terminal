|Homework. Branches||
|---|---|
|1. На локальном репозитории сделать ветки для:||
|- Postman|```git branch Postman```|
|- Jmeter|```git branch Jmeter```|
|- Check_Lists|```git branch Check_Lists```|
|- Bug_Reports|```git branch Bug_reports```|
|- SQL|```git branch SQL```|
|- Charles|```git branch Charles```|
|- Mobile_Testing|```git branch Mobile_Testing```|
|2. Запушить все ветки на внешний репозиторий|```git push --all```|
|3. В ветке Bug_Reports сделать текстовый документ со структурой баг репорта|```touch bug_reports.txt``` [bug_reports.txt](https://github.com/Velorei/Terminal/blob/Bug_Reports/bug_report.txt)|
|4. Запушить структуру багрепорта на внешний репозиторий|```git add bug_reports.txt``` + ```git commit -m "bug_reports.txt"``` + ```git push --set-upstream origin Bug_reports```|
|5. Вмержить ветку Bug_Reports в Main|```git checkout main``` + ```git merge Bug_reports```|
|6. Запушить main на внешний репозиторий|```git push --all```|
|7. В ветке Check_Lists набросать структуру чек листа|```git checkout Check_Lists``` + ```touch check_lists.txt``` [check_lists.txt](https://github.com/Velorei/Terminal/blob/Check_Lists/check_lists.txt)|
|8. Запушить структуру на внешний репозиторий|```git push --set-upstream origin Check_Lists```|
|9. На внешнем репозитории сделать Pull Request ветки Check_Lists в main|Делаем Pull Request ветки [Check_Lists](https://github.com/Velorei/Terminal/tree/Check_Lists)|
|10. Синхронизировать Внешнюю и Локальную ветки Main|```git pull```|
