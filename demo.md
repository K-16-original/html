# html demo
Демо репозиторий для сайта проекта K-16 
Правила работы:
1.Комиты писать только на русском языке и они должны быть понятными.
2.При выполнении задачи с доски в миро достаточно указать в скобках рядом, что задача взята из миро.
3.Файлы называть нормальными и понятными названиями на английском языке.
4.При выкладывании нового комита писать в нашу группу в ватсапе.
API
GET /filtering/

{
  "filter": "column"
  "filter_name": "Дата рождения",
  "filter_meaning": "20/02/2008"
}
Виды фильтров: 
1.Column - ищет строки, где значение указанной пользователем колонки(нок) равно заданному им параметру.
2.Row - ищет колонки, где значение указанной пользовалетем строки равно заданному им параметру(врятли понадобится пользователю, но пусть будет)
Подвиды:
filter_name - имя столбца/колонки, в которую указал пользователь.
filter_meaning - значение, указанное пользовалетем, строки/колонки с которым нужно найти(оно должно быть там, где указанно в filter_name) 
Нужно будет дописать отправку самой таблицы. 
