Чтобы код работал, к нему нужно подключить библиотеку FANN http://leenissen.dk/fann/wp/
Я собирала его в проекте Visual Studio, указывая пути к библиотекам нейросети и заголовочным файлам
Также нужно добавить fannfloat.dll в debug проекта

В файле 630_float.net хранятся данные об обученной нейросети. Цифра соответствует номеру варианта
В файле training.txt содержатся входные и выходные значения для тренировки нейросети
Код Learn.cpp отвечает за обучение сети и запись в файл
Код Program.cpp - непосредственно программа, удовлетворяющая условию задачи
