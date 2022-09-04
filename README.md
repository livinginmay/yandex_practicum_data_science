# Проекты курса "Data Science" в Яндекс.Практикуме
Здесь представлены проекты, которые были выполнены мной на курсе ["Data Science" в Яндекс.Практикуме](https://practicum.yandex.ru/data-scientist/) в 2022 году.
|№|Название проекта|Тема|Описание|Используемые библиотеки|
|-|-|-|-|-|
|1|[Предсказание температуры стали](https://github.com/livinginmay/yandex_practicum_data_science/tree/main/steel_temperature)|Выпускная работа|Задача регрессии. Построение модели для предсказания финальной температуры стали. В проекте рассмотрены **3 различных набора признаков** для обучения и **5 моделей** с подбором гиперпараметров на кросс-валидации. Выполнена **генерация признаков**, анализ их **важности**.|*Pandas, PandaSQL, Scikit-learn, LightGBM, XGBoost, Seaborn*|
|2|[Определение возраста покупателей](https://github.com/livinginmay/yandex_practicum_data_science/tree/main/customers_age)|Компьютерное зрение|Задача регрессии. Построение модели для определения возраста покупателей по фото. В проекте рассмотрена работа с изображениями с помощью предобученной **ResNet50**,а также построенными с нуля **LeNet** и **VGG**. Используется **динамическая загрузка данных**.|*Pandas, Keras, Seaborn*|
|3|[Выявление токсичных комментариев](https://github.com/livinginmay/yandex_practicum_data_science/tree/main/toxic_comments)|Машинное обучение для текстов|Задача классификации. Необходимо построить модель для для того, чтобы автоматически находить токсичные комментарии и отправлять их на модерацию. В проекте рассмотрена работа с текстом с помощью **TF-IDF** и **BERT**. Также при реализации решается проблема дисбаланса классов с помощью техники **downsampling**.  Подготовка признаков TF-IDF включена в **пайплайн** для кросс-валидации.|*Pandas, BERT, NLTK, TF-IDF, spaCy, Scikit-learn*|
|4|[Прогнозирование заказов такси](https://github.com/livinginmay/yandex_practicum_data_science/tree/main/taxi_orders)|Временные ряды|Задача регрессии. Построение модели для предсказания количества заказов такси в аэропортах по историческим данным. В проекте рассмотрена работа с **временным рядом** как на различных моделях **градиентного бустинга**, так и на более простых – **регрессия, дерево решений, случайный лес**.|*Pandas, Scikit-learn, Statsmodels, Catboost, LightGBM, XGBoost, Seaborn*|
|5|[Определение стоимости автомобилей](https://github.com/livinginmay/yandex_practicum_data_science/tree/main/car_prices)|Численные методы|Задача регрессии. Построение модели для быстрого определения стоимости автомобиля с пробегом по техническим характеристикам и комплектации. В проекте рассмотрены модели **градиентного бустинга** в сравнении с более простыми - по времени обучения, скорости и качеству предсказания. Также особое внимание уделено обработке **пропусков** и **выбросов**.|*Pandas, Scikit-learn, Catboost, LightGBM, Category-Encoders, Seaborn*|
|6|[Защита персональных данных клиентов](https://github.com/livinginmay/yandex_practicum_data_science/tree/main/personal_data)|Линейная алгебра|Задача регрессии. Разработка метода защиты персональных данных клиентов страховой компании. Корректность преобразования информации обоснована **теоретически**, подтверждена эмпирическим путем на модели **линейной регрессии**.|*Pandas, NumPy, Scikit-learn*|
|7|[Восстановление золота из руды](https://github.com/livinginmay/yandex_practicum_data_science/tree/main/gold_recovery)|Сборный проект|Задача регрессии. Разработка модели предсказания коэффициента восстановления золота из золотосодержащей руды. В проекте рассмотрены **3 модели** с подбором гиперпараметров на кросс-валидации. Используется **функция расчета значения метрики**. Подробный **EDA**.|*Pandas, Scikit-learn, Seaborn*|
|8|[Выбор локации для нефтяной скважины](https://github.com/livinginmay/yandex_practicum_data_science/tree/main/well_location)|Машинное обучение в бизнесе|Задача регрессии. Необходимо построить модель для определения региона, где добыча нефти принесет наибольшую прибыль. Для предсказания объемов запасов используется **линейная регрессия**, для оценки прибыли и рисков - техника **Bootstrap**.|*Pandas, Scikit-learn, Seaborn*|
