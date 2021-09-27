FROM mysql:5.7.25

ENV MYSQL_ROOT_PASSWORD="vprodbpass"
ENV MYSQL_DATABASE="accounts"

ADD db_backup.sql docker-entry-point-initdb.d/db_backup.sql