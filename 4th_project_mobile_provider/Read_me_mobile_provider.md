# Determination of a prospective tariff for a telecom company.
The federal mobile operator offers its customers two tariff plans: "Smart" and "Ultra". The commercial department wants to understand which tariff brings in more money,
to adjust your advertising budget.
You have to make a preliminary analysis of tariffs on a small sample of customers. At your disposal are the data of 500 Megaline users: who are they, where are they from, how
the tariff is used, how many calls and messages each sent in 2018. It is necessary to analyze the behavior of customers and draw a conclusion - which tariff is better.

### Fields of activity: Internet services, ad platforms.
### Activities: marketing analyst, fraud analyst, data analyst.
### Skills and tools: Python, Pandas, Matplotlib, exploratory data analysis, data visualization, data preprocessing.
### Project objectives: to determine the market value of real estate objects and typical parameters of apartments based on Yandex.Realty data.

Description of tariffs:
> Tariff "Smart"
> Monthly fee: 550 rubles
> Included 500 minutes of calls, 50 messages and 15 GB of data
> Cost of services above the tariff package:
> minute of conversation: 3 rubles
> message: 3 rubles
> 1 GB of Internet traffic: 200 rubles


Tariff "Ultra":
> Monthly fee: 1950 rubles
> Included 3000 minutes of calls, 1000 messages and 30 GB of data
> Cost of services above the tariff package:
> minute of conversation: 1 ruble
> message: 1 ruble
> 1 GB of Internet traffic: 150 rubles

## Study plan:

- Step 1. About the project.
- Step 2. Loading the libraries and exploring the data.
- Step 3. Data preprocessing.
- Step 4. Grouping and combining data.
- Step 5. Calculation of additional indicators.
- Step 6. Analysis of customer behavior.
> Item A. Number of minutes used.\
> Item B. Volume of consumed traffic.\
> Item C. Number of messages used.\
> Item D. Examining overpayments.\
> Item E. Income structure.\
> Item F. Revenue dynamics.\
> Point G. Disconnected subscribers.
- Step 7. Statistical study.
> Item A. Equality of average revenues of tariffs.\
> Item B. Equality of average revenues from tariffs in Moscow and the regions.
- Step 8. Conclusion.

### Result of work:
The following has been clarified:
- The Smart tariff does not provide a sufficient volume of packages. Half of the subscribers are forced to overpay.
- The Ultra tariff provides a package of minutes more than anyone from this selection could spend. Internet is overused by 26% of users. Note that there is a lot of traffic and messages in this tariff, 30 GB and 1000 pieces, respectively. Ultra subscribers are active users of modern forms of communication - Internet and text messages.
- The proceeds from the Smart tariff for 50% consists of overpayments. Most overpayments for the Internet - 1 million rubles. and minutes - 290 tr.
- Revenue from the Ultra tariff mainly consists of ~ 90% subscription fee. Overpayments occur due to traffic overruns (100 tr.).
- The number of subscribers on the Smart tariff grew faster than on Ultra, and revenue grew along with it.
- Perhaps subscribers leave the Smart tariff due to constant overpayments. 22.5% paid even more than they would have paid on Ultra.
- In general, Smart's revenue for the sample is more than 2.6 million rubles. against 2 million rubles at Ultra.
- The expenses of subscribers for communication and Internet on the Smart tariff are well described by the normal distribution, messages are not distributed normally. While all of the above is not described by the normal distribution of Ultra. This indicates a significant heterogeneity in the behavior of subscribers of this tariff.

Conclusions based on statistical analysis:
- The hypothesis about the equality of the average revenue of the Smart and Ultra tariffs was rejected and, based on the superiority of the average revenue of the Ultra tariff, it was concluded that the average revenue from the Ultra tariff is higher than from the Smart tariff.
- The hypothesis about the equality of revenue from the use of both tariffs in Moscow and other regions was not rejected. That is, with a high probability, the average revenue in Moscow is approximately equal to the average revenue in other regions.

### Project status:
Completed.

# Определение перспективного тарифа для телеком-компании.
Федеральный оператор сотовой связи предлагает клиентам два тарифных плана: «Смарт» и «Ультра». Коммерческий департамент хочет понять, какой тариф приносит больше денег,
чтобы скоректировать рекламный бюджет.
Вам предстоит сделать предварительный анализ тарифов на небольшой выборке клиентов. В вашем распоряжении данные 500 пользователей «Мегалайна»: кто они, откуда, каким 
тарифом пользуются, сколько звонков и сообщений каждый отправил за 2018 год. Нужно проанализировать поведение клиентов и сделать вывод — какой тариф лучше.

