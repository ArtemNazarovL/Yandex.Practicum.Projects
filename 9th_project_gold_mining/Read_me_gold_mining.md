# Description of the project
It is necessary to prepare a prototype of a machine learning model for a company that develops business solutions for industrial enterprises.

The model being developed should predict the recovery factor of gold from gold-bearing ore, based on data on the grade of the ore and the process of its refining.

This model optimizes production to avoid opening a loss-making enterprise.

### Fields of activity: Industry.
### Line of business: Machine learning, analyst (universal).
### Skills and tools: Python, Pandas, Matplotlib, Numpy, Scikit-learn, exploratory data analysis.
### Project objectives: to predict the concentration of gold in the ore.

### Contents:
- Step 0. Description of the project.
- Step 1. Data preparation.\
Clause 1.1. Examining files.\
Clause 1.2. Checking the correctness of the calculations of enrichment after flotation.\
Clause 1.3. Features not available in the test sample.\
Clause 1.4. Data preparation.
- Step 2. Data analysis.
Clause 2.1. Let's see how the concentration of metals (Au, Ag, Pb) changes at different stages of purification.\
Clause 2.2. Let us compare the size distributions of raw material granules on the training and test samples.\
Clause 2.3. We investigate the total concentration of all substances at different stages: in raw materials, in rough and final concentrates.
- Step 3. Model\
Clause 3.1. sMAPE function.\ 
Clause 3.2. Training and validation of models.

### Result of work:
- At the first stage, the data were loaded, studied and prepared: the gaps in the regressors were filled in with the means, and the rows with gaps in the target variables were removed.
- In the second step, we analyzed the data. It was concluded that with the passage of the stages of processing in the concentrate, the gold content increases. We checked the similarity of the distribution of granule values ​​in the test and training samples - the samples are similar. We found and removed observations where the total concentration of metals in the raw material was too low, suggesting that initially "poor" ore would not be accepted for production and it makes no sense to predict the recovery of such raw materials.
- In the third step, we tested different models: linear regression, random forest, and gradient boosting. The regression was found to be the best fit to the available data. In addition, such a model is easy to interpret. We also received predictions for the test sample.
### Project status:
Completed.

# Описание проекта
Необходтимо подготовить прототип модели машинного обучения для компании, которая разрабатывает бизнес решения для промышленных предприятий.

Разрабатываемая модель должна предсказать коэффициент восстановления золота из золотосодержащей руды, на основе данных о содержании руды и процессе ее очистки.

Эта модель оптимизирует производство для избежания открытия убыточного предприятия.

### Сферы деятельности: Промышленость.
### Направление деятельности: Машинное обучение, аналитик (универсал).
### Навыки и инструменты: Python, Pandas, Matplotlib, Numpy, Scikit-learn, исследовательский анализ данных.
### Задачи проекта: спрогнозировать концентрацию золота в руде.

### Оглавление:
- Шаг 0. Описание проекта.
- Шаг 1. Подготовка данных.\
Пункт 1.1. Изучение файлов.\
Пункт 1.2. Проверка правильности расчетов обогощения после флотации.\
Пункт 1.3. Признаки недоступные в тестовой выборке.\
Пункт 1.4. Предподготовка данных.
- Шаг 2. Анализ данных.
Пункт 2.1. Посмотрим, как меняется концентрация металлов (Au, Ag, Pb) на различных этапах очистки.\
Пункт 2.2. Сравним распределения размеров гранул сырья на обучающей и тестовой выборках.\
Пункт 2.3. Исследуем суммарную концентрацию всех веществ на разных стадиях: в сырье, в черновом и финальном концентратах.
- Шаг 3. Модель\
Пункт 3.1. Функция sMAPE.\
Пункт 3.2. Обучение и проверка моделей.

### Результат работы:
- На первом этапе были загружены, изучены и подготовлены данные: пропуски в регрессорах были заполненны средними, а строки с пропусками в целевых переменных были удалены.
- На втором шаге, мы проанализировали данные. Вывели, что с прохождением этапов обрабоки в концентрате растет содержание золото. Проверили похожесть распределния значений гранул в тестовой и обучающей выборке - выборки похожи. Нашли и удалил наблюдения, где суммарныая концентрация металлов в сырье была слишком мала, препдпологая, что изначально "бедную" руду не примут на производсвто и пронозировать восстановление такого сырья не имеет смысла.
- На третем этапе мы проверили различные модели: линейную регрессию, случайный лес, и градиентный бустинг. Регрессия оказалась наиболее подходящей к имеющимся данным. Кроме того, такую модель легко интерпретировать. Так же мы получили предсказания для тестовой выборки.
### Статус проекта:
Завершен.
