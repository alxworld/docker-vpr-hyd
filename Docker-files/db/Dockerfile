FROM mysql:8.0.33
LABEL "Project"="Vprofile"
LABEL "Author"="Alex"
LABEL "Version"="1.0"

ENV MYSQL_ROOT_PASSWORD="rootpwd1"
ENV MYSQL_DATABASE="accounts"

ADD db_backup.sql /docker-entrypoint-initdb.d/db_backup.sql
