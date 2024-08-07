# Тестовое задание   от АНО «Центр развития «Среда возможностей»
**Выполнил:Колыванова С.В.<https://t.me/SerVa1>**

## Данные

**Ссылка на данные:**
https://data.mos.ru/opendata/60562?isDynamic=false

https://disk.yandex.ru/d/E9GKZjJyEv7K1A  

файл с геоданными:https://disk.yandex.ru/d/H4dQKVDpU4Rd8g

## Описание задачи от заказчика:

Компания, являющаяся государственным учреждением
выездных проверок и выявление незаконных строительных объектов.

**Данные для анализа:**

-Обширный реестр земельных участков в городе Москве, содержащий разнообразную информацию о каждом участке.

-Файл данных о проведенных выездных проверках.

**Важно:** 
- Данные должны быть сгруппированы по округам города Москвы.

- Необходимо обеспечить высокую степень детализации географических координат для города Москвы (добавить координаты г.Москва с высокой детализацией).

**Требования к выполнению задания:**

Заказчика интересует информация, разбитая по округам, включая:
 - Общее количество объектов.
 
 - Способы их классификации.
 
 - Общие характеристики объектов.

 - Локализацию объектов.
 
 - Количество и распределение проверок по объектам.
 
 - Распределение нагрузки между проверками.
 
 - Частота проведения проверок и количество выявленных нарушений.
 
**Особое внимание следует уделить районам, которые подвергаются проверкам чаще других, и выявить, существуют ли районы с повышенным количеством нарушений.**

Критично уложиться в дедлайн проекта(3дня) и предложить рекомендации заказчику.
Критерии оценки:
Умение кандидата проводить аналитический анализ и визуализацию данных.
Предпочтительно предоставление результатов анализа в форме дашборда и презентации с выводами, удобная для клиент (но ограничений по выбору инструмента - нет).
Визуализация данных на карте Москвы, с высокой степенью детализации, будет считаться значительным преимуществом.
## Цель

Помочь заказчику решить задачи по визуализации и улучшению контроля над земельными участками и оценить эффективность выездных проверок для обеспечения правопорядка в городе.

Предобработка проводилась в Jupyter Notebook(Python).(Более подробно  можно посмотреть на вкладке Документация)

Данные представлены за период с 09.01.2023 по 29.03.4024 г . Москва
## Выводы и рекомендации
- большая часть объектов  расположена в ЦАО(19.6%),ЮВАО(17.6%),ВАО(13,4%)

- В 37%  случаев это пристройки и строения

- Более половины мероприятий проводится по поручению руководителя.

- Демонтировано по результатам  проверок  1262 объекта

- Среднее число проверок на объект- 1.08

- В 77%  случаев выявлены нарушения.И в 60 % случаев это нецелевое использование ЗУ.В 86% случаев это были выездные  обследования.

- В 80%  случаев  проверки проводятся в отношении юридических лиц.

- Максимальное число проверок проводилось на объекте 407, ЦАО, Басманный -47!(не ясно что это)

- Максимальное время проверки - 4 часа.Минимальное - 0,02 часа.(чуть больше минуты?!)

**Вопросы к данным** 

- Количество мероприятий  не равно уникальному числу проверок.То есть в рамках одной проверки может быть проведено  не одно мероприятие.И в рамках одного распоряжения может быть более одной задачи.Это действительно реаально?

- По общему типу 2937 объектов в "Объектах" являются земельными участками.В "Мероприятиях" 4 из них  отмечены как НФ(нежилой фонд?)

- Неясен столбец 'Количество объектов' имеет диапазон от 1 до 12001 применительно к 1 id объекта.

- Нет единообразия в наименованиях и содержимом аналогичных полей на разных вкладках.

- Неясно как проставляется время на объекте???
## Ссылка на дашборд:<https://datalens.yandex/5fq16d17v19mt>
