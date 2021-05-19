nano /etc/services (seznam všech portů služeb)

Apache:
/etc/apache2/ports.conf
+ sites enabled
---------------------------------------------------------------------------------------------------
Nginx
+ pro každou stránku zvlášť

---------------------------------------------------------------------------------------------------
PGSQL:
https://stackoverflow.com/questions/187438/change-pgsql-port
nano /etc/postgresql/11/main/postgresql.conf

---------------------------------------------------------------------------------------------------
MariaDB:
nano /etc/mysql/mariadb.conf.d/50-server.cnf