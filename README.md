# lesson24

***Домашнее задание***

в Office1 в тестовой подсети появляется сервера с доп интерфесами и адресами

в internal сети testLAN

testClient1 - 10.10.10.254 </br>
testClient2 - 10.10.10.254</br>
testServer1- 10.10.10.1</br>
testServer2- 10.10.10.1</br>

развести вланами

testClient1 <-> testServer1

testClient2 <-> testServer2

между centralRouter и inetRouter

"пробросить" 2 линка (общая inernal сеть) и объединить их в бонд

проверить работу c отключением интерфейсов

Vagrant файлом разворачиваю ВМ, ansible  настроивает сеть и bond

проверка работы 

![image](https://github.com/movik242/lesson24/assets/143793993/ceb9d95a-d383-421f-8647-55f749786a52)

![image](https://github.com/movik242/lesson24/assets/143793993/7f235de4-a12f-49b6-8050-ada3b57ef49d)



