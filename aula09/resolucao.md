# Aula 09 - Resolução dos exercícios

1)
```javascript
function imprimir(conteudo) {
    console.log(conteudo)
}
```

2) 
```javascript
/* Verifica se os dois nomes informados são iguais.
 */
function mesmoNome(primeiroNome, segundoNome) {
    return primeiroNome == segundoNome
}

/* Verificação de maioridade.
 */
function maiorDeIdade(idade) {
    return idade >= 18
}

/* Realiza o cálculo do valor do boleto com juros.
 Atualmente, a taxa de juros é de 10%. */
function valorComJuros(valorBoleto) {
    return valorBoleto * 1.1
}

/* Cálculo da média aritmética de todos os itens presentes
 no array passado como argumento. */
function mediaAritmetica(itens) {
    soma = 0

    // somar todos os itens do array
    for (index = 0; index < itens.length; index++) {
        soma += itens[index]
    }

    // dividir o somatório pela quantidade de elementos
    return soma / itens.length
}

/* Cálculo da margem bruta da empresa com base na 
 receita líquida de vendas e no custo dos produtos vendidos.
 O resultado final é multiplicado por 100 para considerar o valor percentual. */
function margemBruta(receitaLiquidaVendas, custoProdutosVendidos) {
    lucroBruto = receitaLiquidaVendas - custoProdutosVendidos
    return (lucroBruto / receitaLiquidaVendas) * 100
}
```

---
:point_left: [Voltar para aula](aula.md)