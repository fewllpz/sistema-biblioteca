# Banco de Dados

## Tabelas principais

### Usuários

* ID
* Nome
* CPF
* E-mail
* Senha

### Livros

* ID
* Título
* Autor
* Editora
* Ano
* Disponibilidade

### Empréstimos

* ID
* Usuário
* Livro
* Data do empréstimo
* Data de devolução

## Relacionamentos

Um usuário pode realizar vários empréstimos.

Um livro pode aparecer em vários registros de empréstimos ao longo do tempo.
