# Nome do Ativo
* Start-laravel-docker MODELO  PHP COM LARAVEL

# Tecnologia
* PHP 7.4
* Composer
* Apache 2
* Docker



# clonando Repositório de codigo-fonte
git clone https://github.com/walissonssousa/Start-laravel-docker.git

# Instalação /Configuracão da aplicação

Para ambientes de desenvolvimento,  deverá obrigatoriamente utilizar o docker para disponibilizar a aplicação em desenvolvimento, para isso é necessário que se tenha o docker e o docker compose instalado e executar o seguinte comando no root da aplicação.

```
# Subindo o Backend
--1- docker-compose build
--2- docker-compose up -d

#listando os container após o build

--docker ps

depois de listado pegar o id do container laravelapp

rodar comando do artisan dentro da IDE 

-- docker exec -it "numero do id" bash

#instalar composer

--composer install

php artisan key:generate

#Configurando o Backend da aplicação

--cp .env.example .env

--php artisan key:generate




# Visualizando aplicação localhost
* API 
http://localhost:8080/




