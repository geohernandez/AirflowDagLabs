FROM library/postgres:14
COPY data.csv /
RUN chown postgres:postgres data.csv
COPY init.sql /docker-entrypoint-initdb.d/
