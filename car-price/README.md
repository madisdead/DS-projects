# Построение модели определения стоимости автомобиля

Сервис по продаже автомобилей с пробегом  разрабатывает приложение для привлечения новых клиентов. В нём можно быстро узнать рыночную стоимость своего автомобиля. На основе исторических данных построена модель для определения стоимости автомобиля.

Навыки и инструменты: python, pandas, lightgbm

## Вывод

Получили, что обучение лучшей модели LightGBM заняло 5.47 s, а RandomForestRegressor 37.7 s. Предсказание для обоих моделей заняло меньше секунды, а результаты подсчета RMSE оказали следующие: для LightGBM 1721.537990222616, для RandomForestRegressor 1944.6699489501673.
