# STPY-21 (Statistics @ Python)

# (#1) «Базовые понятия статистики»: анализ датасета о состоянии здоровья лошадей, испытывающих кишечные колики
- корректное заполнение пропусков в этом датасете в зависимости от типов данных

# (#2) Анализ датасета "YouTube Trends", построение визуализаций:
- Столбчатая диаграмма "Топ-10 категорий видео по просмотрам"
- Круговая диаграмма распределения стран по общему количеству просмотров
- Гистограмма для сравнения распределения "лайков-к-просмотрам", "дизлайков-к-просмотрам" и "комментов-к-просмотрам"
- Боксплот для оценки распределения лайков, дизлайков и комментов пользователей
- Оценка выбросов по 'likes-to-views', 'dislikes-to-views'
- Scatter-plot корреляции между просмотрами и лайками/дизлайками по каналам
- Линейная диаграмма с динамикой просмотров по месяцам
- Гистограмма распределения "лайков-к-просмотрам", "дизлайков-к-просмотрам" на основании датафрейма по странам

# (#3) Случайные события. Случайные величины:
- Моделирование игры против игрового автомата типа "777" методом Монте-Карло
- Расчет среднего выигрыша(проигрыша)

# (#4) «Корреляция и корреляционный анализ» на датасете "Mortality and Water Hardness":
https://www.kaggle.com/ukveteran/mortality-and-water-hardness

В этом датасете содержатся данные по средней годовой смертности на 100000 населения и концентрации кальция в питьевой воде для 61
большого города в Англии и Уэльсе. Города дополнительно поделены на северные и южные.

Задание 1.
Ответить на вопрос: есть ли связь между жёсткостью воды и средней годовой смертностью?
- Построить точечный график
- Рассчитать коэффициенты корреляции Пирсона и Спирмена
- Построить модель линейной регрессии
- Рассчитать коэффициент детерминации
- Вывести график остатков

Задание 2.
Ответить на вопрос: сохраняется ли аналогичная зависимость для северных и южных городов по отдельности?
- Разделить данные на 2 группы
- Повторить аналогичные шаги из пункта 1 для каждой группы по отдельности

# (#5) «Задачи классификации и кластеризации» на датасете "Ирисы Фишера":
- Возьмите датасет с цветками iris’а (функция load_iris из библиотеки sklearn)
- Оставьте два признака - sepal_length и sepal_width и целевую переменную - variety
- Разделите данные на выборку для обучения и тестирования
- Постройте модель LDA
- Визуализируйте предсказания для тестовой выборки и центры классов
- Отбросьте целевую переменную и оставьте только два признака - sepal_length и sepal_width
- Подберите оптимальное число кластеров для алгоритма KMeans и визуализируйте полученную кластеризацию