### Сферы деятельности: интернет-сервисы, площадки объявлений.
### Направления деятельности: маркетинг аналитик, fraud-аналитик, data analyst.
### Навыки и инструменты: Python, Pandas, Matplotlib, исследовательский анализ данных, визуализация данных, предобработка данных.
### Задачи проекта: определить рыночную стоимость объектов недвижимости и типичные параметры квартир на основе данных Яндекс.Недвижимость.

Описание тарифов:
> Тариф «Смарт»
> Ежемесячная плата: 550 рублей
> Включено 500 минут разговора, 50 сообщений и 15 Гб интернет-трафика
> Стоимость услуг сверх тарифного пакета:
> минута разговора: 3 рубля
> сообщение: 3 рубля
> 1 Гб интернет-трафика: 200 рублей


Тариф «Ультра»:
> Ежемесячная плата: 1950 рублей
> Включено 3000 минут разговора, 1000 сообщений и 30 Гб интернет-трафика
> Стоимость услуг сверх тарифного пакета:
> минута разговора: 1 рубль
> сообщение: 1 рубль
> 1 Гб интернет-трафика: 150 рублей

## План исселования:

- Шаг 1. О проекте.
- Шаг 2. Загрузка библиотек и изучение данных.
- Шаг 3. Предобработка данных.
- Шаг 4. Группировка и объединение данных.
- Шаг 5. Рассчет дополнительных показателей.
- Шаг 6. Анализ поведения клиентов.
> Пункт A. Количество используемых минут.\
> Пункт B. Объем потребляемого трафика.\
> Пункт C. Количество использованных сообщений.\
> Пункт D. Изучение переплаты.\
> Пункт E. Структура доходов.\
> Пункт F. Динамика выручки.\
> Пункт G. Отключившиеся абоненты.
- Шаг 7. Статистическое исследование.
> Пункт A. Равнество средних доходов тарифов.\
> Пункт B. Равенство средних доходов от тарифов в Москве и регионах.
- Шаг 8. Вывод.

### Результат работы:
Установлено следующее:
- Тариф Smart не предоставляет достаточный объем пакетов. Половина абонентов вынуждены переплачивать.
- Тариф Ultra предсотавляет пакет минут больший, чем кто либо из данной выборки смог израсходывать. Интрнет перерасходуют 26% пользоватедей. Отметим, что трафика и сообщений в этом тарифе много, 30 гб и 1000шт, соответсвенно. Абоненты Ultra - активные пользователи современных форм коммуникации - интернет и текстовые сообщения.
- Выручка от тарифа Smart на 50% состоит из переплат. Больше всего переплат за интрнет - 1 млн.р. и минуты - 290 т.р.
- Выручка от тарифа Ultra главным образом состоит из абонентсокй платы ~ 90%. Переплаты происходят за счет перерасхода трафика (100 т.р.).
- Количетсво абонентов на тарифе Smart росло быстрее чем на Ultra и вместе с этим росла и выручка.
- Возможно абонеты уходят с тарифа Smart из-за постонняых переплат. 22,5% платили даже больше, чем платили бы на Ultra.
- В целом выручка по выборке больше у Smart 2,6 млн.р. против 2 млн.р. у Ultra.
- Траты абонентов на связь и интрнет на тарифе Smart хорошо описываются нормальным распределением, сообщения не распределны нормально. В то время как всё выше перечисленное не описывается нормальным распределением у Ultra. Это говорит о значительной неоднордности поведения абонентов этого тарифа.

Выводы на основе статистического анализа:
- Отвергнута гипотеза о равенстве средней выручки тарифов Smart и Ultra и на основе превосходства средней выручки тарифа Ultra был сделан вывод, что средняя выручка от тарифа Ultra выше, чем от тарифа Smart.
- Не была отвергнута гипотеза о равенстве выручки от использования обоих тарифов в Москве и других регионах. То есть, с высокой вероятностью, средняя выручка в Москве примерно равна средней выручке в других регионах.

### Статус проекта:
Завершен.

