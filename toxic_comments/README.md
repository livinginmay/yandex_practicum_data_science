# Выявление токсичных комментариев

## Описание
Задача классификации. В проекте рассмотрена работа с текстом с помощью TF-IDF и BERT. Также при реализации решается проблема дисбаланса классов с помощью техники downsampling. Подготовка признаков TF-IDF включена в пайплайн для кросс-валидации.

## Данные
В наличии были следующие данные о комментариях:
* Текст комментария
* Признак, является ли комментарий токсичным
 
## Задача
Интернет-магазин запускает возможность редактирования описания товаров пользователями – т.е. клиенты смогут вносить свои правки и комментировать изменения других. Необходимо построить модель для для того, чтобы автоматически находить токсичные комментарии и отправлять их на модерацию. Метрика качества – F1, требуется добиться ее значения на тестовой выборке не меньше 0.75.

## Статус
Завершен

## Результат
Лучшая модель - логистическая регрессия для признаков, подготовленных с помощью BERT. Она дает на тестовой выборке F1-меру, равную 0.899.

При этом предобработка перед обучением (подготовка признаков для BERT и очистка текста с лемматизацией для TF_IDF) занимает соизмеримое время - в пределах 10 минут для выборки после downsampling, обучение моделей с кросс-валидацией в случае BERT заметно дольше (для случайного леса - 16 секунд против 104), а качество на кросс-валидации отличается на сотые.

## Используемые библиотеки
*Pandas, BERT, NLTK, TF-IDF, spaCy, Scikit-learn*
