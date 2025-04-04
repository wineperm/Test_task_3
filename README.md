### **Задание: Docker-контейнеризация приложения**  
**Уровень:** Junior  
**Инструменты:** Docker, Docker Compose, Python, Nginx.  
**Описание:**  
Создайте Docker-образ для Python-приложения (Flask/Django), которое отображает "Hello, DevOps!". Настройте Nginx как обратный прокси для приложения. Используйте Docker Compose для одновременного запуска приложения и Nginx.  
**ТЗ:**  
- Написать Dockerfile для Python-приложения.  
- Настроить Nginx-контейнер с конфигом для проксирования запросов на порт Python-приложения.  
- Создать docker-compose.yml, связывающий оба контейнера.  
**Критерии:**  
- Приложение доступно на `localhost:80` через Nginx.  
- Логи приложения выводятся в stdout.

## PS Выполнено дополнительно помимо Nginx на Apache и HAproxy
