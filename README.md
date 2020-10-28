# Учебные проекты Яндекс.Практикум специальности "Аналитик данных"

В ходе обучения было выполненно 13, различных по теме и задачам, проектов на языке Python в среде Jupyther Notebook. Кликнув на название проекта - вы перейдете в его папку, где найдете описание и файл проекта.

| Название проекта | Задачи | Результат | Используемые библиотеки |
| :---------------------- | :---------------------- | :---------------------- | :---------------------- |
| [Исследование надёжности заёмщиков](borrowers_research_project) | На основе статистики о платёжеспособности клиентов исследовать влияет ли семейное положение и количество детей клиента на факт возврата кредита в срок | Человек с детьми, не замужем либо в гражданском браке, с низким или средним уровнем дохода, берущий кредит для операций с автомобилем или на образование - скорее всего будет иметь проблемы с возвратом этого кредита. | *Pandas* |
| [Продажа квартир в Санкт-Петербурге](real_estate_market_analysis) | На основе данных сервиса ~~название засекреченно~~ определена рыночная стоимость объектов недвижимости разного типа, типичные параметры квартир, в зависимости от удаленности от центра. Проведена предобработка данных. Добавлены новые данные. Построены гистограммы, боксплоты, диаграммы рассеивания.| *Pandas*, *Matplotlib*|
| [Определение выгодного тарифа для телеком компании](telecom_profitable_tariff_determenation) | Проведен предварительный анализ использования тарифов на выборке клиентов, проанализировано поведение клиентов при использовании услуг оператора и рекомендованы оптимальные наборы услуг для пользователей. Проведена предобработка данных, их анализ. Проверены гипотезы о различии выручки абонентов разных тарифов и различии выручки абонентов из Москвы и других регионов.| *Pandas*, *Matplotlib*, *NumPy*, *SciPy*|
| [Изучение закономерностей, определяющих успешность игр](game_market_success_analysis) | Выявлены параметры, определяющие успешность игры в разных регионах мира. На основании этого подготовлен отчет для магазина компьютерных игр для планирования рекламных кампаний. Проведена предобработка данных, анализ. Выбран актуальный период для анализа. Составлены портреты пользователей каждого региона. Проверены гипотезы: средние пользовательские рейтинги платформ Xbox One и PC одинаковые; средние пользовательские рейтинги жанров Action и Sports разные. При анализе использовал критерий Стьюдента для независимых выборок.| *Pandas*, *Matplotlib*, *NumPy*|
| [Исследование данных авиакомпании](airline_data_analysis) | Проведена выгрузка и подготовка предоставленных данных авиакомпании средствами SQL. Проверен анализ данных во время проведения различных фестивалей и в обычное время.| *SQL*, *Pandas*, *Matplotlib*|
| [Оптимизация маркетинговых затрат в сервисе по продаже билетов](marketing_costs_optimization) | Проведен анализ данных от ~~название засекреченно~~ с целью оптимизации маркетинговых затрат. Рассчитаны метрики LTV, CAC, Retention rate, DAU, WAU, MAU, ROMI| *Pandas*, *Matplotlib*, *Seaborn*, *NumPy*,*SciPy*|
| [Проверка гипотез по увеличению выручки в интернет-магазине — оценка результатов A/B теста](internet_market_hypotesis_check) | Проведена приоритизация гипотез по фреймворкам ICE и RICE. Затем провел анализ результатов A/B-теста, построил графики кумулятивной выручки, среднего чека, конверсии по группам, а затем посчитал статистическую значимость различий конверсий и средних чеков по сырым и очищенным данным. На основании анализа мной было принято решение о нецелесообразности дальнейшего проведения теста.| *Pandas*, *Matplotlib*, *SciPy*|
| [Исследования рынка общепита в Москве для принятия решения об открытии нового заведения](catering_market_analysis) | Мною был исследован вопрос - будет ли успешным и популярным на долгое время кафе, в котором гостей обслуживают роботы-официанты. По результатам анализа подготовлена презентация для инвесторов с рекомендациями. В построении графиков я использовали библиотеки seaborn и plotly. Также мне потребовалось получить район расположения кафе-конкурентов.| *Pandas*, *Seaborn*, *Plotly* |
| [Анализ пользовательского поведения в мобильном приложении](mobile_app_user_behavior_analysis) | В данном проекте мной были изучены принципы событийной аналитики. Я построил воронку продаж, исследовал путь пользователей до покупки. Проанализировал результаты A/B-теста введения новых шрифтов. Сравнил 2 контрольных группы между собой, убедился в правильном разделении трафика, а затем сравнил с тестовой группой. Выявлено, что новый шрифт значительно не повлияет на поведение пользователей.| *Pandas*, *Matplotlyb*, *Seaborn*, *Plotly* |
| [Создание дашборда по пользовательским событиям для агрегатора новостей](user_events_dashboard) | Была проведена коннекция к базе и выгрузка данных. По полученным данным был построен дашборд. По результатам была подготовлена презентация с полученными графиками| *SQLAlchemy*, *PostgreSQL*, *dash*, *Tableau* |
| [Прогнозирование вероятности оттока пользователей для фитнес-центров](user_churn_forecasting) | В данном проекте использовано машинное обучение. Спрогнозирована вероятность оттока (на уровне следующего месяца) для каждого клиента; сформированы типичные портреты пользователей: выделены наиболее яркие группы, охарактеризованы их основные свойства; проанализированы основные признаки, наиболее сильно влияющие на отток.| *Pandas*, *Scikit-learn*, *Matplotlib*, *Seaborn* |
| [Анализ вакансий ручных тестировщиков для QA–факультета](qa_vacancy_analysis) | В данном проекте было необходимо выбрать и проанализировать вакансии, на которые могут откликнуться и получить приглашение на интервью студенты QA-факультета. Был проведен исследовательский анализ данных, получены ответы на вопросы заказчика  | *Pandas*, *NumPy*, *Matplotlib*, *Seaborn* |
| [Выпускной проект. Формирование модели монетизации игрового приложения](game_app_monetization_diploma) | Выпускной проект состоял из трех заданий: написание SQL-запросов, анализ A/B теста и основной проект по формированию модели монетизации игрового приложения. По итогам проекта были созданы дашборд и презентация. | *Pandas*, *NumPy*, *SciPy*, *Math*, *Matplotlyb*, *Seaborn*, *Plotly* |
