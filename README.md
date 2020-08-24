<img alt="GoStack" src="https://storage.googleapis.com/golden-wind/bootcamp-gostack/header-desafios-new.png" />

<h3 align="center">
  Desafio 10: GoRestaurant Web
</h3>

<blockquote align="center">“O tempo que leva para realizar seus sonhos vai passar de qualquer forma”!</blockquote>

<p align="center">
  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/leandroppf/gostack-desafio-reactjs-crud?color=%2304D361">

  <a href="https://rocketseat.com.br">
    <img alt="Made by Leandro Pedroso" src="https://img.shields.io/badge/made%20by-Leandroppf-%2304D361">
  </a>

  <img alt="License" src="https://img.shields.io/badge/license-MIT-%2304D361">

  <a href="https://github.com/leandroppf/gostack-desafio-reactjs-crud/stargazers">
    <img alt="Stargazers" src="https://img.shields.io/github/stars/leandroppf/gostack-desafio-reactjs-crud?style=social">
  </a>
</p>

## :rocket: Sobre o desafio

Nesse desafio o objetivo era desenvolver uma nova aplicação, a GoRestaurant. Para esse desafio, foi utilizado React.js junto com TypeScript, praticando o conceito de CRUD (Create, Read, Update, Delete).

Essa aplicação deve exibir os pratos de comida criados e permitir a criação, remoção e atualização desses pratos.

### Layout da aplicação

Essa aplicação possui um layout desenvolvido pela equipe da Rocketseat.

O layout pode ser acessado através da página do Figma, no [seguinte link](https://www.figma.com/file/1lK6AVCPybtWeBLCH8B08N/GoRestaurant?node-id=0%3A1).

### Funcionalidades da aplicação

- **`Listar os pratos de comida da sua API`**: Sua página `Dashboard` deve ser capaz de exibir uma listagem, com o campo `title`, `value`, e  `description` e `available` de todos os pratos de comida que estão cadastrados na sua API.

- **`Adicionar novos pratos de comida a sua API`**: Em sua página Dashboard você deve abrir um modal ao clicar no botão `Novo Prato` no Header. Esse modal deve ser responsável por cadastrar uma nova `food` passando os campos `image`, `name`, `description`, `value`.

- **`Editar pratos de comida da sua API`**: Em sua página Dashboard você deve abrir um modal ao clicar no botão `Editar Prato`. Esse modal deve ser responsável por editar uma `food` passando os campos `image`, `name`, `description`, `value`.

- **`Remover pratos de comida da sua API`**: Em sua página Dashboard você deve remover um prato de comida ao clicar no botão com ícone de lixeira no componente Food.

- **`Alterar disponibilidade dos pratos de comida da sua API`**: Em sua página Dashboard você deve alterar a disponibilidade de um prato de comida ao clicar no switch que é controlado pelo valor de `available`.

### Específicação dos testes

O template também possui testes automatizados e um dos objetivos é que o código criado passe em todos os testes listados abaixo:

* **`should be able to list all the food plates from your api`**: Para que esse teste passe, sua aplicação deve permitir que sejam listados, toda os pratos de comidas que são retornadas da sua fake API.

- **`should be able to add a new food plate`**: Para que esse teste passe, você deve permitir que um prato de comida seja adicionado a sua api, adicionando-o também à listagem.

- **`should be able to edit a food plate`**: Para que esse teste passe, você deve permitir que um prato de comida seja editado na sua api, editando-o também na listagem.

- **`should be able to remove a food plate`**: Para que esse teste passe, você deve permitir que um prato de comida seja removido da sua api, removendo-o também da listagem.

- **`should be able to update the availibility of a food plate`**: Para que esse teste passe, em sua dashboard você deve permitir que o status do prato de comida seja alterado entre `Disponível` e `Indisponível`;

---

Desafio concluído no dia 08/08/2020 por Leandro Pinto Pedroso Filho
