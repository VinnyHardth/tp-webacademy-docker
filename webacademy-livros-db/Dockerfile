FROM mysql:latest

# Copia todos os arquivos do diretório atual para o diretório de trabalho no contêiner
COPY ./script.sql /docker-entrypoint-initdb.d/

# Expõe a porta 3306 para permitir conexões externas
EXPOSE 3306

# Inicia o servidor MySQL
CMD ["mysqld"]
