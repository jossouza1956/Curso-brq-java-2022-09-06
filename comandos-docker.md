#Principais comendos
##como iniciar um container (que ainda nao existe)?
...
docker run NOME-DA IMAGEM
...
docker run docker/getting-started
...
## para listar os container que estão em execução
...
docker ps
...
# Se eu quiser parar a execuçõ de um container:

```
    docker stop NOMEDOCONTAINER
    Ex: docker stop cool_varahamihira
```
# Se eu quiser iniciar um container que já existe:

```
    docker start NOMEDOCONTAINER
    Ex: docker start cool_varahamihira
    ```
    docker rm NOMEDOCONTAINER
    Ex: docker rm cool_varahamihira
```
  ..
       docker run  --name NOMEDOCONTAINERDESEJO -p PORTA-HOSPEDEIRO:PORTA-CONTAINER  NOMEDAIMAGEM
    Ex: docker run --name hello-world -p 80:80  docker/getting-started
    ...
    #redirecionar a maquina hospedeira para um container doker
    ...
    docker stop hello-world
    ...
    ...
    docker stop hello-world
    ...
    docker run --name hello-world -p 80:80  docker/getting-started
    ...
    

