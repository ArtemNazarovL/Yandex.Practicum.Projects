# Customer churn

Every month, in small quantities, customers leave the bank of the bank. After analyzing the situation, marketers realized that retaining customers is cheaper than attracting new ones.
It is necessary to build a model based on historical data that can predict whether the client will leave. Metric used: F1-measure to be brought to a minimum
up to 0.59. It is also necessary to plot the AUC-ROC curve and compare it with the F-1 measure.

### Fields of activity: business, investments, banking, lending.
### Direction of activity: Machine learning, classification.
### Skills and tools: Python, Pandas, Scikit-learn.
### Project objectives: to determine whether the client will leave the bank, based on the data.

### Table of contents.
- Step 1. Data preparation.\
1.1. Loading data and getting to know it for the first time.\
1.2. Data preparation.
- Step 2. Study of the problem.\
2.1. Decision tree.\
2.2. Random forest.\
2.2. logistic regression.
- Step 3. Fighting imbalance.\
3.1. Class weighting.\
3.2. Upsampling.\
3.3. downsampling.
- Step 4. Model testing.

### Result of work:
- We studied and prepared the data;
- Conducted a test of models without class balancing and chose a random forest as a working model;
- Conducted a test of balancing methods for training models and chose a class weighting method;
- We tested the model on a test sample and got a result slightly higher than the required one - 0.63 (F-measure);
- Gave recommendations on the use of the model (setting the cut-off threshold at 0.38).

### Project status:
Completed.

# Отток клиентов

Каждый месяц , в небольших количествах, из банка банка уходят клиенты. Маркетологи проанализировав ситуацию, поняли, что сохранять клиентов дешевле, чем привлекать новых.
Необходимо построить модель, на основе исторических данных, способную предсказать уйдет ли клиент. Используемая метрика: F1-мера, которую нужно довести как минимум 
до 0.59. Также необходимо построить AUC-ROC кривую и сравнить ее с F-1 мерой.

### Сферы деятельности: бизнес, инвестиции, банковская сфера, кредитование.
### Направление деятельности: Машинное обучение, классификация.
### Навыки и инструменты: Python, Pandas, Scikit-learn.
### Задачи проекта: определить уйдет клиент из банка, на основе данных.

### Оглавление.
- Шаг 1. Подготовка данных.\
1.1. Загрузка данных и первое знакомство с ними.\
1.2. Подготовка данных.
- Шаг 2. Исследование задачи.\
2.1. Решающее дерево.\
2.2. Случайный лес.\
2.2. Логистическая регрессия.
- Шаг 3. Борьба с дисбалансом.\
3.1. Взвешивание классов.\
3.2. Upsampling.\
3.3. Downsampling.
- Шаг 4. Тестирование модели.

### Результат работы:
- Мы изучили и подготовили данные;
- Провели тест моделей без балансировки классов и выбрали случайный лес в качестве рабочей модели;
- Провели тест способов балансировки для обучения моделей и выбрали метод взвешивания классов;
- Испытали модель на тестовой выборке и получили результат чуть выше требуемого - 0.63 (F-мера);
- Дали рекомендации по использованию модели (установление порога отсечения на уровне 0,38).

### Статус проекта:
Завершен.
