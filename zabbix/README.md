```
wget https://raw.githubusercontent.com/nukhub/compose/main/zabbix/zabbix.yml
wget https://raw.githubusercontent.com/nukhub/compose/main/zabbix/.env
```
```
http://IP:8080 (Admin/zabbix)
```
```
monitoring du zabbix server : pour la config de l'agent sur le server (debian) => mettre l'IP du container dans /etc/zabbix/zabbix_agentd.conf, option Server=
monitoring du reste : pour les autres agents, mettre l'IP du server (debian) (pas celle du container)
```
