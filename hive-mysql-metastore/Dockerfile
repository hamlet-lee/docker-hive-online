from mysql:5.5.62
MAINTAINER "Hamlet Lee <lisining@gmail.com>"
RUN apt-get update && apt-get install -y vim
COPY hive-schema-2.3.0.mysql.sql /docker-entrypoint-initdb.d/hive-schema-2.3.0.mysql.sql
COPY hive-txn-schema-2.3.0.mysql.sql /hive-txn-schema-2.3.0.mysql.sql
