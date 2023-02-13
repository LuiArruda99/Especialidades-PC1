# Especialidades---PC1
 
### :rocket: Tecnologias Usadas

O projeto foi feito com as seguintes tecnologias:

- [NodeJS](https://nodejs.org/en/)
- [ReactJS](https://pt-br.reactjs.org/)
- [ExpressJS](https://expressjs.com/pt-br/)
- [JWT](https://jwt.io/)
- [Yup](https://github.com/jquense/yup)
- [Styled-Components](https://styled-components.com/)
{...}

## :hammer: Deploy da Aplicação
{...}


## Executando o Projeto
#### Clonando o projeto
```sh
$ baixe o .zip do projeto e abra a pasta no VSCode
```
$ cd Especialidades - PC1
```
#### Iniciando a API
```sh
$ cd api
```
# Criando a imagem Docker do banco de dados:
# Dentro do projeto, já existe uma arquivo docker-compose.yml que possui o
# PostgreSQL como banco de dados, basta ter o Docker instalado em sua máquina.
$ docker-compose up -d # Iniciará em background e não irá bloquear o shell

# Rodando as migrations para o banco de dados e iniciando o projeto
$ yarn && yarn typeorm migration:run && yarn dev:server
```



#### Iniciando o Frontend
```sh
$ cd web
$ yarn && yarn start
```


<p align="center" style="margin-top: 20px; border-top: 1px solid #eee; padding-top: 20px;">Feito com :purple_heart: by <strong>Luiz Claudio e Antonio Carlos</strong> </p>