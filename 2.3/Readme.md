### Задание 1. Создать Deployment приложения и решить возникшую проблему с помощью ConfigMap. Добавить веб-страницу
- Создать Deployment приложения, состоящего из контейнеров nginx и - multitool.
- Решить возникшую проблему с помощью ConfigMap.
- Продемонстрировать, что pod стартовал и оба конейнера работают.
- Сделать простую веб-страницу и подключить её к Nginx с помощью ConfigMap. 
- Подключить Service и показать вывод curl или в браузере.

![alt text](1.png)

Манифест

- [deploy-nginx-multitool.yml](deploy-nginx-multitool.yml)
- [configmap.yml](configmap.yml)
- [service.yml](service.yml)

### Задание 2. Создать приложение с вашей веб-страницей, доступной по HTTPS
- Создать Deployment приложения, состоящего из Nginx.
- Создать собственную веб-страницу и подключить её как ConfigMap к приложению.
- Выпустить самоподписной сертификат SSL.
- 
![alt text](2.png)

- Создать Secret для использования сертификата.
- Создать Ingress и необходимый Service, подключить к нему SSL в вид.
- Продемонстировать доступ к приложению по HTTPS.

![alt text](3.png)

Манифест

- [deploy-nginx.yml](deploy-nginx.yml)
- [configmap-nginx.yml](configmap-nginx.yml)
- [service-nginx.yml](service-nginx.yml)
- [ingres-nginx.yml](ingres-nginx.yml)