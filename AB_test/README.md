## 🎎Анализ результатов А/В-теста
📕[ipynb](https://github.com/nottdzr/Portfolio/blob/main/AB_test/AB_test.ipynb)

### Описание проекта 
Для принятия решения о внедрении улучшенной системы рекомендаций интернет-магазина было проведено А/B-тестирование. Ожидается, что новая система рекомендаций повысит конверсию пользователей на каждом этапе воронки продаж не менее, чем на 10%. Необходимо оценить результаты теста, а также корректность его проведения в целом (пересечения с конкурирующим тестом, влияние сезонности, соответствие требованиям ТЗ и т.п.).

Данные получены в виде нескольких датасетов: профили пользователей; действия пользователей; участники тестов с распределением по группам; перечень првоеденных маркетинговых событий.

### Навыки и инструменты
🐍Python: pandas, numpy, statsmodels.stats.proportion, matplotlib, seaborn, plotly

### Общие выводы
Была построена воронка продаж для обеих групп теста. Расчет конверсии показал, что новая система рекомендаций не показала ожидаемых результатов, а наоборот ухудшила имеющиеся показатели. Однако, были выявлены множественные нарушения при проведении А/B-теста, которые могли исказить результаты, поэтому рекомендуется провести тест повторно либо отказаться от внедрения новой системы рекомендаций. 
