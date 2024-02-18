## <center> <img src = https://raw.githubusercontent.com/AndreyRysistov/DatasetsForPandas/main/hh%20label.jpg alt="drawing" style="width:400px;">

# PROJECT-2. Анализ резюме из HeadHunter (Блок 2 по SQL)

## Оглавление  
[1. Описание проекта](https://github.com/MrMonkeyfeeder/Project_HH2/tree/master/README.md#Описание-проекта)  
[2. Какой кейс решаем?](https://github.com/MrMonkeyfeeder/Project_HH2/tree/master/README.md#Какой-кейс-решаем)  
[3. Краткая информация о данных](https://github.com/MrMonkeyfeeder/Project_HH2/tree/master/README.md#Краткая-информация-о-данных)  
[4. Этапы работы над проектом](https://github.com/MrMonkeyfeeder/Project_HH2/tree/master/README.md#Этапы-работы-над-проектом)  
[5. Результат](https://github.com/MrMonkeyfeeder/Project_HH2/tree/master/README.md#Результат)  
[6. Выводы](https://github.com/MrMonkeyfeeder/Project_HH2/tree/master/README.md#Выводы)

### Описание проекта
Мы устроились на работу в кадровое агентство, которое подбирает вакансии для IT-специалистов. Наш первый проект — создание модели машинного обучения, которая будет рекомендовать вакансии клиентам агентства, претендующим на позицию Data Scientist. Сначала нам необходимо понять, что из себя представляют данные и насколько они соответствуют целям проекта. В литературе эта часть работы над ML-проектом называется Data Understanding, или анализ данных.

⬆️ [к оглавлению](https://github.com/MrMonkeyfeeder/Project_HH2/tree/master/README.md#Оглавление)

### Какой кейс решаем?
Каждая из частей проекта будет состоять из блока практических заданий, которые необходимо выполнить в своих Jupyter-ноутбуках, и контрольных вопросов на платформе, которые проверяются автоматически.

Наш проект включает в себя несколько этапов:

* знакомство с данными;
* предварительный анализ данных;
* детальный анализ вакансий;
* анализ работодателей;
* предметный анализ.

Требования к оформлению ноутбука-решения:

* Решение оформляется только в Jupyter Notebook.
* Решение оформляется в соответствии с ноутбуком-шаблоном.
* Каждое задание выполняется в отдельной ячейке, выделенной под задание (в шаблоне они помечены как ваш код здесь). Не следует создавать много ячеек для решения задачи — это провоцирует неудобства при проверке.
* Текст SQL-запросов и код на Python должны быть читаемыми. Не забывайте про отступы в SQL-коде.
* Выводы по каждому этапу оформляются в формате Markdown в отдельной ячейке (в шаблоне они помечены как ваши выводы здесь).
* Выводы можно дополнительно проиллюстрировать с помощью графиков. Они оформляются в соответствии с теми правилами, которые мы приводили в модуле по визуализации данных.
* Удалить ячейку с данными соединения перед фиксацией работы в GitHub.

Формат ноутбука с решением:

* Номер задания.
* Код для получения ответа.
* Результат запроса.
* Выводы по блоку заданий.
* Общий вывод в конце по результатам анализа, имеющихся данных по вакансиям.

Критерии оценки (максимум 8 баллов):

* 2 балла Правильность решения задач, логичность построения запросов.
* 2 балла Читабельность и верное форматирование запросов и кода на Python, наличие комментариев в запросах; аккуратность оформления решения.
* 2 балла Логичность и полнота выводов.
* 2 балла Дополнительные исследования данных.

Что практикуем:

* Учимся писать хороший код на Python;
* Учимся работать с pgSQL;
* Учимся получать по запросу нужные данные для минимальной следующей обработки
* Размещаем итог на GitHub.

Краткая информация о данных:

Структура базыданых:

## <center> <img src = https://lms.skillfactory.ru/asset-v1:SkillFactory+DST-3.0+28FEB2021+type@asset+block@SQL_pj2_2_1.png alt="drawing" style="width:400px;">


* VACANCIES Таблица хранит в себе данные по вакансиям и содержит следующие столбцы:
* AREAS Таблица-справочник, которая хранит код города и его название.
* EMPLOYERS Таблица-справочник со списком работодателей.
* INDUSTRIES Таблица-справочник вариантов сфер деятельности работодателей.
* EMPLOYERS_INDUSTRIES Дополнительная таблица, которая существует для организации связи между работодателями и сферами их деятельности.


⬆️[к оглавлению](https://github.com/MrMonkeyfeeder/Project_HH2/tree/master/README.md#Оглавление)

### Этапы работы над проектом:
* Импортирование нужных библиотек;
* Подготовка данных;
* Решение заданий;
* Составление графиков;
* Описание выводов и предложений.

⬆️[к оглавлению](https://github.com/MrMonkeyfeeder/Project_HH2/tree/master/README.md#Оглавление)

### Результат:
* Проведен полный анализ полученных данных;
* Анализируемые показатели приведены в читабельные таблицы;
* Подготовлена визуализация анализируемых данных;
* Сделаны выводы и предложения.

⬆️[к оглавлению](https://github.com/MrMonkeyfeeder/Project_HH2/tree/master/README.md#Оглавление)

### Выводы:
Всё глубже и глубже погружаемся в профессию! На данном этапе лучше всего усвоился SQL 😃

⬆️[к оглавлению](https://github.com/MrMonkeyfeeder/Project_HH2/tree/master/README.md#Оглавление)