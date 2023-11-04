# Biblioteca Virtual
Este é um projeto de uma biblioteca virtual desenvolvida em SQL, onde os livros são armazenados em um banco de dados. O objetivo principal é demonstrar boas práticas de modelagem de dados e normalização de um banco de dados.

## Objetivo do Projeto
O banco de dados inicial foi entregue em um estado desorganizado, com informações misturadas e estrutura não otimizada. O propósito deste projeto foi realizar a reestruturação e normalização do banco de dados, seguindo boas práticas de modelagem e SQL limpo.

## Estrutura do Banco de Dados
O banco de dados foi estruturado da seguinte forma:

![untitled](https://github.com/evertonmdev/LimpandoDBLivros/assets/122039415/21c05d1e-78d0-4f98-b347-a4cd837409d4)

### Tabelas:

- Livros: Contém informações sobre os livros, como título, autor, editora, ano de publicação e ISBN. 
- Autores: Mantém o registro dos autores.
- Editoras: Armazena os dados das editoras.

### Relacionamentos: 
A tabela de Livros possui chaves estrangeiras (autor_id e editora_id) que se referem às tabelas de Autores e Editoras respectivamente.

## Funcionalidades
- Adição de Livros: É possível adicionar novos livros à biblioteca informando título, autor, editora, ano de publicação e ISBN.

- Consulta de Livros: Permite consultar a lista de livros disponíveis na biblioteca.

- Detalhes de Livro: Ao selecionar um livro, é possível visualizar detalhes como autor, editora, ano de publicação e ISBN.

- Adição de Autores e Editoras: Permite adicionar novos autores e editoras ao sistema.
