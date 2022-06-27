# Exploratory analysis of steel processing steps and construction of a steel temperature prediction model.

The metallurgical plant set a goal to reduce electricity costs. To do this, it is necessary to learn how to effectively predict the steel temperature at different stages.
production.

### Table of contents.
1. Loading files and preparing data.
- 1.1. Downloading files.
- 1.2. Data preparation
2. Exploratory data analysis.
- 2.1. Temperature.
- 2.2. heating duration.
- 2.3. active power.
- 2.4. reactive power.
3. Creation of additional signs and consolidation of tables.
- 3.1. Temperatures.
- 3.2. heating.
- 3.3. alloying materials.
- 3.4. Merging tables.
4. Gradient boosting.
5. Linear regression.

### Fields of activity: production, metallurgy.
### Activities: data scientist, data analyst.
### Skills and tools: Python, Pandas, Matplotlib, Scikit-learn, Statsmodels, Catboost, exploratory data analysis, data visualization, data preprocessing.
### Objectives of the project: to determine the temperature of steel at different stages of production.

### Result of work:
1. The last sample temperature of each batch was chosen as the target. The data has been prepared and cleaned.
2. Were investigated: temperatures, heating and power. The signs are normally distributed, but the power and heating time are colorized, so the formula was used
full power to create a new feature. Collated features have been removed.
3. Features were also created: the time between temperature measurements and the first temperature.
4. All features were combined into one dataframe, which was divided into training and test sets.
5. Cross-validation parameters were selected for the CatBoost gradient boosting model and MAE was obtained on the test set equal to 5.4.
6. Linear regression was trained on the training set and tested on the test set. MAE is less than six. A linear relationship was found between the two alloying
materials.

### Project status:
Completed.

# Исследовательский анализ этапов обработки стали и построение модели предсказания температуры стали.

Металлургический завод поставил задачу уменьшить расходы на электроэнергию. Для этого необходимо научиться эффективно предсказывать температуру стали на разных этапах 
производства.

### Оглавление.
1. Загрузка файлов и предподготовка данных.
- 1.1. Загрузка файлов.
- 1.2. Предподготовка данных
2. Исследовательский анализ данных.
- 2.1. Температура.
- 2.2. Продолжительность нагрева.
- 2.3. Активная мощность.
- 2.4. Реактивная мощность.
3. Создание дополнительных признаков и объединение таблиц.
- 3.1. Температуры.
- 3.2. Нагревы.
- 3.3. Легирующие материалы.
- 3.4. Объединение таблиц.
4. Градиентный бустинг.
5. Линейная регрессия.

### Сферы деятельности: производство, металлургия.
### Направления деятельности: data scientist, data analyst.
### Навыки и инструменты: Python, Pandas, Matplotlib, Scikit-learn, Statsmodels, Catboost, исследовательский анализ данных, визуализация данных, предобработка данных.
### Задачи проекта: определить температуру стали на разных этапах производства.

### Результат работы:
1. Целевым признаком была выбрана последняя температура замера каждой партии. Данные были подготовлены и очищены.
2. Были исследованы: температуры, нагревы и мощности. Признаки распределены нормально, но мощности и время нагрева коллерированны, поэтому была использована формула 
полной мощности для создания нового признака. Коллерированные признаки были удалены.
3. Также были созданы признаки: время между замерами температуры и первая температура.
4. Все признаки были объединены в один датафрейм, который был разбит на обучающую и тестовую выборки.
5. Были подобраны парметры на кросс-валидации для модели градиентного бустинга CatBoost и получен MAE на тестовой выборке равный 5,4.
6. Линейная регрессия была обучена на обучающей выборке и проверена на тестовой. MAE осталось меньше шести. Была выявлена линейная зависимость между двумя легирующеми
материалами.

### Статус проекта:
Завершен.
