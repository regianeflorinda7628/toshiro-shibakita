# Projeto Microsserviços com Docker

![Docker](https://img.shields.io/badge/Docker-Container-blue)
![PHP](https://img.shields.io/badge/PHP-Backend-purple)
![Nginx](https://img.shields.io/badge/Nginx-WebServer-green)
![Linux](https://img.shields.io/badge/Linux-Ubuntu-orange)

---

## Descrição do Projeto

Docker: Utilização prática no cenário de Microsserviços  
Instrutor: Denilson Bonatti - Digital Innovation One

Neste projeto é apresentada uma aplicação prática utilizando Docker no cenário de microsserviços. O objetivo é demonstrar como containers podem ser utilizados para facilitar o desenvolvimento e a execução de aplicações de forma isolada e escalável.

Pré-requisitos: conhecimentos básicos em Linux, Docker e AWS.

---

## Melhorias realizadas

- Execução da aplicação utilizando Docker
- Testes realizados em Ubuntu Server
- Execução do ambiente utilizando VirtualBox
- Atualização da documentação do projeto

---

## Como executar o projeto

1. Clonar o repositório

git clone https://github.com/regianeflorinda/toshiro-shibakita.git

2. Acessar a pasta do projeto

cd nome-do-repo

3. Construir a imagem Docker

sudo docker build -t site-docker .

4. Executar o container

sudo docker run -d -p 80:80 site-docker

5. Acessar no navegador

http://localhost

---

## Tecnologias utilizadas

- Docker
- Nginx
- PHP
- MySQL
- Linux (Ubuntu)

---

## Estrutura do Projeto

- Dockerfile → configuração da imagem Docker
- nginx.conf → configuração do servidor Nginx
- index.php → aplicação PHP
- banco.sql → script do banco de dados
- README.md → documentação do projeto

---

## Autora

Regiane Florinda  
Bootcamp DIO - Containers
