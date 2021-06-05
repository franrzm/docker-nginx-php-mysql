ARG mysql_version

FROM mysql:${mysql_version}

COPY ./sql-scripts/ /docker-entrypoint-initdb.d/
