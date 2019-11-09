# cloudera-quick-start-docker

Para rodar é necessário ter docker instalado na maquina

## Docker para Linux (Ubuntu)
https://docs.docker.com/install/linux/docker-ce/ubuntu/

## Docker para windows
https://docs.docker.com/docker-for-windows/

Arquivos que você queira mandar pro hadoop coloque na pasta **files**

* Rodar o comando **docker-compose up** para subir o container da cloudera com os bancos necessários

Ele irá subir a maquina e isso pode levar algum tempo, após, em outro terminal verificar se o container está *ligado* com o comando **docker ps** um container com o nome **quickstart.cloudera** deverá aparecer.

* Para acessar o Hue basta acessar o endereço no navegador **localhost:8888**

* Para conectar no bash do container e usar hadoop/sqoop e afins **docker exec -it quickstart.cloudera bash**


Dúvidas estou a disposição