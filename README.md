# Docker-Compose-Mysql-Alfresco
O projeto contém um arquivo docker-compose.yml que permite configurar e executar
 o Alfresco com o MySQL como banco de dados, juntamente com o Camunda.

 Por padrão o camunda vem em Docker, entõa para melhores práticas elaboramos ele em 
docker compose para que ele subisse junto ao Alfresco.
O Alfresco por default vem em postgres, alteramos para mysql e utlizamos o pacote
do mariadb.

Este docker compose foi elaborado em base a um projeto real.


