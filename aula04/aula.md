# Aula 04 - Variáveis

Assista aos vídeos: 
* Parte **teórica**: https://youtu.be/-ny7Kqm0V68
  * _Este vídeo contém uma explicação teórica sobre o que são variáveis em qualquer linguagem de programação._
.
* Parte **prática**: https://youtu.be/Qxz5TKqYkCg
  * _Este vídeo demonstra na prática como trabalhar com variáveis em Javascript. Mas é importante ficar atento a alguns detalhes do vídeo:_
    * O conteúdo é apresentado numa ferramenta chamada Visual Studio Code, mas ela não é obrigatória. Você pode escolhar por criar todo código no Repl ou no próprio navegador, conforme explicado na [aula anterior](../aula03/aula.md);
    * Tudo o que é mostrado no arquivo `scripts.js` pode ser feito no Repl ou no próprio navegador. Nestes casos, você não precisa se preocupar com o arquivo `home.html` que é apresentado no vídeo;
    * Embora o vídeo mostre a criação de variáveis com o prefixo `let`, isto não é muito importante para o aprendizado neste momento. Você pode criar variáveis digitando diretamente o nome da variável e seu valor. Ex.: `empresa = "CWI"`

> É **#fundamental** que você assista aos vídeos e leia o material complementar. É **#opcional** _(embora bem interessante)_ que você faça o exercício.

---

#### _Material complementar:_

_Importante:_

* Toda variável tem um nome;
* Uma variável tem/recebe um valor;
* O símbolo `=` indica que um valor está sendo atribuído à variável. Para testar se uma variável é igual a outra, deve-se usar `==`.

...

_Tipos de variáveis:_

* **Numérico**: valores numéricos positivos ou negativos, podendo ter valores fracionários se necessário _(muitas linguagens tratam números inteiros e fracionários como tipos diferentes; não é o caso de Javascript)_. Ex.:
  ```javascript
  idade = 30
  ano = 2020
  temperatura = -5.2
  saldoConta = 1157.48
  pi = 3.14159265359
  ```

* **Caracter**: também conhecido como `string`, são variáveis que podem ter qualquer valor, numérico, textual ou com caracteres especiais. Seu valor é sempre colocado entre aspas. Ex.:
  ```javascript
  endereco = "Avenida dos 15, nº 985 - CEP: 9876-532"
  programa = "CWI Reset: reset, restart, go!"
  paragrafo = "Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum."
  ```

* **Lógico**: também conhecido como `booleano`, são variáveis que só têm dois valores: `true` _(verdadeiro)_ e `false` _(falso)_. Ex.:
  ```javascript
  menorDeIdade = false
  aprovado = true
  ```

---

#### _Exercício:_

Repare na variável `apresentacao` mostrada a seguir. Ela é uma `string` que representa um texto que pode mudar conforme o valor de outras variáveis.

Identifique e crie todas as variáveis necessárias para que o texto de `apresentacao` seja exibido sem erros. Depois, crie a variável `apresentacao` exatamente como mostrado a seguir e a imprima da seguinte forma: `console.log(apresentacao)`.

```javascript
apresentacao = "Meu nome é " + nomeCompleto + " (sou conhecido[a] como " + apelido + ") e tenho " + idade + " anos. Nasci no dia " + dataNascimento + ", na cidade de " + localNascimento + ". Tenho " + altura + "m de altura e atualmente estou " + (trabalhando ? "empregado" : "desempregado") + "."
```

_Dica: você deve criar as demais variáveis `antes` de criar a variável `apresentacao`._

_**Após** fazer o exercício, dá uma conferida no [nosso exemplo](resolucao.md) também._ 

---

:point_left: [Voltar para aula anterior](../aula03/aula.md) ..... [Avançar para próxima aula](../aula05/aula.md) :point_right: