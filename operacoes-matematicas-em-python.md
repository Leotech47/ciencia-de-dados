Claro! Abaixo está uma **aula descritiva sobre operações matemáticas em Python** no formato Markdown. Você pode copiar e colar em qualquer editor que suporte esse formato (como VS Code, Jupyter Notebook ou repositórios no GitHub).

---

# 📚 Aula: Operações Matemáticas em Python

## ✳️ Introdução

Python é uma linguagem poderosa para cálculos matemáticos, oferecendo desde operações básicas até funções avançadas. Nesta aula, vamos abordar:

1. Operações aritméticas básicas
2. Precedência de operadores
3. Operadores de atribuição
4. Operações com números decimais e negativos
5. Uso do módulo `math`
6. Exemplos práticos

---

## 1️⃣ Operações Aritméticas Básicas

| Operador | Descrição       | Exemplo   | Resultado |
| -------- | --------------- | --------- | --------- |
| `+`      | Adição          | `5 + 3`   | `8`       |
| `-`      | Subtração       | `10 - 4`  | `6`       |
| `*`      | Multiplicação   | `6 * 7`   | `42`      |
| `/`      | Divisão         | `15 / 3`  | `5.0`     |
| `//`     | Divisão inteira | `17 // 3` | `5`       |
| `%`      | Módulo (resto)  | `10 % 4`  | `2`       |
| `**`     | Exponenciação   | `2 ** 3`  | `8`       |

```python
print(5 + 3)
print(10 - 4)
print(6 * 7)
print(15 / 3)
print(17 // 3)
print(10 % 4)
print(2 ** 3)
```

---

## 2️⃣ Precedência de Operadores

A ordem de execução segue a lógica matemática (PEMDAS):

**P**arênteses
**E**xponenciação
**M**ultiplicação e **D**ivisão
**A**dição e **S**ubtração

```python
# Sem parênteses
resultado1 = 2 + 3 * 4      # Resultado: 14

# Com parênteses
resultado2 = (2 + 3) * 4    # Resultado: 20

print(resultado1)
print(resultado2)
```

---

## 3️⃣ Operadores de Atribuição

| Operador | Equivalente a      | Exemplo   |
| -------- | ------------------ | --------- |
| `=`      | Atribuição simples | `x = 5`   |
| `+=`     | `x = x + valor`    | `x += 3`  |
| `-=`     | `x = x - valor`    | `x -= 2`  |
| `*=`     | `x = x * valor`    | `x *= 4`  |
| `/=`     | `x = x / valor`    | `x /= 2`  |
| `**=`    | `x = x ** valor`   | `x **= 2` |

```python
x = 10
x += 5     # x = 15
x *= 2     # x = 30
print(x)
```

---

## 4️⃣ Números Decimais e Negativos

Python trabalha bem com números **decimais (float)** e **negativos**:

```python
a = -10
b = 4.5
c = a + b   # Resultado: -5.5
print(c)
```

---

## 5️⃣ Módulo `math` (Funções Matemáticas Avançadas)

Para operações mais complexas, use o módulo `math`:

```python
import math

print(math.sqrt(16))        # Raiz quadrada → 4.0
print(math.pow(2, 3))       # Potência → 8.0
print(math.factorial(5))    # Fatorial → 120
print(math.floor(4.7))      # Arredonda para baixo → 4
print(math.ceil(4.2))       # Arredonda para cima → 5
print(math.pi)              # Constante PI
```

---

## ✅ Exemplos Práticos

### Exemplo 1: Cálculo de Média

```python
nota1 = 8.5
nota2 = 7.0
nota3 = 9.0

media = (nota1 + nota2 + nota3) / 3
print(f"Média final: {media:.2f}")
```

### Exemplo 2: Verificar número par ou ímpar

```python
numero = 7

if numero % 2 == 0:
    print("Par")
else:
    print("Ímpar")
```

---

## 📝 Conclusão

Com esses conhecimentos, você já pode:

* Realizar cálculos simples e avançados
* Utilizar operadores e funções matemáticas do Python
* Aplicar lógica matemática em seus códigos

➡️ Pratique criando pequenos scripts com cálculos e lógicas matemáticas!

---

