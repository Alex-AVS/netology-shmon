# 04. Система сбора логов Elastic Stack

### 1. Запуск
Создаём ELK-стек с использованием конфигурации из задания, изменив только настройки памяти -Xms2G -Xmx2G java для elasticsearch.
Иначе всё печально. 
При достаточном количестве свободной памяти работает:

![tf](img/04-docker-up.png)

Интерфейс Kibana:

![tf](img/04-kibana-init.png)

### 2. Работа с Kibana

Создаём DataView:

![tf](img/04-kibana-create-dataview.png)

Обзор:

![tf](img/04-kibana-dataview-overview.png)

Отфильтровали события от нашего тестового приложения:

![tf](img/04-kibana-dataview-someapp.png)

