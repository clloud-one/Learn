# NAT

Технология, позволяющая нескольким устройствам в локальной сети использовать один публичный IP-адрес для выхода в интернет



**Работа NAT:**

1. Устройство в локальной сети отправляет запрос в интернет (веб-сайт)

2. Роутер (Устройство выполняющее роль Маршутизатора):
   
   - Локальный IP (192.168.1.10) → Публичный IP (95.165.32.1).
   
   - Порт источника (например, 1234) → Уникальный внешний порт (54321).

3. Сервер в интернете видит запрос от 95.165.32.1 и отправляет ответ обратно.

4. Маршутизатор сопоставляет ответ с исходным устройством (192.168.1.10) и передаёт данные.


