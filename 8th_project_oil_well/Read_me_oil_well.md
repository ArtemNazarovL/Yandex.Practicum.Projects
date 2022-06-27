# Choice of location for the oil well

Our task is to choose a place for drilling a new oil well.

We have access to oil samples from three regions, each containing 10,000 deposits. For each field, the quality of oil and the volume of reserves are known. It is necessary to develop a machine learning model capable of identifying the region that will bring the greatest profit. You also need to analyze the expected profit and risks using Bootstrap.

Place selection procedure:

Deposits are searched for in the selected region, and for each of them the characteristic values ​​are determined.
Develop a model and estimate the amount of reserves.
Choose places with the highest parameter ratings. The number of deposits depends on the available budget and the cost of developing the deposit.
The profit is considered as the sum of the profits of the selected deposits.

#### Fields of activity: Mining companies.
#### Line of business: Machine learning, regression, business model development, financial analyst.
#### Skills and tools: Python, Pandas, Bootstrap.
#### Project objectives: to select a location for the development of an oil field.

### Contents:
- Step 0. Description of the project.
- Step 1. Loading and preparing data.
- Step 2: Train and validate the model.\
Item A. Training the model.\
Point B. Analysis of the model.
- Step 3. Preparation for profit calculation.
- Step 4. Calculation of profit and risks. \
Item A. Region 0.\
Item B. Region 1.\
Item C. Region 2.

### Result of work:
- A regression model was prepared to obtain target attribute predictions for three variables.
- Using the bootstrap model and technique, the average expected profit for each region was determined, as well as the confidence interval and the risk of loss.
- The risk of loss was below the threshold only in region 1 with an average expected profit of 498769860 rubles.

### Project status:
Completed.

# Выбор локации для скважины

Перед нами стоит задача - выбрать место для бурения новой нефтяной скважины.

Нам доступны пробы нефти из трёх регионов, каждый из которых содержит 10000 месторождений. По каждому месторождению известны качество нефти и объём запасов. Необходимо разработать модель машинного обучения сопосбную определить регион, который принесет наибольшую прибыль. Также нужно проанализировать ожидаемую прибыль и риски при помощи Bootstrap.

Порядок выбора места:

В выбранном регионе ищут месторождения и для каждого из них определяют значения признаков.
Разрабатывают модель и оценивают количество запасов.
Выбирают места с наивысшими оценками параметров. Количество месторождений зависит от доступного бюджета и стоимости разработки месторождения.
Считают прибыль, как сумму прибыли выбранным месторождений.

#### Сферы деятельности: Добывающие компании.
#### Направление деятельности: Машинное обучение, регрессия, разработка бизнес-модели, финансовый аналитик.
#### Навыки и инструменты: Python, Pandas, Bootstrap.
#### Задачи проекта: выбрать локацию для разработки нефтяного месторождения.

### Оглавление:
- Шаг 0. Описание проекта.
- Шаг 1. Загрузка и подготовка данных.
- Шаг 2. Обучение и проверка модели.\
Пункт A. Обучение модели.\
Пункт B. Анализ модели.
- Шаг 3. Подготовка к расчету прибыли.
- Шаг 4. Расчет прибыли и рисков. \
Пункт A. Регион 0.\
Пункт B. Регион 1.\
Пункт C. Регион 2.

### Результат работы:
- Была подготовлена модель регрессии для получения предсказаний целеовго признака по трем перменным.
- При при помощи модели и техники будстреп была определена средняя ожидаемая прибыль для каждого региона, а также доверительный интервал и риск получения убытка.
- Риск получения убытка оказался ниже порога только в регионе 1 со средней ожидаемой прибылью 498769860 рублей.

### Статус проекта:
Завершен.
