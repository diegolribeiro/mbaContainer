# Projeto de Entrega da matéria de container e virtualização


### Objetivo
  -Esta aplicação disponibilizará um cluster (SWARM) de containers com 3 réplicas do frontend, 2 réplicas do microserviço e 1 do banco de dados
  
### Tecnologias
- Java
- Maven
- Spring boot
- Banco de dados Mysql
- Docker
- Swarm

### Como executar

- Para executar o sistema utilizar o docker e o arquivo docker-compose.yml contido neste projeto e os comandos abaixo:
  - docker network create -d overlay net
  - docker stack deploy -c docker-compose.yml microservico_replica
