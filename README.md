# PROJECT-3.-EDA-Feature-Engineering

## Оглавление

1. Описание проекта.
2. Какой кейс решаем?
3. Краткая информация о данных.
4. Этапы работы над проектом.
5. Результаты

## Описание проекта.

Вы работаете дата-сайентистом в компании Booking. Одна из проблем компании — это нечестные отели, которые накручивают себе рейтинг. Одним из способов обнаружения таких отелей является построение модели, которая предсказывает рейтинг отеля. Если предсказания модели сильно отличаются от фактического результата, то, возможно, отель ведёт себя нечестно, и его стоит проверить.

## Какой кейс решаем?

✔️ создадите свою первую модель, основанную на алгоритмах машинного обучения;

✔️ примете участие в [соревновании на Kaggle](https://www.kaggle.com/code/aleksandrosip/project-3-eda-feature-engineering);

✔️ поймёте, как правильно «подготовить» данные, чтобы ваша модель работала лучше.

*Что от нас требуется?*

Модель машинного обучение нам дана в готовом виде. Более того нам, по условию задачи, запрещено изменять ее параметры.

Основная наша задача состоит в:
* очистке данных;
* проектировании новых признаков;
* Разведовательном анализе данных (IDA).

 В результате проделанной работы мы должны добиться наилучшего показателя метрики и выставить свой результат на соревнование на Kaggle.

## Краткая информация о данных.

Для рашения поставленной задачи нам представлен датасет, в котором содержатся сведения о 515 738 отзывов на отели Европы.

Датасет уже разбит на тренировочные и тестовые данные в соотношении 1/3. Проекту также предоставлен образец файла submission.csv в который мы запишем результаты работы модели, чтобы выставить на соревнование.

## Этапы работы над проектом.

Работа над проектом проводилась на платформе Kaggle. Где имеется 12 версий кода в которых путём создания, преобразования, удаления признаков предпринимались попытки улучшения метрики.

Применялись следующие шаги при работе с данными:

* удаление признаков с очень сильной корреляционной связью (мультиколлинеарность); удаление признаков заведомо лишних для данной задачи

* преобразование признаков путем стандартизации и кодирования в числовой тип данных

* создание и обучение модели

* запись результатов в файл

