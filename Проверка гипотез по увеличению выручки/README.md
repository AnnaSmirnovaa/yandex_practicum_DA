# Проверка гипотез по увеличению выручки в интернет-магазине. Оценка результатов A/B теста.

## Задача
Используя данные интернет-магазина необходимо приоритизировать гипотезы, запустить A/B-тест, проанализировать результаты
## Данные
- краткое описание гипотезы
- охват пользователей по 10-балльной шкале
- влияние на пользователей по 10-балльной шкале
- уверенность в гипотезе по 10-балльной шкале
- затраты ресурсов на проверку гипотезы по 10-балльной шкале. Чем больше значение Efforts, тем дороже проверка гипотезы
- идентификатор заказа
- идентификатор пользователя, совершившего заказ
- дата, когда был совершён заказ
- выручка заказа
- группа A/B-теста, в которую попал заказ
- дата
- группа A/B-теста
- количество пользователей в указанную дату в указанной группе A/B-теста

## Результаты исследования
Провела приоритизацию гипотез по фреймовкам ICE и RICE, запустила A/B-тест,  проанализировала результаты, построила графики кумулятивной выручки, среднего чека, конверсии по группам, а затем посчитала статистическую значимость различий конверсий и среднийх чеков по сырым и очищенным данным. Сделала вывод о возможности остановки теста.
## Используемые библиотеки
Python, Pandas, Matplotlib, NumPy, SciPy
