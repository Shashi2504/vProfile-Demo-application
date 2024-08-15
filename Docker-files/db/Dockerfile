FROM mysql:8.0.33
LABEL "Project"="Database Setup"
LABEL "Name= "Shashi"

ENV MYSQL_ROOT_PASSWDRD = "sassy2912"
ENV MYSQL_DATABASE = "accounts"

ADD db_backup.sql /docker-entrypoint-initdb.d/db_backup.sql
