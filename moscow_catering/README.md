# Исследование данных o заведениях общественного питания Москвы.
## Задача
  
Заказчик исследования инвесторы из фонда «Shut Up and Take My Money» собираются открыть заведение общественного питания в Москве. Проведем исследование рынка Москвы, найдем интересные особенности, которые в будущем помогут в выборе подходящего инвесторам места и категории для открытия заведения общественного питания в Москве.
## Данные
В нашем распоряжении данные с заведениями общественного питания Москвы, составленный на основе данных сервисов Яндекс Карты и Яндекс Бизнес на лето 2022 года.
- название заведения
- адрес заведения
- категория заведения, например «кафе», «пиццерия» или «кофейня»
- информация о днях и часах работы
- широта географической точки, в которой находится заведение
- долгота географической точки, в которой находится заведение
- рейтинг заведения по оценкам пользователей в Яндекс Картах (высшая оценка — 5.0)
- категория цен в заведении, например «средние», «ниже среднего», «выше среднего» и так далее
- строка, которая хранит среднюю стоимость заказа в виде диапазона
- число с оценкой среднего чека
- число с оценкой одной чашки капучино
- число, выраженное 0 или 1, которое показывает, является ли заведение сетевым
- административный район, в котором находится заведение
- количество посадочных мест.
## Используемые библиотеки
Python, Pandas, Plotly, Seaborn, Folium, Matplotlib