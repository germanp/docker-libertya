FROM postgres:9.5

COPY ./create_db.sh /docker-entrypoint-initdb.d/10-create_db.sh
COPY dump_libertya_1907ar_pyme_postgres9.5.sql.gz /docker-entrypoint-initdb.d/20-dump.sql.gz