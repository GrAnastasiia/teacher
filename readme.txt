Цель проекта: разработать решение, которое позволит персонализировать предложения постоянным клиентам, чтобы увеличить их покупательскую активность.

Этапы проекта:

Открыть файлы с данными.
Провести предобработку данных.
Провести исследовательский анализ данных.
Объединить таблицы.
Провести корреляционный анализ признаков данных.
Обучить несколько моделей и выбрать лучшую.
Оценить важность признаков.
Выполнить сегментацию покупателей.

В работе использовались модели DecisionTreeClassifier, KNeighborsClassifier, LogisticRegression, SVC

Целью нашего проекта было разработать решение, которое позволит персонализировать предложения постоянным клиентам, чтобы увеличить их покупательскую активность. В ходе исследования мы провели предобработку и исследовательский анализ данных, а также разработали и выявили лучшую модель машинного обучения. В результате исследования удалось выяснить:

Предпочтения клиентов по рассылке показали, что большинство из них соглашаются на получение дополнительных предложений о товарах, что может свидетельствовать о заинтересованности в новых акциях и предложениях. Тем более, что такие клиенты сохраняют свой прежний уровень активности больше, чем те, кто отказался.

В отношении предпочтений по сервису, большинство клиентов предпочитают использовать стандартный уровень сервиса, что может быть индикатором их довольства текущими услугами.

Среднее время регистрации на сайте составляет около 600 дней, причем есть как пользователи с более длительным, так и с более коротким временем с момента регистрации.

Анализ популярности категорий товаров показал, что самая популярная категория покупок среди клиентов - "Товары для детей", в то время как категория "Кухонная посуда" наименее популярна.

Средний просмотр категорий за визит оказывает существенное влияние на уровень покупательской активности.

Акционные покупки и наличие неоплаченных продуктов оказывают влияние на снижение уровня покупательской активности.

Выбранная нами группа клиентов с высокой вероятностью снижения покупательской активности и наиболее высокой прибыльностью, в своем большинстве имеет стандартную подписку и согласие на получение информации о предложениях. Это может помочь в поддержании уровня покупательской активности клиентов, а рекомендации товаров из категорий "Товары для детей" и "Домашний текстиль" с учетом частоты маркетинговых активностей за последние 6 месяцев могут быть эффективными для удержания клиентов.