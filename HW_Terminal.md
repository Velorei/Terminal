|Linux terminal (GitBash) commands||
|---|---|
|1. Посмотреть где я|```pwd```|
|2. Создать папку|```mkdir Terminal_dz_1```|
|3. Зайти в папку|```cd Terminal_dz_1/```|
|4. Создать 3 папки|```mkdir d1 d2 d3```|
|5. Зайти в любую папку|```cd d1```|
|6. Создать 5 файлов (3 txt, 2 json)|```touch dz1.txt dz2.txt dz3.txt dz4.json dz5.json```|
|7. Создать 3 папки|```mkdir p1 p2 p3```|
|8. Вывести содержимое папки|```ls``` или ```ls -la```|
|9. Открыть любой txt файл|```vim dz1.txt```|
|10. Написать туда что-нибудь|нажать на клавишу "i", ввести текст:<br/>pwd <br/>cd <br/>mkdir <br/>cat <br/>git add<br/>ls <br/>git commit <br/>git init <br/>git push|
|11. Сохранить и выйти|```shift```+```:```+```wq```+```return```|
|12. Выйти из папки на уровень выше|```cd ..```|
|13. Переместить любые 2 файла, которые вы создали, в любую другую папку|```mv d1/dz1.txt p1/dz1.txt``` и ```mv d1/dz2.txt p1/dz2.txt```|
|14. Скопировать любые 2 файла, которые вы создали, в любую другую папку|```cp d1/dz1.txt p1/dz1.txt``` и ```cp d1/dz2.txt p1/dz2.txt```|
|15. Найти файл по имени|```find -name dz1.txt```|
|16. Просмотреть содержимое в реальном времени|```tail -f dz1.txt```|
|17. Вывести несколько первых строк из текстового файла|```head -2 dz1.txt```|
|18. Вывести несколько последних строк из текстового файла|```tail -2 dz1.txt```|
|19. Просмотреть содержимое длинного файла|```less dz1.txt```|
|20. Вывести дату и время|```date```|
|||
|Задание*||
|1. Отправить http запрос на сервер|```curl "http://162.55.220.72:5005/object_info_3?name=Valeriia&age=18&salary=500"```|
|2. Написать скрипт который выполнит автоматические пункты|```nano script.sh```|
-------------------------------------
```
#!/bin/bash
mkdir skript
cd skript
mkdir skript_f1 skript_f2 skript_f3
cd skript_f3
touch skr_text1.txt skr_text2.txt skr_text3.txt skr_js1.json skr_js2.json
mkdir skr1 skr2 sk3
ls -la
cp skr_text1.txt skr_js1.json skr1
```
------------------------------------
```
ctrl^x 
Y(yes)
return
```
------------------------------------
```bash script.sh```
------------------------------------
