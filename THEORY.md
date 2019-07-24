### Central network

###### 192.168.0.0/28 - directors

Network address 192.168.0.0; broadcast 192.168.0.15; hosts - 14

###### 192.168.0.32/28 - office hardware

Network address 192.168.0.32; broadcast 192.168.0.47; hosts - 14

###### 192.168.0.64/26 - wifi

Network address 192.168.0.64; broadcast 192.168.0.127; hosts - 62

В этой сети избыточное деление, есть простаивающие диапазоны. Логичнее было бы поделить сети на 192.168.0.0/27 и 192.168.0.32/27, получаем большее количество узлов в сети и нет простаивающих диапазонов.

### Office1 network

###### 192.168.2.0/26 - dev

Network address 192.168.2.0; broadcast 192.168.0.63; hosts - 62

###### 192.168.2.64/26 - test servers

Network address 192.168.2.64; broadcast 192.168.2.127; hosts - 62

###### 192.168.2.128/26 - managers

Network address 192.168.2.128; broadcast 192.168.2.191; hosts - 62

###### 192.168.2.192/26 - office hardware

Network address 192.168.2.192; broadcast 192.168.2.255; hosts - 62

#### Office2 network

###### 192.168.1.0/25 - dev

Network address 192.168.1.0; broadcast 192.168.1.127; hosts - 126

###### 192.168.1.128/26 - test servers

Network address 192.168.1.128; broadcast 192.168.1.191; hosts - 62

###### 192.168.1.192/26 - office hardware

Network address 192.168.1.192; broadcast 192.168.1.255; hosts - 62
