# Лабораторная работа 4

Сделал: `Ахмедов Бахадыр`
## Часть 1

<img width="500" src="./images/image_1.png"/>


Создаем `Docker image` (образ)

`RUN apt-get update && apt-get install -y libaa-bin`

Обновляем пакетный менеджер и устанавливаем ПО под названием `aafire`.



## Часть 2


<img width="500" src="./images/image_2.png"/>

Затем запускаем команду сборки образа с тегом `aafire`

`docker build -t aafire .`

<img width="500" src="./images/image_3.png"/>

Запускаем контейнер на основе созданного образа

<img width="500" src="./images/image_4.png"/>

<img width="500" src="./images/image_5.png"/>

проверяем запущенный контейнер

## Часть 3
<img width="500" src="./images/image_6.png"/>

 Устонавливаем утилиту `ping` 


<img width="500" src="./images/image_7.png"/>

Затем запускаем команду запуска образа 
`sudo docker build -t aafire .`



<img width="500" src="./images/image_8.png"/>

 запускаем два контейнера с `aafire`
 при помощи комнады 
 sudo docker 
 `run -it --name container1 aafire"` и `run -it --name container2 aafire"`


<img width="500" src="./images/image_9.png"/>

Проверяем

## Часть 4


<img width="500" src="./images/image_10.png"/>

Создадим сеть

<img width="500" src="./images/image_11.png"/>

Подключим контейнеры к сети 


<img width="500" src="./images/image_12.png"/>

Просмотрим настройки созданной сети.


<img width="500" src="./images/image_13.png"/>

 Протестируем соединение между контейнерами.
