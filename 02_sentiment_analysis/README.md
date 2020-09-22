# Анализ тональности текста

[Jupyter Notebook](https://github.com/sk-il/portfolio/blob/master/02_sentiment_analysis/sentiment_analysis.ipynb)

Проект был выполнен в рамках специализации "Машинное обучение и анализ данных" от Яндекс и МФТИ на Coursera.

## Задача

Побить бейзлайн в соревновании по сентимент-анализу отзывов на товары на английском языке на Kaggle Inclass:
https://www.kaggle.com/c/simplesentiment

Метрика - Accuracy.

## Вывод

Была предпринята попытка решить задачу двумя способами: с помощью TF-IDF векторизации и линейными моделями из библиотеки Skickit-learn, а также с помощью облегченной версии BERT - DistilBERT в связке с логистической регрессией. В обоих случаях бейзлайн был пробит, но, как и следовало ожидать,  DistilBERT показал лучший результат, но работал значительно дольше.

## Используемые библиотеки

- Pandas
- NumPy
- RegExp
- NLTK
- Scikit-learn
- PyTorch
- DistilBert (from Transformers)

## Данные

https://www.kaggle.com/c/simplesentiment/data
