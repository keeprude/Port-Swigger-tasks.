1)Просто добавляем в конец адресной строки 'UNION SELECT NULL--  -> получаем ошибку.
2)Добавим еще NULL-- -> получаем ошибку.
3)Добавим третий NULL-- все получилось, то есть выдается 3 столбца. 
('UNION SELECT NULL, NULL, NULL--)
