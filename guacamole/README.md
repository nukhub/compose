```
wget https://raw.githubusercontent.com/nukhub/compose/main/guacamole/guacamole.yml
```
```
docker compose -f guacamole.yml up -d
```
```
docker run --rm guacamole/guacamole /opt/guacamole/bin/initdb.sh --mysql > initdb.sql
```
```
docker exec -i guacamole_db mysql --user guacamole --password=change-me guacamole_db < initdb.sql
```
