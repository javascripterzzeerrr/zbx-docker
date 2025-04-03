# zbx-docker

Для выполнения установки zabbix с помощью docker-compose, необходимо:
1) Создать файл .env и указать там необходимые переменные окрудения - PATH_VOLUME_POSTGRES, POSTGRES_PASSWORD, ZBX_SERVER_HOST, ZBX_SERVER
2) docker compose -f zbx-docker-compose.yaml up