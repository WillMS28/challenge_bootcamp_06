<h1 align='center'>Projeto Back-End de transações financeiras</h1>

<p>Aplicação que possibilita a realização de transações financeiras e listagem</p>

## Sobre a Aplicação

<p>Foi realizada com o ituito de colocar em prática os conceitos de models, repositories e services, itulizando os conhecimentos adquiridos com Node.js junto ao Typescript.<br />
Essa será uma aplicação para armazenar transações financeiras de entrada e saída, que deve permitir o cadastro e a listagem dessas transações.</p>

<h4 align="center"> 
	  ✅ Projeto finalizado 
</h4>

### Features

- [x] Cadastrar transações ```income``` para depósitos
- [x] Cadastrar transações ```outcome``` para retiradas
- [x] Balanço do saldo da conta 
- [x] Listagem com todas as transações realizadas juntamente com o balanço
- [x] Impedir de realizar ```outcome``` quando a conta estiver sem o saldo 

### Pré-requisitos

Antes de começar, você vai precisar ter instalado em sua máquina as seguintes ferramentas:
[Git](https://git-scm.com), [Node.js](https://nodejs.org/en/). 
Além disto é bom ter um editor para trabalhar com o código como [VSCode](https://code.visualstudio.com/)

### 🔄 Rodando o Back End (servidor)

```bash
# Clone este repositório
$ git clone <https://github.com/WillMS28/challenge_bootcamp_06>

# Acesse a pasta do projeto no terminal/cmd
$ cd challenge_bootcamp_06

# Instale as dependências
$ npm install

# Execute a aplicação em modo de desenvolvimento
$ npm run dev:server

# O servidor inciará na porta:3333 - acesse <http://localhost:3333>
```

### 🛠 Tecnologias

As seguintes ferramentas foram usadas na construção do projeto:

- [Node.js](https://nodejs.org/en/)
- [TypeScript](https://www.typescriptlang.org/)
