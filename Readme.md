Предсказание оттока клиентов.
==============================

Описание проекта:
----------------------

Банк столкнулся с проблемой - стали уходить клиенты. Маркетологи решили, что сохранять текущих клиентов дешевле, чем привлекать новых. Цель - спрогнозировать, уйдёт клиент из банка в ближайшее время или нет. Необходимо построить модель с достаточным значением F1-меры (как минимум 0.59), а для построенной модели измерить AUC-ROC, и сравнить её значение с F1-мерой. В распоряжении исторические данные о поведении клиентов и расторжении договоров с банком.

Результат: 
----------------

Построили модель, прогнозирующую уход клиента. Обучили финальную модель и проверили ее на тестовой выборке. Достигли значения F1 = 0.61. Исследовали метрику AUC-ROC и сравнили её с F1.

Инструменты и техники:
----------------------

Numpy, scikit-learn, Python, Pandas, предобработка данных, масштабирование признаков, взвешивание классов, измерение метрик F1 и AUC-ROC, downsampling

Статус проекта: Закончен
