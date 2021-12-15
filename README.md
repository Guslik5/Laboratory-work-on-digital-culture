# Архиватор файлов.
Целью лабораторной работы является разработка программы по архивированию
и распаковке нескольких файлов в один архив. Архиватор должен
1. Уметь архивировать несколько (один и более) указанных файлов в архив с
расширением *.arc
2. Уметь распаковывать файловых архив, извлекая изначально запаковонные
файлы
3. Предоставлять список файлов упакованных в архиве
4. Сжимать и разжимать данные при архивировании с помощью алгоритма
Хаффмана (опциональное задание, оценивается доп баллами)
#
Архиватор должен быть выполнен в виде консольного приложения,
принимающего в качестве аргументов следующий параметры

● --file FILE
Имя файлового архива с которым будет работать архиватор

● --create
Команда для создания файлового архива

● --extract;
Команда для извлечения из файлового архива файлов

● --list
Команда для предоставления списка файлов, хранящихся в архиве

● FILE1 FILE2 …. FILEN
Свободные аргументы для передачи списка файлов для запаковки


