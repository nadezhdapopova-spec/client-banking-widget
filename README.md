# Проект "Client-banking-widget"

## Описание:

"Client-banking-widget" - это учебный проект по Python. 

Проект содержит код для разработки виджета банковских операций клиента. 
Виджет создается для отображения нескольких последних успешных банковских операций клиента.


## Установка:

1. Клонируйте репозиторий проекта:
````
git clone https://github.com/nadezhdapopova-spec/client-banking-widget.git
````
2. Установите зависимости внутри каталога проекта:
````
poetry install
````

## Использование:

В проекте содержатся функции:

* **mask_account_card: маскировка номера банковской карты или номера банковского счета**

#### Пример работы функции для карты:

Visa Platinum 7000792289606361  # входной аргумент

Visa Platinum 7000 79** **** 6361  # выход функции

#### Пример работы функции для счета:

Счет 73654108430135874305  # входной аргумент

Счет **4305  # выход функции

* **get_date: преобразование даты в формат "ДД.ММ.ГГГГ"**
  
#### Пример работы функции:

"2024-03-11T02:26:18.671407"  # входной аргумент

"11.03.2024"  # выход функции

* **filter_by_state: фильтрация данных**

* **sort_by_date: сортировка данных по дате**


## Лицензия:

Проект распространяется под [лицензией MIT](https://github.com/nadezhdapopova-spec/client-banking-widget/blob/main/LICENSE)
