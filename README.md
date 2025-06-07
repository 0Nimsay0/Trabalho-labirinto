# Labirinto - Resolução Automática

Este projeto implementa um programa em C# que cria e resolve automaticamente um labirinto em uma matriz 15x15, buscando encontrar um ponto específico chamado "queijo" (representado por 'Q').

---

## Descrição

O programa gera um labirinto aleatório usando caracteres `|` para paredes e `.` para caminhos livres, delimitado por paredes `*`. Um ponto aleatório do labirinto é marcado como o "queijo" (`Q`), que é o objetivo a ser encontrado.

O usuário deve informar as posições iniciais (linha e coluna) para que o programa inicie a busca. A solução utiliza uma abordagem com pilhas para percorrer o labirinto, marcando o caminho explorado com `'v'` e os pontos mortos com `'x'`.

---

## Funcionalidades

- Geração aleatória de labirinto com paredes e caminhos livres.
- Definição aleatória da posição do "queijo".
- Busca automática do queijo a partir da posição inicial informada pelo usuário.
- Exibição passo a passo da resolução do labirinto no console.
- Indicação clara quando não há caminho possível para o queijo.

---

## Sobre o código

O programa utiliza:

- Arrays multidimensionais para representar o labirinto.
- Pilhas (`Stack<int>`) para controle do caminho durante a resolução.
- Funções para geração, exibição e resolução do labirinto.
- Controle simples do console para animação da busca.

---
