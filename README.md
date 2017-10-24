## Otimizaçao

### index.html
-Para otimizar o index.html somente foi retirado o google fonts.

### views/js/main.js
-O maior gargalo é a funcao updatePositions()
1. Foi retirado o scrollTop para nao ter problema de Layout repetido.
2. Foi retirado a variavel Items da funcao já que ela é estatica nao precisando criar toda vez que a funcao é chamada.
3. Foi diminuido a quantidade desnecessaria de pizzas no background já que nao usara as 200.

- Foi adicionado o requestAnimationFrame no updatePosition().
- Foi adiconado o will-change:transform no .css.
- Arrumou o slider de tamanho de pizza.