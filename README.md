# Teste de front-end Via Varejo

Este teste busca avaliar quesitos técnicos para as pessoas que se candidatem às vagas de desenvolvimento front-end da Via Varejo. Com algumas alterações de requisitos realizadas pela NewTab Academy.

## O desafio

O objetivo é criar uma SPA (Single Page Application) seguindo [este layout](https://goo.gl/yMrCaf).

## O que a aplicação deverá fazer:

- Incluir transações de compra ou venda de mercadoria.
- Criar um extrato das transações incluídas. As transações deverão ser mostradas na ordem em que foram incluídas.
- Mostrar o saldo final e destacar se houve lucro ou prejuízo.
- A aplicação deverá ser responsiva e estar de acordo com o layout fornecido.
- Persistir as transações no Local Storage.

## Outros requisitos

### HTML

- As opções do campo “Tipo de transação” são: Compra e Venda.
- Caso não exista nenhuma transação cadastrada, adicione a mensagem “Nenhuma transação cadastrada.” na lista do Extrato.

### CSS

- O layout deve se adaptar e mudar de acordo com o tamanho da tela
  - Testar em smartphones, tablets (modos portrait e landscape) e monitores a partir de 1024px até 1900px.
- A fonte utilizada é a [Lato](https://fonts.google.com/specimen/Lato).
- A largura máxima do conteúdo é 1100px.

### JavaScript

- Validar o formulário para que todos os campos sejam preenchidos.
- Adicionar uma máscara no campo “Valor” para que apenas números sejam preenchidos e com a formatação correta. (Padrão: XX,XX)
- Ao adicionar uma nova transação, persistir no Local Storage e já atualizar a lista com o extrato. Atualizar também o cálculo apresentado.
- Ao clicar no link “Limpar dados”, apresentar uma mensagem de confirmação e em seguida apagar as informações, atualizando a lista.

## O que será avaliado

- Boas práticas de HTML
- Responsividade e boas práticas de CSS
- Conhecimento de Javascript orientado a objeto, funcional e/ou reativo
- Utilização de git
