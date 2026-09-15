# 📚 Sistema de Biblioteca

## 🎯 Objetivo

O Sistema de Biblioteca tem como objetivo facilitar o gerenciamento de livros, usuários, empréstimos e devoluções, tornando a organização da biblioteca mais rápida e eficiente.

## ⚠️ Problema

O controle manual de livros e empréstimos pode causar perda de informações, atrasos e dificuldade para localizar livros. O sistema busca resolver esses problemas através da organização digital das informações.

## 👥 Público-alvo / Usuários

* Bibliotecários
* Funcionários
* Alunos

## ⚙️ Funcionalidades

* Cadastro de usuários
* Cadastro de livros
* Consulta de livros
* Consulta de disponibilidade
* Registro de empréstimos
* Registro de devoluções
* Controle de livros disponíveis
* Relatórios

## 📋 Requisitos

### Requisitos Funcionais

* **RF01:** Cadastrar usuários
* **RF02:** Cadastrar livros
* **RF03:** Consultar livros
* **RF04:** Registrar empréstimos
* **RF05:** Registrar devoluções

### Requisitos Não Funcionais

* **RNF01:** O sistema deverá possuir autenticação.
* **RNF02:** O sistema deverá realizar backup.
* **RNF03:** A interface deverá ser responsiva.

## 📌 Regras de Negócio

* Um usuário não poderá realizar novo empréstimo caso possua livro em atraso.
* Um livro emprestado não poderá ser emprestado novamente.
* Somente usuários cadastrados poderão realizar empréstimos.

## 👤 Casos de Uso

Os principais casos de uso do sistema são:

* Cadastrar usuário
* Cadastrar livro
* Consultar livro
* Realizar empréstimo
* Registrar devolução
* Consultar disponibilidade do livro

## 🗄️ Banco de Dados

O banco de dados será responsável por armazenar informações de:

* Usuários
* Livros
* Empréstimos

As principais informações armazenadas serão os dados dos usuários, dados dos livros e informações sobre os empréstimos e devoluções.

## 🏗️ Arquitetura

O sistema será dividido em três partes principais:

**Interface → Sistema → Banco de Dados**

A interface permite a interação com o usuário, o sistema processa as informações e o banco de dados armazena os dados.

## 🖥️ Telas

O sistema contará com telas para:

* Login
* Página inicial
* Cadastro de livros
* Consulta de livros
* Empréstimos
* Devoluções

Uma imagem da tela do sistema está disponível na documentação.

## 🧪 Testes

Serão realizados testes para verificar:

* Cadastro de usuários
* Cadastro de livros
* Consulta de livros
* Registro de empréstimos
* Registro de devoluções

## 📊 Diagrama UML

O projeto possui um diagrama UML de casos de uso, representando os principais usuários e funcionalidades do sistema.

## 📁 Documentação

A documentação completa está organizada na pasta **docs**, contendo:

* [Requisitos](docs/requisitos.md)
* [Regras de Negócio](docs/regras-negocio.md)
* [Casos de Uso](docs/casos-de-uso.md)
* [Banco de Dados](docs/banco-dados.md)
* [Arquitetura](docs/arquitetura.md)
* [Telas](docs/telas.md)
* [Testes](docs/testes.md)

## 👨‍💻 Equipe

* Julia Maria Campos Costa
* Luis Fellipe Barbosa Gomes
* Kayo Gonzaga de Lima
* Maria Luiza Taques da Silva
* Guilherme Vinicius da Silva Correa

## 📌 Versão

**1.0**

---

## 🌐 GitHub Pages

A documentação do projeto está disponível online através do GitHub Pages.

