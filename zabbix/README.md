```
wget https://raw.githubusercontent.com/nukhub/compose/main/zabbix/zabbix.yml
wget https://raw.githubusercontent.com/nukhub/compose/main/zabbix/.env
```
```
http://IP:8080 (Admin/zabbix)
```
```
monitoring du zabbix server :
pour la config de l'agent sur le server (debian)
=> mettre l'IP du container dans /etc/zabbix/zabbix_agentd.conf, option Server=
=> mettre l'IP de la machine dans l'host (via interface web zabbix)
```
```
monitoring du reste :
pour les autres agents, mettre l'IP de la machine (pas celle du container)
```
