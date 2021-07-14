# DS Sales Project
[![NPM](https://img.shields.io/npm/l/react)](https://github.com/devsuperior/sds1-wmazoni/blob/master/LICENSE) 

# Sobre

https://icarovendas.netlify.app/

<p>Projeto de dashboard de vendas feito em React, consultando uma API desenvolvida com Spring Boot. Durante o desenvolvimento, foi criada uma 
API com quatros endpoints:</p>

- GET /sellers: Retorna todos os vendedores cadastrados;
- GET /sales: Retorno pageado, contendo informações de todas as vendas realizadas;
- GET /sales/amount-by-seller: Retorna o nome de cada vendedor e o valor total de suas vendas;
- GET /sales/success-by-seller: Retorna o nome de cada vendedor, quantidade de visitas e de vendas efetivas.

## Mobile layout

<div float="left">
  <img src="https://user-images.githubusercontent.com/19571060/117524839-ca108400-af95-11eb-9e3d-9715138a124f.png" width="300">
  <img src="https://user-images.githubusercontent.com/19571060/117524845-d7c60980-af95-11eb-95ef-7085855797cb.png" width="300">
</div>

## Desktop layout
<div>
  <img src="https://user-images.githubusercontent.com/19571060/117524879-05ab4e00-af96-11eb-9af5-8897a015cce8.png">
</div>

# Technologies used
## Back end
- Java
- Spring Boot
- JPA / Hibernate
- Maven
## Front end
- HTML / CSS / JS / TypeScript
- ReactJS
- ReactRouterDom
- Apex Charts
- Axios
## Deploy
- Back end: Heroku
- Front end web: Netlify
- Database: Postgresql

# How to execute the project

## Back end
Requirements: Java 11

```bash
# clone the repository
git clone https://github.com/icarogga/Vendas-REACT-SPRING.git

# go to the backend directory
cd backend

# run the project
./mvnw spring-boot:run
```

## Front end web
Requirements: yarn

```bash
# go to the frontend directory, backend's sister directory
cd frontweb

# install the dependencies
yarn

# run the project
yarn start
```

# Author

Ícaro Coelho

https://www.linkedin.com/in/ícaro-coelho-3a5b60206/

