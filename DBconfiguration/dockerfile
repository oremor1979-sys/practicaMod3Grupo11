#La imagen a utilizar 
FROM postgres:latest 
# Instrucciones de ejecución automatica al crear el columen de datos por primera vez 
#Copiar un script SQL al directorio de inicialización de PostgreSQL 
COPY init.sql /docker-entrypoint-initdb.d/01_init.sql 
COPY save_data.sql /docker-entrypoint-initdb.d/02_save_data.sql
