### Задание 1. Создать Pod с именем hello-world
- проверяем - pods отсутствуют - продолжаем

![alt text](1.png)

- запускаем pod-hello-world
- проверяем что pod работает
- пробрасываем порты
- и выводим содержимое через curl
  
![alt text](2.png)

### Задание 2. Создать Service и подключить его к Pod
- Создать Pod с именем netology-web.
- Создать Service с именем netology-svc и подключить к netology-web.
- Подключиться локально к Service с помощью kubectl port-forward и вывести значение (curl или в браузере).

проверяем

![alt text](3.png)

в наличии один pod

запускаем второй pod и создаем сервис, собираем информацию
![alt text](4.png)

запускаем проброс портов и выводим в curl

![alt text](5.png)