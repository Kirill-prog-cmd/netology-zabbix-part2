# ZABBIX_CONFIG2
## Задание 1
Создайте свой шаблон, в котором будут элементы данных, мониторящие загрузку CPU и RAM хоста.

# Процесс выполнения
1. Выполняя ДЗ сверяйтесь с процессом отражённым в записи лекции.
2. В веб-интерфейсе Zabbix Servera в разделе Templates создайте новый шаблон
3. Создайте Item который будет собирать информацию об загрузке CPU в процентах
4. Создайте Item который будет собирать информацию об загрузке RAM в процентах
Требования к результату
 Прикрепите в файл README.md скриншот страницы шаблона с названием «Задание 1»

## Ответ 
1. Создаем новый шаблон
 ![alt text](https://github.com/Agooll007/Avetisov-8-04-hw/blob/main/img/Zadacha1.png)
 ![alt text](https://github.com/Agooll007/Avetisov-8-04-hw/blob/main/img/Macros.png)
 ![alt text](https://github.com/Agooll007/Avetisov-8-04-hw/blob/main/img/Template_zadanie1.png)
 Создаем item
 ![alt text](https://github.com/Agooll007/Avetisov-8-04-hw/blob/main/img/RAM%20ITEM.png)
 ![alt text](https://github.com/Agooll007/Avetisov-8-04-hw/blob/main/img/CPU%20ITEM.png)
 
## Задание 2
Добавьте в Zabbix два хоста и задайте им имена <фамилия и инициалы-1> и <фамилия и инициалы-2>. Например: ivanovii-1 и ivanovii-2.

Процесс выполнения
Выполняя ДЗ сверяйтесь с процессом отражённым в записи лекции.
Установите Zabbix Agent на 2 виртмашины, одной из них может быть ваш Zabbix Server
Добавьте Zabbix Server в список разрешенных серверов ваших Zabbix Agentов
Добавьте Zabbix Agentов в раздел Configuration > Hosts вашего Zabbix Servera
Прикрепите за каждым хостом шаблон Linux by Zabbix Agent
Проверьте что в разделе Latest Data начали появляться данные с добавленных агентов
Требования к результату
 Результат данного задания сдавайте вместе с заданием 3

## Задание 3
Привяжите созданный шаблон к двум хостам. Также привяжите к обоим хостам шаблон Linux by Zabbix Agent.

Процесс выполнения
Выполняя ДЗ сверяйтесь с процессом отражённым в записи лекции.
Зайдите в настройки каждого хоста и в разделе Templates прикрепите к этому хосту ваш шаблон
Так же к каждому хосту привяжите шаблон Linux by Zabbix Agent
Проверьте что в раздел Latest Data начали поступать необходимые данные из вашего шаблона
Требования к результату
 Прикрепите в файл README.md скриншот страницы хостов, где будут видны привязки шаблонов с названиями «Задание 2-3». Хосты должны иметь зелёный статус подключения
![alt text](https://github.com/Agooll007/Avetisov-8-04-hw/blob/main/img/Zadanie1_hosts.png)
![alt text](https://github.com/Agooll007/Avetisov-8-04-hw/blob/main/img/Latest%20Data.png)
![alt text](https://github.com/Agooll007/Avetisov-8-04-hw/blob/main/img/Monitoring.png)

## Задание 4
Создайте свой кастомный дашборд.
Процесс выполнения
Выполняя ДЗ сверяйтесь с процессом отражённым в записи лекции.
В разделе Dashboards создайте новый дашборд
Разместите на нём несколько графиков на ваше усмотрение.
Требования к результату
 Прикрепите в файл README.md скриншот дашборда с названием «Задание 4»
![alt text](https://github.com/Agooll007/Avetisov-8-04-hw/blob/main/img/Zadanie4.png)
