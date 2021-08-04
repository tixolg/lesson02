# lesson02

1. Dockerfile
- app1 apache, port 81
- app2 nginx, port 82

В каждый контейнер пробрасывается файл с конфигурацией по изменению порта.

2. Double tagging подтверждён скриншотом.
docker run -d -p 5000:5000 --name registry registry:2

3. docker-compose.yaml  

