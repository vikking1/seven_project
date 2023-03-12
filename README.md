# seven_project
Из «Бета-Банка» стали уходить клиенты. Каждый месяц. Немного, но заметно. Банковские маркетологи посчитали: сохранять текущих клиентов дешевле, чем привлекать новых.

Нужно спрогнозировать, уйдёт клиент из банка в ближайшее время или нет. Вам предоставлены исторические данные о поведении клиентов и расторжении договоров с банком.

Постройте модель с предельно большим значением F1-меры. Чтобы сдать проект успешно, нужно довести метрику до 0.59. Проверьте F1-меру на тестовой выборке самостоятельно.


В ходе данной работы была разработана модель, котрая может предугадывать покинет ли человек банк или нет, со среднее гармоническим значением 0.609, и а площадь под кривой ROC равный 0.85 и коэффициент детерминаци равный 0.818, что говорит 81.8 процент ответов будет правильны.
Так же из анализа были убраны такие столбцы как ID фамилия и индекс (не несут какую либо информацию для данной модели)
Изменен тип хранения данных в не которых столбцах, ислледована модель с дисбалансом и с балансированной выборкой и построены таблицы.
Увелечение значения выборки повлияло на средне гармоническое число положительно т.е. значение стало больше
