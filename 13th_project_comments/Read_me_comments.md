# Classification of online store comments
The online store is developing a service in which users can edit and supplement product descriptions, like in wiki communities.
In other words, users themselves give characteristics to goods. Therefore, the service needs a tool that will highlight toxic comments so that moderators
could handle them on their own.

In this project, we will teach the model to classify comments into taxic and all the rest.

### Fields of activity: Internet services, start-ups.
### Activities: NLP, machine learning.
### Skills and tools: Python, Pandas, BERT, nltk, tf-idf.
### Project Goals: Identify toxic comments.

### Table of contents.
- Step 1. Description of the project.
- Step 1.1. Training.
- Step 1.2. Education.
- Step 1.3. Conclusions.

### Result of work:
Lgbm made it possible to achieve the required level of the metric F1 = 0.7698 (F1>75 is the rear requirement). LGBM training time is less than Cat Boost. Possible to achieve better results
on both LGBM and Cat Boost, adjusting the parameters and most likely increasing the training time. With the current parameters, the best model is LGBM. Regression turned out
faster than other models, but showed the worst quality.

### Project status:
Completed.

# Классификация комментраиев интернет магазина
Интернет-магазин разрабатывает сервис, в котором пользователи могут редактировать и дополнять описания товаров, как в вики-сообществах. 
Другими словами пользователи сами дают характеристики товарам. Поэтому сервис нуждается в инструменте, который будет выделять токсичные комментарии, чтобы модераторы 
могли обработать их самостоятельно.

В этом проекте научим моедль классифицировать комментарии на таксичные и все остальные.

### Сферы деятельности: интернет-сервисы, стартапы.
### Направления деятельности: NLP, машинное обучение.
### Навыки и инструменты: Python, Pandas, BERT, nltk, tf-idf.
### Задачи проекта: определить токсичные комментарии.

### Оглавление.
- Шаг 1. Описание проекта.
- Шаг 1.1. Подготовка.
- Шаг 1.2. Обучение.
- Шаг 1.3. Выводы.

### Результат работы:
Lgbm позволил достичь небходимого уровня метрики F1 = 0.7698 (F1>75 - требование задния). Время обучения LGBM меньше чем у Cat Boost. Возможно достичь лучших результатов 
и на LGBM и на Cat Boost, подбирая параметры и, скорее всего, увеличивая время обучения. С текущими параметрами наилучшей моделью является LGBM. Регрессия оказалсь 
быстрее остальных моделей, но показала хучшее качество. 

### Статус проекта:
Завершен.
