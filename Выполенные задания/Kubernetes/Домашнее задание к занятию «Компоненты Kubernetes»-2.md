Для данного проекта  кнужен ластер из 3 master node  2 ядра CPU и 4 ГБ ОЗУ каждая и  3 worker nods с ресурсами 18,25Гб ОЗУ и 14,2 ядер на каждую
 
##  Ресурсы на worker
 База данных:

3 копии базы данных, каждая потребляет 4 ГБ ОЗУ и 1 ядро.
Всего: 3 * (4 ГБ + 1 ядро) = 12 ГБ ОЗУ и 3 ядра.
Система кеширования:

3 копии кеша, каждая потребляет 4 ГБ ОЗУ и 1 ядро.
Всего: 3 * (4 ГБ + 1 ядро) = 12 ГБ ОЗУ и 3 ядра.
Фронтенд:

5 копий фронтенда, каждая потребляет не более 50 МБ ОЗУ и 0.2 ядра.
Всего: 5 * (50 МБ + 0.2 ядра) = 250 МБ ОЗУ и 1 ядро.
Бекенд:

10 копий бекенда, каждая потребляет 600 МБ ОЗУ и 1 ядро.
Всего: 10 * (600 МБ + 1 ядро) = 6 ГБ ОЗУ и 10 ядер.
Общая нагрузка на worker node:

Сумма всех ресурсов компонентов:
12 ГБ ОЗУ + 3 ядра (база данных) + 12 ГБ ОЗУ + 3 ядра (кеш) + 250 МБ ОЗУ + 1 ядро (фронтенд) + 6 ГБ ОЗУ + 10 ядер (бекенд).
Всего: примерно 30.25 ГБ ОЗУ и 17 ядер.
