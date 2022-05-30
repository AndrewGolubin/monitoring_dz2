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
3. Внутри Infra создан дашборд "infra stats", отражающий сводную информацию по инфраструктуре на основе экспортеров с возможностью выбора рассматриваемого хоста.
4. Внутри app создан дашборд "Site aviability", отражающий сводную информацию о CMS.
5. При помощи Grafana создан алерт о недоступности CMS

Скрины - ниже

Контейнеры на Virt2

![Slide_1](https://user-images.githubusercontent.com/23739863/170943417-39f96bf4-f5d3-4182-a2f4-fcd2264012ac.png)

Папки infra и app

![Slide_2](https://user-images.githubusercontent.com/23739863/170944225-a564968b-d068-46e1-a4ea-efdc24973b31.png)

Дашборд infra stats

![Slide_3](https://user-images.githubusercontent.com/23739863/170944528-d91e9815-c796-46f2-9855-ef1556cc68e6.png)

![Slide_4](https://user-images.githubusercontent.com/23739863/170944724-e76b8acf-b750-4dd6-91ef-fad8af179687.png)

Дашборд Site aviability

![Slide_5](https://user-images.githubusercontent.com/23739863/170944914-3c6440f8-bcf0-4097-aeb4-0c009fc06058.png)

Алерт из Grafana с отражением в Telegram

![Slide_6](https://user-images.githubusercontent.com/23739863/170945442-a0a7d456-92ed-4f0f-b5c7-898f276b9c35.png)

![Slide_7](https://user-images.githubusercontent.com/23739863/170945604-4ea955ce-814c-4ba7-9dc1-51bc60d34913.png)

![Slide_8](https://user-images.githubusercontent.com/23739863/170945787-abbaf81f-7c4d-4c74-8c2e-15921eda5f34.png)

