# sber_virtual_internship
https://v.preactum.ru/stazhirovki/sberbank-data-science/

## Информация о проекте

### Задача
Предсказание объема стабильных средств клиентов без сроков погашения, в данном конкретном случае это расчетные счета клиентов.

### С какой целью?
Умение точно прогнозировать объем и динамику стабильного остатка средств на расчетных счетах позволяет Банку зарабатывать на кредитовании, но при этом держать в приемлемых рамках риск того, что клиенты могут в любой момент потребовать эти средства назад – это называется "управление риском ликвидности". Для этого строится ML модель прогнозирования стабильного остатка средств на расчетных счетах клиентов, связанная с моделями прогноза рынков, макроэкономики и поведения клиентов.

### Внешние показатели, влияющие на расчетные счета клиентов:
- Стоимость акций Сбера (Источник: Investing.com, Ссылка: https://ru.investing.com/equities/sberbank_rts-historical-data)
- Стоимость золота в России в рублях на грамм (Источник: Центральный Банк РФ, Ссылка: https://cbr.ru/hd_base/metall/metall_base_new/)
- Ключевая ставка Банка России и инфляция (Источник: Центральный Банк РФ, Ссылка: https://cbr.ru/hd_base/infl/)
- Курс валюты, стоимость доллара в рублях (Источник: Центральный Банк РФ, Ссылка: https://cbr.ru/currency_base/dynamics/)

### Построение модели
Для предсказания стабильных средств была применена библиотека XGBoost и модель XGBRegressor

### Визуализация
- Matplotlib
- Seaborn
- Plotly

### Оценка предсказаний
- R_squared (для кросс валидации)
- Mean absolute error
- Mean squared error
- Root mean squared error

Важное примечание!
Архив с данными загружен на Яндекс.Диск: https://disk.yandex.ru/d/0PfezLyV6uTz-A

