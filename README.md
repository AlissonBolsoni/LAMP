# LAMP com Docker Compose

Esse é uma stack com

* PHP
* Apache
* MySQL
* phpMyAdmin
* Laravel
* Nodejs
* Npm
* VueJs

## Instalação

Clone this repository on your local computer and checkout the appropriate branch e.g. 7.1.x. Run the `docker-compose up -d`.

```shell
git clone https://github.com/AlissonBolsoni/LAMP.git
cd LAMP/
git fetch --all
git checkout 7.1.x
docker-compose up -d
```

Sua stack LAMP está pronta

## Uso
docker exec atfb-server [COMANDO]  

docker exec atfb-server -it [COMANDO] //caso o comando precise de interação  

docker exec atfb-server npm run serve --prefix ./[NOME_DO_PROJETO]
