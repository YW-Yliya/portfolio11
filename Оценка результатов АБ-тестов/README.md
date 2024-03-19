# Проверка гипотезз по уввеличению выручки в интернет-магазине - оценка результатов А/B теста

## Цель:
Приоритезировать гипотезы; запустить A/B-тест; проанализировать результаты.

### Описание данных 
Файл `hypothesis.csv`:

- `Hypothesis` — краткое описание гипотезы;
- `Reach` — охват пользователей по 10-балльной шкале;
- `Impact` — влияние на пользователей по 10-балльной шкале;
- `Confidence` — уверенность в гипотезе по 10-балльной шкале;
- `Efforts` — затраты ресурсов на проверку гипотезы по 10-балльной шкале. Чем больше значение Efforts, тем дороже проверка гипотезы.

Файл `orders.csv`:

- `transactionId` — идентификатор заказа;
- `visitorId` — идентификатор пользователя, совершившего заказ;
- `date` — дата, когда был совершён заказ;
- `revenue` — выручка заказа;
- `group` — группа A/B-теста, в которую попал заказ.

Файл `visitors.csv`:

- `date` — дата;
- `group` — группа A/B-теста;
- `visitors` — количество пользователей в указанную дату в указанной группе A/B-теста


## Выводы

Prioritization of hypotheses was carried out using the ICE and RICE frameworks. Then we analyzed the results of the A/B test, built graphs of cumulative revenue, average bill,
conversions by groups, and then calculate the statistical significance of the differences in conversions and average checks based on raw and cleaned data. Based on the analysis it was
a decision was made that further testing was inappropriate.

## Навыки и инструменты

Python, Pandas, Matplotlib, SciPy, A/B-тестирование
