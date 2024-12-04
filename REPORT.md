# Лабораторная работа 2

Сделал: `Ахмедов Бахадыр`
## Часть 1

<img width="500" src="./images/image_1.png"/>


Создаем `Docker image` (образ)

`RUN apt-get update && apt-get install -y libaa-bin`

Обновляем пакетный менеджер и устанавливаем ПО под названием `aafire`.



## Часть 2

Затем запускаем команду сборки образа с тегом `aafire`

`docker build -t aafire .`

<img width="500" src="./images/image_2.png"/>

Запускаем контейнер на основе созданного образа
<img width="500" src="./images/image_3.png"/>

<img width="500" src="./images/image_4.png"/>

проверяем запущенный контейнер
<img width="500" src="./images/image_5.png"/>

## Часть 3
 Устонавливаем утилиту `ping` 
<img width="500" src="./images/image_6.png"/>

Затем запускаем команду сборки образа 

`sudo docker build -t aafire .`

Проверяем:

<img width="500" src="./images/image_7.png"/>


 запускаем два контейнера с `aafire`
 при помощи комнады 
 sudo docker 
 `run -it --name container1 aafire"` и `run -it --name container2 aafire"`

<img width="500" src="./images/image_8.png"/>

Проверяем:

<img width="500" src="./images/image_9.png"/>

## Часть 4

Создадим сеть

<img width="500" src="./images/image_10.png"/>

Подключим контейнеры к сети 
<img width="500" src="./images/image_11.png"/>

Просмотрим настройки созданной сети.
<img width="500" src="./images/image_12.png"/>

 Протестируем соединение между контейнерами.
<img width="500" src="./images/image_13.png"/>
