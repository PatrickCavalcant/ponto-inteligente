# ponto_inteligente

[![author](https://img.shields.io/badge/author-patrick-red.svg)](https://www.linkedin.com/in/patrick-cavalcante-moraes-a95635179/)
[![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](https://github.com/PatrickCavalcant)

O projeto aqui desenvolvido utiliza como padrão o Angular 12 integrado com uma API Restful criada com Spring Boot e Java.</br>
A integração consistui em consumir uma API Restful em Spring e Java, com cadastro de usuários, autenticação via token JWT (JSON Web Token) e CRUDs de cadastro, que incluem listagem de dados com paginação e ordenação.


<a href="https://github.com/PatrickCavalcant/ponto-inteligente/tree/main/ponto-inteligente-api"> <h3> Ponto Inteligente API </h3> </a>
API do sistema de ponto inteligente com Java e Spring Boot.
### Como executar a aplicação

```
./mvn spring-boot:run
API será executada em http://localhost:8080
```

<a href="https://github.com/PatrickCavalcant/ponto-inteligente/tree/main/ponto-inteligente-client"> <h3> Ponto Inteligente Cliente </h3> </a>
Código cliente Angular 12 do sistema de ponto inteligente.
### Como executar a aplicação
O código cliente depende da API RESTful, que deverá estar configurada e em execução como requisito.
Para executar o cliente (após a execução da API RESTful), execute os seguintes passos:
```
cd ponto-inteligente-client
npm install -g @angular/cli
npm install
npm start
```
Acesse a aplicação em [http://localhost:4200](http://localhost:4200)  

*Para sua execução certifique-se também de possuir o [NodeJS](http://nodejs.org).*  
*A instalação do @angular/cli acima pode necessitar ser executada como admin do sistema*  


<h4>Tela de Login</h4>
<img src="img/login.png" width="800" align="center" >
<h4>Interface de Admin</h4>
<img src="img/admin.png" width="800">
<h4>Interface do controle do Ponto Inteligente</h4>
<img src="img/controle.png" width="800">
<h4>Adicionar Ponto Inteligente</h4>
<img src="img/add.png" width="800">

<h4>O foi desenvolvido: </h4>
Criado aplicações com recursos avançados do Angular </br>
Consumir uma API RESTful criada em Spring Boot/Java </br>
Criar aplicações com o Angular Material </br>
Autenticação e autorização de acesso com tokens JWT (JSON Web Token)</br>
Trabalhar com rotas entre componentes</br>
Criar Guards para adicionar segurança e controle as rotas</br>
Criar formulários reativos</br>
Validação de dados</br>
Cria validadores personalizados para CPF e CNPJ</br>
Aplicar máscara a campos como data, CPF e CNPJ</br>
Utilizar componentes como Date Picker e janelas modais</br>
Criar tabelas de listagem de dados com paginação e ordenação</br>
Criar tabelas de listagem de dados Lazy loading</br>
Criar formulários com recursos avançados.</br>
