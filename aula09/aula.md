# Aula 09 - Funções, procedimentos e comentários

Leia o artigo: https://www.linhadecomando.com/javascript/javascript-inserindo-comentarios

Assista ao vídeo: https://youtu.be/2g2bfD6q5NQ

> É **#fundamental** que você assista ao vídeo e leia o artigo. É **#opcional** _(embora bem importante)_ que você leia o material complementar e faça os exercícios.

---

#### Leitura complementar:_

* http://www.linhadecodigo.com.br/artigo/2918/a-importancia-de-uma-boa-documentacao.aspx

---

#### _Exercícios:_

1. Crie uma função chamada `imprimir` que recebe um argumento e simplesmente imprime ele na tela;
2. Lembra dos exercícios que propusemos na [Aula 05 - Variáveis](../aula05/aula.md#exercícios)? Com base neles, faça o seguinte:
   * Crie uma função para cada algoritmo proposto lá, exceto o número `6`;
   * Todas as funções devem _retornar_ o valor final;
   * Procure dar nomes que façam sentido às funções. _Ex.: a função para o item `4` poderia se chamar `mediaAritmetica` ou `calcularMediaAritmetica`_;
   * Procure utilizar comentários para documentar cada método;
   * Na função da média aritmética, evite colocar todos os itens como argumentos do método, pois isso limitaria sua utilização a um número fixo de elementos. Tente implementar uma lógica para receber um array e calcular a média em cima dele, tornando a função mais reaproveitável em diferentes situações.
3. Com as funções criadas, execute todo código abaixo e verifique se os resultados são os esperados _(o resultado esperado de cada função está no comentário ao lado da chamada)_:
```javascript
cwi = "CWI"
reset = "Reset"
imprimir(mesmoNome(cwi, cwi))   // true
imprimir(mesmoNome(cwi, reset)) // false

imprimir("---")

imprimir(maiorDeIdade(30)) // true
imprimir(maiorDeIdade(18)) // true
imprimir(maiorDeIdade(5))  // false

imprimir("---")

imprimir(valorComJuros(100))   // 110
imprimir(valorComJuros(984.5)) // 1082.95

imprimir("---")

imprimir(mediaAritmetica([1]))             // 1
imprimir(mediaAritmetica([1, 4, 10]))      // 5
imprimir(mediaAritmetica([1, 2, 3, 4, 5])) // 3

imprimir("---")

imprimir(margemBruta(1000000, 500000))      // 50
imprimir(margemBruta(528459.11, 632501.87)) // -19.68[...]
```

_**Após** ter feito os exercícios, dá uma conferida em [como nós resolvemos](resolucao.md) eles também._

---

:point_left: [Voltar para aula anterior](../aula08/aula.md) ..... [Avançar para próxima aula](../aula10/aula.md) :point_right: