# Домашнее задание к занятию «Кластеризация и балансировка нагрузки» - `Костюк Денис`

### Задание 1
#### •	Запустите два simple python сервера на своей виртуальной машине на разных портах
![Скрин1](https://github.com/denniskostyuk/balans/blob/main/task_11.png)
![Скрин2](https://github.com/denniskostyuk/balans/blob/main/task_12.png)
#### •	Установите и настройте HAProxy, воспользуйтесь материалами к лекции по ссылке
#### •	Настройте балансировку Round-robin на 4 уровне.
#### •	На проверку направьте конфигурационный файл haproxy, скриншоты, где видно перенаправление запросов на разные серверы при обращении к HAProxy.
![Скрин3](https://github.com/denniskostyuk/balans/blob/main/task_13.png)
![Скрин4](https://github.com/denniskostyuk/balans/blob/main/task_14.png)
![Скрин5](https://github.com/denniskostyuk/balans/blob/main/task_15.png)
   



### Задание 2
#### •	Запустите три simple python сервера на своей виртуальной машине на разных портах
![Скрин6](https://github.com/denniskostyuk/balans/blob/main/task_21.png)
![Скрин7](https://github.com/denniskostyuk/balans/blob/main/task_22.png)
![Скрин8](https://github.com/denniskostyuk/balans/blob/main/task_23.png)
#### •	Настройте балансировку Weighted Round Robin на 7 уровне, чтобы первый сервер имел вес 2, второй - 3, а третий - 4
#### •	HAproxy должен балансировать только тот http-трафик, который адресован домену example.local
#### •	На проверку направьте конфигурационный файл haproxy, скриншоты, где видно перенаправление запросов на разные серверы при обращении к HAProxy c использованием домена example.local и без него.

