````markdown
# O que é Lógica de Programação?

Lógica de programação é o conjunto de regras e técnicas usadas para resolver problemas por meio de algoritmos, utilizando uma sequência lógica de instruções. Ela é a base para escrever programas em qualquer linguagem de programação e envolve raciocínio lógico, análise e estruturação de dados.

## Exemplos práticos

1. **Verificação de maioridade**
   ```javascript
   const idade = 20;

   if (idade >= 18) {
     console.log("Maior de idade");
   } else {
     console.log("Menor de idade");
   }
````

*Lógica:* Verifica se a idade informada é maior ou igual a 18.

2. **Cálculo de média de notas**

   ```javascript
   const nota1 = 7.5;
   const nota2 = 8.0;
   const media = (nota1 + nota2) / 2;

   if (media >= 6) {
     console.log("Aprovado");
   } else {
     console.log("Reprovado");
   }
   ```

   *Lógica:* Calcula a média de duas notas e decide o resultado.

3. **Laço para contar de 1 a 5**

   ```javascript
   for (let i = 1; i <= 5; i++) {
     console.log(i);
   }
   ```

   *Lógica:* Repete uma ação (imprimir número) enquanto a condição for verdadeira.

```

````markdown
## Por que a lógica de programação é importante?

- **Base para qualquer linguagem:** Antes de aprender uma linguagem de programação (como JavaScript, Python ou Java), é essencial entender a lógica por trás dos programas.
- **Resolução de problemas:** Ajuda a quebrar problemas complexos em partes menores e solucionáveis.
- **Eficiência:** Um bom raciocínio lógico permite criar algoritmos mais rápidos, organizados e com menos erros.

## Mais exemplos práticos

4. **Validação de senha**
   ```javascript
   const senha = "123456";

   if (senha.length >= 6) {
     console.log("Senha válida");
   } else {
     console.log("Senha muito curta");
   }
````

*Lógica:* Verifica se a senha possui pelo menos 6 caracteres.

5. **Cálculo de desconto em compras**

   ```javascript
   const valorCompra = 120;
   let desconto = 0;

   if (valorCompra > 100) {
     desconto = valorCompra * 0.1; // 10% de desconto
   }

   const valorFinal = valorCompra - desconto;
   console.log(`Valor final: R$ ${valorFinal}`);
   ```

   *Lógica:* Aplica desconto em compras acima de R\$ 100.

6. **Verificar número par ou ímpar**

   ```javascript
   const numero = 7;

   if (numero % 2 === 0) {
     console.log("Número par");
   } else {
     console.log("Número ímpar");
   }
   ```

   *Lógica:* Usa o operador módulo (%) para saber se o número é divisível por 2.

```

````markdown
## Mais exemplos práticos de lógica de programação

7. **Simulação de login simples**
   ```javascript
   const usuario = "admin";
   const senha = "1234";

   if (usuario === "admin" && senha === "1234") {
     console.log("Acesso permitido");
   } else {
     console.log("Acesso negado");
   }
````

*Lógica:* Verifica se o usuário e a senha correspondem aos valores esperados.

8. **Calculadora simples com switch**

   ```javascript
   const operador = "+";
   const num1 = 10;
   const num2 = 5;
   let resultado;

   switch (operador) {
     case "+":
       resultado = num1 + num2;
       break;
     case "-":
       resultado = num1 - num2;
       break;
     case "*":
       resultado = num1 * num2;
       break;
     case "/":
       resultado = num1 / num2;
       break;
     default:
       console.log("Operador inválido");
   }

   console.log(`Resultado: ${resultado}`);
   ```

   *Lógica:* Executa operações com base no operador informado.

9. **Contador regressivo**

   ```javascript
   let contador = 5;

   while (contador > 0) {
     console.log(contador);
     contador--;
   }

   console.log("Contagem encerrada");
   ```

   *Lógica:* Executa uma ação enquanto uma condição for verdadeira, reduzindo o valor a cada repetição.

## Conclusão

A lógica de programação é essencial para qualquer desenvolvedor, pois é o alicerce sobre o qual os programas são construídos. Dominar a lógica permite criar sistemas eficientes, escaláveis e fáceis de manter, independentemente da linguagem usada.

```

````markdown
## Exercício prático para treinar lógica de programação

### Problema:
Crie um algoritmo que receba o nome de um produto, o preço unitário e a quantidade comprada. Calcule o valor total da compra e aplique um desconto de:

- 5% se o valor for entre R$ 100 e R$ 200;
- 10% se for acima de R$ 200.

Ao final, exiba o valor com desconto.

### Solução em JavaScript:
```javascript
const nomeProduto = "Camiseta";
const precoUnitario = 75;
const quantidade = 3;

const valorTotal = precoUnitario * quantidade;
let desconto = 0;

if (valorTotal > 200) {
  desconto = valorTotal * 0.10;
} else if (valorTotal >= 100) {
  desconto = valorTotal * 0.05;
}

const valorFinal = valorTotal - desconto;

console.log(`Produto: ${nomeProduto}`);
console.log(`Total sem desconto: R$ ${valorTotal.toFixed(2)}`);
console.log(`Desconto: R$ ${desconto.toFixed(2)}`);
console.log(`Total com desconto: R$ ${valorFinal.toFixed(2)}`);
````

*Lógica aplicada:*

* Multiplicação para calcular o total.
* Condicional para aplicar o desconto correto.
* Subtração para obter o valor final.

---

