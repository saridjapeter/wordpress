# wordpress+grafana+prometheus
## Install
```bash
git clone https://github.com/saridjapeter/wordpress.git
docker-compose up -d
```
Блог доступен по адресу http://blog.example.com/
Предварительно делаем DNS запись или прописываем в файле hosts.

Prometheus
http://blog.example.com:9090

Ggrafana
http://blog.example.com:3000/
Login: admin
Password: admin
Есть 3 готовых dashboards.
