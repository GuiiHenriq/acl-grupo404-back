# Projeto Faculdade: E-commerce :rocket:
Projeto desenvolvido na OPE da Faculdade Impacta, no curso de Análise e Desenvolvimento de Sistemas.
Criamos um e-commerce, onde existe o comércio livre entre Vendedor e Comprador. Semelhante a cases como **Mercado Livre** e **Enjoei**. 

## Observações 🤖

> Desenvolvido em [NodeJS](https://nodejs.org/en/)


## Rodar Back-end :computer:

> :grey_exclamation: **Necessário ter o Docker instalado** :grey_exclamation:

> 
  :one: Faça o clone do projeto:
> git clone https://github.com/GuiiHenriq/acl-grupo404-back

 :two: Dentro da pasta criada, crie um arquivo **.env** de configuração:

    ###### PARAMETERS TO PostgreSQL ###
    DB_HOST=db
    DB_NAME=grupo_404
    DB_USER=root
    DB_PASSWORD=root
    SECRET=RTwRic%jdSa5E7cgQ&rQ

Descrição de cada atributo:

    DB_HOST -> Recebe o host, no exemplo acima estou passando o container do docker("db") correspondente ao banco de dados.
    DB_NAME -> Nome do banco de dados que será criado automaticamente quando subir a instância do docker
    DB_USER -> Usuário do banco que será criado
    DB_PASSWORD -> Senha do banco para o usuário criado
    SECRET -> Hash

 :three: Rode o projeto no terminal:
> docker-compose up

> O projeto irá abrir na URL http://localhost:2000/

## Melhorias :thought_balloon:

> :one: Criar um chat interativo entre Vendedor e Comprador.

> :two: Criar sistema de checkout.

## Repositórios :mag_right:
> [Back-end](https://github.com/GuiiHenriq/acl-grupo404-back)

> [Front-end](https://github.com/GuiiHenriq/acl-grupo404-front)


## Disponível no Link :checkered_flag:
> :rocket: https://loja404.netlify.app/ :rocket:
