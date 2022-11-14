# Projeto DBInclui

# **DB Inclui**

Web app que dissemina a cultura de inclusão dentro da DBServer, com foco na cultura surda. O web app é destinado para todas as pessoas que desejam aprender **LIBRAS** e enteder um pouco mais sobre inclusão de PCD`s na sociedade. O web app aproveita o guia de acessibilidade e a apostila de Libras como fonte de informação de inclusão, assim como utiliza a **API Libras** para as funcionalidades específicas.

## Especificações

- Disponibilizado na Playstore
- Web APP com login de pessoa dbservante, que forneça dicas de inclusão com textos traduzidos em **Libras** e que ensine **Libras**;
- Gamification: Funcionalidades de gamificação que estimulam as pessoas da DB a permanecer aprendendo sobre inclusão e lbiras;
- Seja um facilitador para cultura de inclusão da DB;

## Problemas que serão resolvidos

- Propor uma alternativa tecnológica que estimula a autonomia no aprendizado de **inclusão**;
- Propor uma alternativa tecnológica que estimula a autonomia no aprendizado de **Libras**;
- Propor uma alternativa tecnológica para facilitar a comunicação entre pessoas ouvintes e Pessoas Surdas, para além de um texto estático de apostila;
- Propor uma alternativa tecnológica que estimule as pessoas a manter a prática de **Libras**, para além dos workshops e treinamentos;
- Propor uma alternativa tecnológica que facilite estimule as pessoas ouvintes a se comunicarem com as pessoas surdas, usando **Libras**;

## Usuários

- Pessoas que não tem conhecimento sobre **inclusão**;
- Pessoas que não tem conhecimento de **Libras**;
- Pessoas que desejam saber mais sobre inclusão e **Libras**;
- Pessoas da **DBServer**;

<br>

---

# Tecnologias

## Frontend

A Lib/Framework principal utilizada será ReactJS.

|       Nome      |                           Documentação                          |               Links dos pacotes               |
|:---------------:|:---------------------------------------------------------------:|:---------------------------------------------:|
| Typescript      | https://www.typescriptlang.org/docs/                            | https://www.npmjs.com/package/typescript      |
| React           | https://reactjs.org/docs/getting-started.html                   | https://www.npmjs.com/package/react           |
| React Bootstrap | https://react-bootstrap.github.io/getting-started/introduction  | https://www.npmjs.com/package/react-bootstrap |
| Axios           | https://axios-http.com/docs/intro                               | https://www.npmjs.com/package/axios           |
| Jest            | https://jestjs.io/docs/getting-started                          | https://www.npmjs.com/package/jest            |

## Backend

Utilizaremos Node.js com Typescript para o backend da aplicação.

|        Nome       	|                  Documentação                  	|                  Links dos pacotes                |
|:-----------------:	|:----------------------------------------------:	|:-----------------------------------------------:	|
| Node.js           	| https://nodejs.org/dist/latest-v16.x/docs/api/ 	| https://nodejs.org/en/download/                 	|
| Typescript        	| https://www.typescriptlang.org/docs/           	| https://www.npmjs.com/package/typescript        	|
| Mongoose          	| https://mongoosejs.com/docs/                   	| https://www.npmjs.com/package/mongoose          	|
| Axios             	| https://axios-http.com/docs/intro              	| https://www.npmjs.com/package/axios             	|
| Express           	| http://expressjs.com/en/4x/api.html            	| https://www.npmjs.com/package/express           	|
| Express Validator 	| https://express-validator.github.io/docs/      	| https://www.npmjs.com/package/express-validator 	|
| JWT               	| https://jwt.io/introduction                    	| https://www.npmjs.com/package/jsonwebtoken      	|

---

## Versionamento

### Clone o repositório

```
$ git clone https://github.com/dbinclui-org/dbinclui-frontend.git
```

### Iniciar o uso do Git Flow no projeto
```
$ git flow init
```

### Certifique-se de que a branch para "production releases" é a main
```
Which branch should be used for bringing forth production releases?
   - main
Branch name for production releases: [main] 
```

### Certifique-se de que a branch para "next release" é a develop
```
Branch name for "next release" development: [develop] 
```

### Aperte "ENTER" em cada input para usar as nomenclaturas padrões das features
```
How to name your supporting branch prefixes?
Feature branches? [feature/] 
Release branches? [release/] 
Hotfix branches? [hotfix/] 
Support branches? [support/] 
Version tag prefix? []
```

### Crie a branch baseada no número do seu card no Trello
```
$ git flow feature start DBI-61 <-- número do card do Trello
```

### Adicione e faça o commit das mudanças da branch
```
$ git add -A
$ git commit -m "Update README"
```

### Publique as modificações realizadas
```
$ git push --set-upstream origin feature/DBI-61
```

### Para realizar o *pull request* é necessário mudar o base repository para o repositório que possui o "dbinclui-org"
<img src="https://i.imgur.com/2D3kkjl.png"/>

### Confirme se a *develop* está marcada na *base* e se a sua *feature* está no *compare*, após isso já é possível clicar no botão para criar o *pull request*
<img src="https://i.imgur.com/kRLdwkc.png"/>

### Mude o título do *pull request* para o nome da feature + o título do card do Trello, como mostrado abaixo, após isso já é possível clicar no botão para criar o *pull request*
<img src="https://i.imgur.com/AZywbED.png"/>

### Após as mudanças serem aprovadas por duas pessoas e serem passadas no teste, será possível realizar o *merge request*
<img src="https://i.imgur.com/V76w9Bh.png"/>

## Qualidade

O Projeto deverá conter uma boa cobertura testes para manter a qualiade de software.

- Testes Unitários
- Testes E2E

## Banco de Dados

Banco de dados disponibilizado será o Mongodb.

## Segurança

O Site precisará implementar o protocolo **HTTPS**.

## Infraestrutura/Devops

Serviço de hospedagem e monitoramento (https://devcenter.heroku.com/articles/monitoring-apps) será o Heroku.

<!--
# Entendendo o Produto
## O produto é
- Um guia do museu personalizado
- Um facilitador para melhora a experiência do usuário
- Acesso/inclusivo
- Sistema Web Responsivo
- Interativo
## Não é
- Um guia estático
- Não abriga o usuário fazer uma rota única
- Aplicativo
- Um mapa do museu
## Faz
- Cria rota personalizada
- Melhora a experiência do usuário no museu
- Sugere rotas para usuário
- Descrição das atrações
- Guia de forma iterativa
- Propõe uma visita auto guiada
## Não faz
- Disponibiliza só roteiro que o ADMIN cadastrou
- Utiliza Geo Localização
- Identifica usuários
- Classifica rotas
- Gera QRCode -->
