# Determining the age of buyers from photographs.
A supermarket is developing a computer vision system to process customer photos. Cameras are installed next to the cash registers. Thus, the company will be able to:
- Analyze purchases and offer products that may be of interest to buyers of this age group;
- Control the conscientiousness of cashiers when selling alcohol.
It is necessary to develop a model that will determine the approximate age of a person from a photograph. We have a dataset with photos of people and their ages.

### Fields of activity: business, offline.
### Fields of activity: machine learning, CV.
### Skills and tools: Python, Keras.
### Tasks of the project: determination of age from a photograph.

### Result of work:
We got the required result of the metric - MAE equal to 7.27. This means that our model is on average wrong for exactly this number of years. To complete the task was
the ResNet50 architecture is applied, which uses 50 layers in the neural network, some of which do not follow each other. The quality of the model can be improved by simply limiting
number of epochs 16th. In this case we will get MAE - 6.26.

### Project status:
Completed.

# Определение возраста покупателей по фотографиям.
Супермаркет разрабатывает систему компьютерного зрения для обработки фотографий покупателей. Рядом с кассами установлены камеры. Таким образом компания сможет:
- Анализировать покупки и предлагать товары, которые могут заинтересовать покупателей этой возрастной группы;
- Контролировать добросовестность кассиров при продаже алкоголя.
Необходимо разработать модель, которая определит приблизительный возраст человека по фотографии . У нас есть набор данных с фотографиями людей и их возрастом.

### Сферы деятельности: бизнес, оффлайн.
### Направления деятельности: машинное обучение, CV.
### Навыки и инструменты: Python, Keras.
### Задачи проекта: определение возраста по фотографии.

### Результат работы:
Мы получили требуемый результат метрики - MAE равный 7,27. Это значит наша моедль в среднем ошибается именно на такое количество лет. Для выполнения задания была 
применена архитектура ResNet50, которая использует 50 слоев в нейросети, некоторые из которых идут не друг за другом. Качество модели можно улчшить, просто ограничив 
количество эпох 16-ю. В этом случае мы получим MAE - 6.26.

### Статус проекта:
Завершен.

