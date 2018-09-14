#### desafio-explorar-marte
#### Desafio Explorar Marte

Um conjunto de sondas foi enviado pela NASA à Marte e irá pousar num planalto. Esse planalto, que curiosamente é retangular, deve ser explorado pelas sondas para que suas câmeras embutidas consigam ter uma visão completa da área e enviar as imagens de volta para a Terra.

A posição e direção de uma sonda são representadas por uma combinação de coordenadas x-y e uma letra representando a direção cardinal para qual a sonda aponta, seguindo a rosa dos ventos em inglês.

-------North/Norte

West/Oeste---------East/Leste

--------South/Sul

O planalto é dividido numa malha para simplificar a navegação. Um exemplo de posição seria (0, 0, N), que indica que a sonda está no canto inferior esquerdo e apontando para o Norte.

Para controlar as sondas, a NASA envia uma simples sequência de letras. As letras possíveis são "L", "R" e "M". Destas, "L" e "R" fazem a sonda virar 90 graus para a esquerda ou direita, respectivamente, sem mover a sonda. "M" faz com que a sonda mova-se para a frente um ponto da malha, mantendo a mesma direção.

Nesta malha o ponto ao norte de (x,y) é sempre (x, y+1).


- Desenvolver o algoritmo, e implementar em node.js
  - Finalizado https://github.com/klebercarvalho/desafio-explorar-marte/
- Fazer BDD / TDD, e implententar testes usanod Chai (assertation library) e Mocha (test runner)
  - Terminar até 17/09
- Fron-end usando Vue
  - Terminar até 20/09
4) Utilizar Docker
  - Terminar até 24/09

