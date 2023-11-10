### Предсказание дефолта сделки

Задача - построить алгоритм, определяющий вероятность дефолта того или иного заказа на исторических данных. Бейзлайн точности на тестовых данных 70%. Проверка проходила на стороне чекера, итоговая модель выдала точность 71%.

### Описание данных
Файл с тренировочными данными с таргетной переменной лежит в train.csv. Файл с тестовыми данными без таргетной переменной лежит в test.csv

Ниже в табличном формате вы можете найти наименования фичей и таргетной колонки и их описания. Заметьте: гномы достаточно аккуратны в предоставлении конфиденциальной информации, поэтому некоторые признаки достаточно абстрактны и их точный смысл неизвестен.

Наименование колонки	Описание колонки
Deal_id	- Номер заказа
Deal_date	- Дата заказа
First_deal_date	- Дата первого заказа
Secret_dwarf_info_1	- Засекреченный признак №1
Secret_dwarf_info_2	- Засекреченный признак №2
Secret_dwarf_info_3	- Засекреченный признак №3
First_default_date - Первая дата дефолта гнома
Successful_deals_count - Сколько оплаченных заказов было сделано
Region - Регион таверны
Tavern - Тип таверны
Hashed_deal_detail_1 - Засекреченный признак по заказу №1
Hashed_deal_detail_2 - Засекреченный признак по заказу №2
Hashed_deal_detail_3 - Засекреченный признак по заказу №3
Hashed_deal_detail_4 - Засекреченный признак по заказу №4
Hashed_deal_detail_5 - Засекреченный признак по заказу №5
Hashed_deal_detail_6 - Засекреченный признак по заказу №6
Age - Возраст, сделавшего заказ
Gender - Пол, сделавшего заказ
Default - Дефолтнул ли по этой покупке? 1 - да, 0 - нет.
