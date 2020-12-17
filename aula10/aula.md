# Aula 10 - Juntando tudo

Assista ao vídeo: https://youtu.be/aWv871ExPqY

> É **#fundamental** que você assista ao vídeo. É **#opcional** _(embora bem importante)_ que você faça o exercício.

---

#### _Exercício:_

Uma empresa quer verificar se um colaborador está qualificado para a aposentadoria. Para estar em condições de se aposentar, ele deve atender a pelo menos um dos seguintes critérios: 
* Ter pelo menos 65 anos de idade;
* Ter trabalhado no mínimo 30 anos;
* Ter pelo menos 60 anos de idade e 25 anos de trabalho.

Você deve criar uma função chamada `verificarAposentadoria`, que recebe um `nome` como argumento e verifica se aquele colaborador pode se aposentar. 

A função deve imprimir uma mensagem dizendo `"Parabéns, já pode sair de férias eternas :)"` ou `"Infelizmente para você, ainda falta um tempo :("`. Caso seja informado o nome de um colaborador que não existe, deve ser apresentada a mensagem `"Colaborador inválido :|"`.

Use os arrays abaixo para considerar as informações de colaboradores, idade e tempo de trabalho:

```javascript
colaboradores    = ['Rhoger', 'Cléverson', 'Gleysberto', 'Nádio', 'Rosiméri', 'Regislane', 'Agripino', 'Wellison']
idades           = [      69,          66,           58,      61,         60,          64,         59,         55]
temposDeTrabalho = [      31,          29,           30,      26,         25,          24,         26,         29]
```

Com a função criada, execute todo código abaixo e verifique se os resultados são os esperados _(o resultado esperado de cada execução está no comentário ao lado da chamada)_:
```javascript
verificarAposentadoria('Rosiméri')    // true (regra 3)
verificarAposentadoria('Agripino')    // false (falta 1 ano de idade para regra 3)
verificarAposentadoria('Rhoger')      // true (todas)
verificarAposentadoria('Hudnélson')   // false (colaborador inexistente)
verificarAposentadoria('Gleysberto')  // true (regra 2)
verificarAposentadoria('Regislane')   // false (falta 1 ano de idade para regra 1 e 1 de trabalho para regra 3)
verificarAposentadoria('Cléverson')   // true (regras 1 e 3)
verificarAposentadoria('Nádio')       // true (regra 3)
verificarAposentadoria('Wellison')    // false (falta 1 ano de trabalho para regra 2)
verificarAposentadoria('Florisberto') // false (colaborador inexistente)
```

_**Após** ter feito o exercício, dá uma conferida em [como nós criamos a função](resolucao.md).

---

:point_left: [Voltar para aula anterior](../aula09/aula.md)
:point_left: [Voltar para o índice](../material.md#algoritmos-e-lógica-de-programação-fundamental)