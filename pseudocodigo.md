# 📘 O que é Pseudocódigo?

**Pseudocódigo** é uma forma simplificada de descrever algoritmos utilizando linguagem natural estruturada. Ele serve como um rascunho lógico antes da implementação em uma linguagem de programação real.

### ✅ Características:

* Fácil de entender.
* Não segue regras rígidas de sintaxe.
* Focado na **lógica**, não na **forma**.
* Usado para **planejar e comunicar algoritmos**.

---

## 📌 Exemplo 1: Verificar se uma pessoa pode votar

**Problema:** A pessoa pode votar se tiver 16 anos ou mais.

```pseudocodigo
Início
  Ler idade
  Se idade >= 16 então
    Escrever "Pode votar"
  Senão
    Escrever "Não pode votar"
Fim
```

---

## 📌 Exemplo 2: Preparar café

**Problema:** Fazer café caso tenha café e água disponíveis.

```pseudocodigo
Início
  Se tem_café E tem_água então
    Colocar água na cafeteira
    Colocar café no filtro
    Ligar a cafeteira
    Esperar o café ficar pronto
    Servir o café
  Senão
    Escrever "Não é possível fazer café"
Fim
```

---

## 📌 Exemplo 3: Calcular o troco de uma compra

**Problema:** Dado o valor da compra e o valor pago, calcular e exibir o troco.

```pseudocodigo
Início
  Ler valor_da_compra
  Ler valor_pago
  troco ← valor_pago - valor_da_compra
  Se troco < 0 então
    Escrever "Valor pago insuficiente"
  Senão
    Escrever "Troco: " + troco
Fim
```
Claro! Abaixo estão **3 exemplos de pseudocódigo aplicados à Matemática**, escritos em **Markdown** com explicações:

---

## 📌 Exemplo 1: Calcular a média de 3 números

> **Problema:** Ler 3 números e calcular a média aritmética.

```pseudocodigo
Início
  Ler num1
  Ler num2
  Ler num3
  media ← (num1 + num2 + num3) / 3
  Escrever "Média = " + media
Fim
```

---

## 📌 Exemplo 2: Verificar se um número é par ou ímpar

> **Problema:** Ler um número inteiro e informar se ele é par ou ímpar.

```pseudocodigo
Início
  Ler numero
  Se numero % 2 = 0 então
    Escrever "Número é par"
  Senão
    Escrever "Número é ímpar"
Fim
```

---

## 📌 Exemplo 3: Calcular o fatorial de um número

> **Problema:** Calcular o fatorial de um número inteiro positivo.

```pseudocodigo
Início
  Ler n
  fatorial ← 1
  Para i de 1 até n faça
    fatorial ← fatorial * i
  FimPara
  Escrever "Fatorial de " + n + " = " + fatorial
Fim
```


