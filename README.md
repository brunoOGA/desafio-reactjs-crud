<h1 align="center">Desafio: GoRestaurant Web</h1>

## Sobre 
A aplicação usa uma fake API, e exibe os pratos de comida criados e permitir a criação, remoção e atualização desses pratos.

## Funcionalidades da aplicação

- Listar os pratos de comida da sua API: A página Dashboard exibe uma listagem, com o campo title, value, e description e available de todos os pratos de comida que estão cadastrados na API.

- Adicionar novos pratos de comida a sua API: Na página Dashboard o usuário ao clicar no botão Novo Prato no Header abre um modal. Esse modal é responsável por cadastrar uma nova food passando os campos image, name, description, value.

- Editar pratos de comida da sua API: Na página Dashboard o usuário ao clicar no botão Editar Pratoa bre um modal. Esse modal é responsável por editar uma food passando os campos image, name, description, value.

- Remover pratos de comida da sua API: Na página Dashboard o usuário ao clicar no botão com ícone de lixeira no componente Food deveremover um prato de comida.

- Alterar disponibilidade dos pratos de comida da sua API: Na página Dashboard o usuário pode alterar a disponibilidade de um prato de comida ao clicar no switch que é controlado pelo valor de available.

---
## Tecnologias utilizadas
- [React.js](https://pt-br.reactjs.org/)
---
## Como baixar o projeto 

```bash
  
  # Clonar o repositório
  $ git clone https://github.com/brunoOGA/desafio-reactjs-crud
  
  # Entrar no diretório
  $ cd desafio-reactjs-crud
  
  # Instalar as dependências
  $ yarn
  
  # Realizar os testes
  $ yarn test
  
  # Iniciar API fake
  yarn json-server server.json -p 3333
  
  # Iniciar o prjeto
  $ yarn start
  
```
