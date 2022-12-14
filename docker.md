## Comandos básicos úteis para utilizar com DOCKER

**Ver Containers**

`docker ps -a`
****
**Ver status dos containers**

`docker stats {IDCONTAINER ou não coloque nada para listar todos}`
****

**Build de um container utilizando Docker-compose**

`docker-compose up --build`
****
**Ver logs do container**

`docker logs -f {IDCONTAINER}`
****
**Acessar o container**

`docker exec -it {IDCONTAINER} /bin/sh` -> Para containers que utilizem o **shell**
****
**Ver imagens baixadas no docker**

`docker image ls`
****
**Apagar imagens não utilizadas**

`docker image prune -a`

_Entenda imagem não utilizada como imagem que não possui nenhum container vinculado_
