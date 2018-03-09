# Arquitetura

* As funções relacionadas ao gerenciamento das casas do jogo da velha ficarão no módulo
**jogovelha.py**.

* O estado de cada casa do jogo será representada por uma string: "." para casa vazia; "X" para casa ocupada pelo 1° jogador; "O" para casa ocupada pelo 2º jogador

* Afunção inicializar() retornara uma lista 3x3, onde casa posição contera uma string