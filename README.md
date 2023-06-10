# Competition_Kaggle_rent_car
Тетрадь с кодом и расчетами для соревнований на Kaggle</br>
Описание задачи</br>
Многие знают про маркетплейсы где продаются б/у вещи, где есть возможность недорого купить качественную и полезную вещь. Но всегда волнует вопрос - кто и как устанавливает цену, и какие его характеристики больше всего влияют на итоговую стоимость продажи?!</br> Вопрос становиться особо актуальным, если речь идет про дорогие товары, например про автомобили!</br>
Цель проекта - разработанная модель предсказания стоимости автомобиля на вторичном рынке.</br>

<b>Данные</b></br>
`train.csv` - информация о продажах (~440000) автомобилей с аукционов, которые будут использоваться в качестве обучающих данных.</br>
`test.csv` - информация о продажах (~110000) автомобилей с аукционов, которые будут использоваться в качестве тестовых данных. </br>
`sample_submission.csv` - файл предсказаний в правильном формате. </br>
`vin` - идентификатор каждого автомобиля в тестовом наборе. </br>
`sellingprice` - Целевой признак. Задача - предсказать значение 'sellingprice' для каждого автомобиля из этого датасета. </br>

<b>Описание полей данных</b></br>
'year' - год производства</br>
'make' - производитель</br>
'model' - модель</br>
'trim' - модификация</br>
'body' - тип кузова</br>
'transmission' - тип КПП</br>
'vin' - идентификатор (вин)</br>
'state' - штат регистрации</br>
'condition' - состояние по шкале (1-5)</br>
'odometer' - пробег в милях</br>
'color' - цвет кузова</br>
'interior' - цвет интерьера</br>
'seller' - продавец</br>
'sellingprice' - стоимость продажи</br>
'saledate' - дата продажи</br>
  
<b>Метрика качества. </b></br>
Работа модели будет оцениваться по метрике MAPE (Mean Absolute Percentage Error)

<b>Формат файла с результатами</b></br>

vin                     	sellingprice
1g6dp567450124779          	4359.65
