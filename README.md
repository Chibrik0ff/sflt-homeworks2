# Домашнее задание к занятию 2 «Кластеризация и балансировка нагрузки» - `Чибриков Станислав`

### Задание 1

- Запустите два simple python сервера на своей виртуальной машине на разных портах
- Установите и настройте HAProxy, воспользуйтесь материалами к лекции по [ссылке](2/)
- Настройте балансировку Round-robin на 4 уровне.
- На проверку направьте конфигурационный файл haproxy, скриншоты, где видно перенаправление запросов на разные серверы при обращении к HAProxy.

### *Ответ*

![Скриншот](https://github.com/Chibrik0ff/8-03-hw/blob/main/img/9f7a06c1-c270-47a3-8566-65193ad55ed6.jpg)

[Haproxy_1](https://github.com/Chibrik0ff/8-03-hw/blob/main/haproxy.cfg)

 ---

### Задание 2

- Запустите три simple python сервера на своей виртуальной машине на разных портах
- Настройте балансировку Weighted Round Robin на 7 уровне, чтобы первый сервер имел вес 2, второй - 3, а третий - 4
- HAproxy должен балансировать только тот http-трафик, который адресован домену example.local
- На проверку направьте конфигурационный файл haproxy, скриншоты, где видно перенаправление запросов на разные серверы при обращении к HAProxy c использованием домена example.local и без него.

### *Ответ*

![Скриншот](https://github.com/Chibrik0ff/8-03-hw/blob/main/img/1947ef0f-f9a6-4739-a296-2dc489ae256c.jpg)

[Haproxy_2](https://github.com/Chibrik0ff/8-03-hw/blob/main/haproxy2.cfg)

 ---