# Configuring-DHCPv6
## 1 Произведем базовую настройку маршрутизаторов R1 R2 и создаим топологию 

![](https://github.com/iGORnetwork/Configuring-DHCPv6/blob/main/image/Screenshot_1.png)
![](https://github.com/iGORnetwork/Configuring-DHCPv6/blob/main/image/Screenshot_2.png)
![](https://github.com/iGORnetwork/Configuring-DHCPv6/blob/main/image/Screenshot_3.png)

# 2 Убеждаемся, что маршрутизация работает с помощью пинга адреса E0/1 R2 из R1

![](https://github.com/iGORnetwork/Configuring-DHCPv6/blob/main/image/Screenshot_4.png)

# 3 Проверим назначения адреса SLAAC от R1 R2

![](https://github.com/iGORnetwork/Configuring-DHCPv6/blob/main/image/Screenshot_5.png)

# 4 Настроем R1 для предоставления DHCPv6 без отслеживания  состояния для PC-A.

![](https://github.com/iGORnetwork/Configuring-DHCPv6/blob/main/image/Screenshot_6.png)
![](https://github.com/iGORnetwork/Configuring-DHCPv6/blob/main/image/Screenshot_7.png)

# 5 Настроим DHCPv6 сервер с сохранением состояния на R1

![](https://github.com/iGORnetwork/Configuring-DHCPv6/blob/main/image/Screenshot_8.png)

# Настроем R2 в качестве агента DHCP-ретрансляции для локальной сети на E0/1.
