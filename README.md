<h1 align="center">
    <img alt="Be The Hero" src="frontend/src/assets/índice.svg" width="250px" />
</h1>

<h4 align="center"> 
	🚀 Semana OmniStack 11.0
</h4>

<p align="center">
  <a href="#computer-projeto">Projeto</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#rocket-tecnologias">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#information_source-como-usar">Como usar</a>&nbsp;&nbsp;&nbsp;
</p>

## :computer: Projeto
<strong>Be The Hero</strong> é um projeto da <strong>11º edição da Semana OmniStack</strong> que é ministrada pelo <strong>Diego Fernandes</strong> da <strong>Rocketseat</strong>.
O projeto é um sistema de ajuda para ONGs onde uma instituição posta uma caso/<i>incident</i> informando um valor necessário para resolução do problema. A partir daí os <i>Heroes</i> entram em ação contactando a ONG para ajudar coma uma doação financeira.

Na ideia original, a versão Web, feita em React, conta apenas com a parte administrativa para ONGs. Nela uma instituição se cadastra, faz login e cadastra um caso.

Já no aplicativo, desenvolvido em React Native, foi feito apenas a área dos <i>Heroes</i>. Estes visualizam uma lista com os casos de todas as ONGs, acessam os detalhes de um caso e entram em contato, por e-mail ou Whatsapp, diretamente pelo aplicativo.

<img src="frontend/src/assets/logon.PNG" alt="Página login">
<img src="frontend/src/assets/incidents.PNG" alt="Página incidentes">
<img src="frontend/src/assets/new-incident.PNG" alt="Página novo incidente">
<img src="frontend/src/assets/new-ong.PNG" alt="Página nova ong">

<div>
	<img src="mobile/assets/incidents.PNG" alt="Página incidentes" width="300px" align="center">
	<img src="mobile/assets/details.PNG" alt="Página detalhes" width="300px" align="center">
	<img src="mobile/assets/email.PNG" alt="Página email" width="300px" align="center">
</div>


## :rocket: Tecnologias
Este projeto foi desenvolvido com as seguintes tecnologias:

- [Node.js](https://nodejs.org/en/) 
- [React](https://reactjs.org)
- [React Native](https://facebook.github.io/react-native/)
- [Expo](https://expo.io/)

## :information_source: Como usar
Para clonar e rodar esta aplicação, você vai precisar [Git](https://git-scm.com), [Node.js][nodejs] + [Npm][npm] instalado em seu computador.

Na sua linha de comando:

### Instalar API
```bash
# Clonar este repositório
$ git clone https://github.com/grioos/omnistack11

# Vá para o repositório
$ cd omnistack11/backend

# Instalar denpendências
$ npm install

# Rodar Migrates
$ npm knex migrate:latest 

# Rodar as Seeds
$ npm seed

# Rodas a API
$ npm start
```
---

Feito com :black_heart: by [Gabriel Rios](https://www.linkedin.com/in/grioos/)

[nodejs]: https://nodejs.org/
[npm]: https://www.npmjs.com/get-npm
[vc]: https://code.visualstudio.com/
