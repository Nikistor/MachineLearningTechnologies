# Лабораторная работа №5
## Ансамбли моделей машинного обучения.
### Цель лабораторной работы: изучение ансамблей моделей машинного обучения.

### Требования к отчету:
Отчет по лабораторной работе должен содержать:
1. титульный лист;
2. описание задания;
3. текст программы;
4. экранные формы с примерами выполнения программы.

### Задание:
1. Выберите набор данных (датасет) для решения задачи классификации или регресии.
2. В случае необходимости проведите удаление или заполнение пропусков и кодирование категориальных признаков.
3. С использованием метода train_test_split разделите выборку на обучающую и тестовую.
4. Обучите следующие ансамблевые модели:
- одну из моделей группы бэггинга (бэггинг или случайный лес или сверхслучайные деревья);
- одну из моделей группы бустинга;
- одну из моделей группы стекинга.
5. (+1 балл на экзамене) Дополнительно к указанным моделям обучите еще две модели:
- Модель многослойного персептрона. По желанию, вместо библиотеки scikit-learn возможно использование библиотек TensorFlow, PyTorch или других аналогичных библиотек.
- Модель МГУА с использованием библиотеки - https://github.com/kvoyager/GmdhPy (или аналогичных библиотек). Найдите такие параметры запуска модели, при которых она будет по крайней мере не хуже, чем одна из предыдущих ансамблевых моделей.
6. Оцените качество моделей с помощью одной из подходящих для задачи метрик. Сравните качество полученных моделей.
