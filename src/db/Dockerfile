# This dockerfile is currently not used
FROM postgres:16

COPY ./postgresql.conf postgres.conf
COPY ./pg_hba.conf /etc/postgresql/9.5/main/pg_hba.conf
COPY ./pgdg.list /etc/apt/sources/list.d/pgdg.list

CMD ["postgres"]
