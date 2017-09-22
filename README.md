# zabbix-docker
Simple Zabbix environment for testing purpose written in Docker compose

### It creates following containers: 
1. PostgreSQL database
2. Zabbix backend server
3. Zabbix fronted server ( with Apache httpd )

### How you can run it?
```docker-compose up -f docker-compose.yml```

### How you can reach services?
* Zabbix frontend: port **80**
  * Username: Admin
  * Password: zabbix
* PostgreSQL server: **5432**
* Zabbix server: **10051**
