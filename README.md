# Debian Wiki

Версия: Debian 12 (Bookworm)

* Автоматическая установка (Automating Linux Installations)
* Сборки
* Пакеты

## Пакеты

* screen

* ### stress

***Установка***

```sh
sudo apt install stress
```

*Пример: загрузка 4 ядер на 60 секунд*

```sh
sudo stress --cpu 4 --timeout 60
```

*Пример: загрузка 2 ядер на 5 минут*

```sh
sudo stress -c 2 -t 5m
```

* ssh

* telnet

* htop

* mc

* i3wm
