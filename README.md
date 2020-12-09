# wordpress+grafana+prometheus
## Install
```bash
git clone https://github.com/saridjapeter/wordpress.git
docker-compose up -d
```
Блог доступен по адресу http://blog.example.com/ <br>
Предварительно делаем DNS запись или прописываем в файле hosts.

***Prometheus***<br>
http://blog.example.com:9090 <br>
Login: admin<br>
Password: admin<br>

***Grafana***<br>
http://blog.example.com:3000/ <br>
Login: admin<br>
Password: admin<br>
Есть 3 готовых dashboards.
