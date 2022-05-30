Что необходимо сделать:

1. На VM с установленным Prometheus установите Grafana последней версии доступной на момент выполнения дз
2. Создайте внутри Grafana папки с названиями infra и app
3. Внутри директории infra создайте дашборд который будет отображать сводную информацию по инфраструктуре (CPU, RAM, Network, etc.)
4. Внутри директории app создайте дашборд который будет отображать сводную информацию о CMS (доступность компонентов, время ответа, etc.)

5. Задание со звездочкой 1 - при помощи Grafana создайте alert о недоступности одного из компонентов CMS и инфраструктуры
6. Задание со звездочкой 2 - создайте DrillDown dashboard который будет отображать сводную информацию по инфраструктуре, но нажав на конкретный инстанс можно получить полную информацию

Отчет:

1. Все работы велись на инфраструктуре, созданной в  https://github.com/AndrewGolubin/monitoring_dz1.
2. На ВМ Virt2, в докере, установлена Grafana, внутри которой созданы папки infra и app.
3. Внутри Infra создан дашборд "insra stats", отражающий сводную информацию по инфраструктуре на основе экспортеров с возможностью выбора рассматриваемого хоста.
4. Внутри app создан дашборд "Site aviability", отражающий сводную информацию о CMS.
5. При помощи Grafana создан алерт о недоступности CMS

Скрины - ниже

