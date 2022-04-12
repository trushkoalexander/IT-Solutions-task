# IT-Solutions-task


- Dockerfile находится в dir /my_flask_app
- health-check в Dockerfile
- docker-compose up -d (для запуска Python(Flask), Prometheus, Gragana, NodeExporter)
- Метрики Prometheus (Error rate, RPS по http_status, Total RPS, CPU usage, Average memory usage)
- Grafana dashboard с визуализацией метрик лежит: IT-Solutions-task/grafana/dashboards/*

- Файл для запуска image приложения в Kuber лежит: IT-Solutions-task/k8s/deploy-app-simple.yaml
