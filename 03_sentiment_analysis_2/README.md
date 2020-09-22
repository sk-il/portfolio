# Анализ тональности текста. Парсинг данных.

### [Jupyter Notebook](https://github.com/sk-il/portfolio/blob/master/03_sentiment_analysis_2/sentiment_analysis_2.ipynb)

Проект был выполнен в рамках специализации "Машинное обучение и анализ данных" от Яндекс и МФТИ на Coursera.

## Задача

Оценить возможное качество работы алгоритма для задачи анализа тональности отзывов на товары на русском языке. Предоставлена только небольшая тестовая выборка, данные для обучения нужно получить самостоятельно.

Оценка качества в этом задании реализована через контест на Kaggle Inclass:

https://inclass.kaggle.com/c/product-reviews-sentiment-analysis

Метрика - Accuracy, таргет - строго больше 85%.

## Вывод

Данные для обучения были спарсенны с сайта с отзывами на технику. Удалось пробить безйлайн с первого раза с помощью логистической регрессии.

## Используемые библиотеки

- Pandas
- Requests
- Beautiful Soup
- RegExp
- Pymorphy
- Scikit-learn

## Данные

https://www.kaggle.com/c/product-reviews-sentiment-analysis/data
