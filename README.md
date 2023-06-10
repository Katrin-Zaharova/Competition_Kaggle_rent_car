# Competition_Kaggle_rent_car
Тетрадь с кодом и расчетами для соревнований на Kaggle</br>
Описание задачи</br>
Многие знают про маркетплейсы где продаются б/у вещи, где есть возможность недорого купить качественную и полезную вещь. Но всегда волнует вопрос - кто и как устанавливает цену, и какие его характеристики больше всего влияют на итоговую стоимость продажи?!</br> Вопрос становиться особо актуальным, если речь идет про дорогие товары, например про автомобили!</br>
Цель проекта - разработанная модель предсказания стоимости автомобиля на вторичном рынке.</br>

<b>Данные<b></br>
`train.csv` - информация о продажах (~440000) автомобилей с аукционов, которые будут использоваться в качестве обучающих данных.</br>
`test.csv` - информация о продажах (~110000) автомобилей с аукционов, которые будут использоваться в качестве тестовых данных. </br>
`sample_submission.csv` - файл предсказаний в правильном формате. </br>
`vin` - идентификатор каждого автомобиля в тестовом наборе. </br>
`sellingprice` - Целевой признак. Задача - предсказать значение 'sellingprice' для каждого автомобиля из этого датасета. </br>

<b>Описание полей данных<b></br>
'year' - год производства
'make' - производитель
'model' - модель
'trim' - модификация
'body' - тип кузова
'transmission' - тип КПП
'vin' - идентификатор (вин)
'state' - штат регистрации
'condition' - состояние по шкале (1-5)
'odometer' - пробег в милях
'color' - цвет кузова
'interior' - цвет интерьера
'seller' - продавец
'sellingprice' - стоимость продажи
'saledate' - дата продажи
