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

Ótimo! Vamos continuar a aula com mais conteúdos úteis sobre operações matemáticas em Python, ainda no formato Markdown.

---

## 🔁 6️⃣ Operações com Funções Personalizadas

Você pode criar suas próprias funções para reutilizar cálculos:

```python
def soma(a, b):
    return a + b

def potencia(base, expoente):
    return base ** expoente

print(soma(10, 5))           # 15
print(potencia(2, 3))        # 8
```

---

## 🧮 7️⃣ Conversões de Tipos Numéricos

### `int()`, `float()`, `str()`

Essas funções convertem valores entre tipos numéricos e texto.

```python
valor = "10.5"

numero = float(valor)    # Converte string para float
inteiro = int(float(valor))  # Converte string para float e depois para int

print(numero)    # 10.5
print(inteiro)   # 10
```

---

## 📦 8️⃣ Bibliotecas Extras para Matemática

Além do `math`, outras bibliotecas úteis incluem:

### ✅ `random` – Geração de números aleatórios

```python
import random

print(random.randint(1, 10))      # Número inteiro entre 1 e 10
print(random.uniform(1.5, 5.5))   # Número float entre 1.5 e 5.5
```

### ✅ `decimal` – Precisão em cálculos financeiros

```python
from decimal import Decimal

a = Decimal('10.35')
b = Decimal('2.20')

print(a + b)     # Resultado com precisão exata: 12.55
```

---

## 🧑‍🏫 9️⃣ Exercícios Práticos

### 1. Calcular o perímetro e área de um retângulo

```python
largura = 5
altura = 3

perimetro = 2 * (largura + altura)
area = largura * altura

print(f"Perímetro: {perimetro}")
print(f"Área: {area}")
```

### 2. Converter graus Celsius para Fahrenheit

```python
celsius = 30
fahrenheit = (celsius * 9/5) + 32

print(f"{celsius}°C = {fahrenheit}°F")
```

### 3. Calcular a hipotenusa (Teorema de Pitágoras)

```python
import math

cateto1 = 3
cateto2 = 4

hipotenusa = math.sqrt(cateto1**2 + cateto2**2)
print(f"Hipotenusa: {hipotenusa}")
```

---

## 🧾 🔟 Resumo da Aula

* **Operadores**: `+`, `-`, `*`, `/`, `//`, `%`, `**`
* **Ordem de precedência**: Parênteses > Potência > Multiplicação/Divisão > Soma/Subtração
* **Operadores de atribuição**: `=`, `+=`, `-=`, `*=`, etc.
* **Funções do `math`**: `sqrt()`, `pow()`, `floor()`, `ceil()`, `factorial()`
* **Bibliotecas úteis**: `math`, `random`, `decimal`
* **Conversão de tipos**: `int()`, `float()`, `str()`

---

## 🏁 Próximos Passos

* Pratique resolvendo pequenos problemas com matemática em Python
* Estude estruturas de repetição e condicionais para fazer programas interativos
* Aprenda a usar o Jupyter Notebook para testar expressões matemáticas com mais facilidade

---

Perfeito! Vamos adicionar mais conteúdo complementar para fechar bem a aula. Incluirei tópicos como **tratamento de erros matemáticos**, **funções lambda para cálculos simples**, e **boas práticas**. Tudo ainda no padrão Markdown.

---

## 🚫 1️⃣1️⃣ Tratamento de Erros Matemáticos

Em alguns casos, é importante prevenir falhas como **divisão por zero** ou **valores inválidos**:

```python
try:
    a = 10
    b = 0
    resultado = a / b
except ZeroDivisionError:
    print("Erro: divisão por zero não é permitida.")
```

Outro exemplo com raiz quadrada negativa:

```python
import math

try:
    x = -9
    resultado = math.sqrt(x)
except ValueError:
    print("Erro: não é possível calcular a raiz de número negativo.")
```

---

## ⚡ 1️⃣2️⃣ Funções Lambda para Cálculos Simples

Funções lambda são úteis para expressões matemáticas rápidas e reutilizáveis:

```python
# Função tradicional
def dobro(x):
    return x * 2

# Função lambda
dobro_lambda = lambda x: x * 2

print(dobro(5))          # 10
print(dobro_lambda(5))   # 10
```

Exemplo com soma:

```python
soma = lambda a, b: a + b
print(soma(3, 4))  # 7
```

---

## 📌 1️⃣3️⃣ Boas Práticas ao Usar Matemática em Python

* ✅ **Use nomes de variáveis claros** (`raio`, `altura`, `preco_total`)
* ✅ **Comente fórmulas** complexas
* ✅ **Valide entradas do usuário**
* ✅ **Evite usar números mágicos** direto no código (prefira variáveis nomeadas)
* ✅ **Utilize `round()` para controle de casas decimais**

```python
preco = 10 / 3
print(round(preco, 2))   # Resultado: 3.33
```

---

## 🧠 1️⃣4️⃣ Desafio Final

Crie um programa que calcule o valor de uma prestação em atraso, aplicando juros simples:

**Fórmula:**
`prestacao = valor + (valor * taxa * tempo)`

Onde:

* `valor` = valor original da dívida
* `taxa` = juros ao mês (ex: 0.02 para 2%)
* `tempo` = número de meses de atraso

```python
def calcular_prestacao(valor, taxa, tempo):
    return valor + (valor * taxa * tempo)

valor = float(input("Digite o valor original da dívida: "))
taxa = float(input("Digite a taxa de juros (ex: 0.02 para 2%): "))
tempo = int(input("Digite o número de meses em atraso: "))

total = calcular_prestacao(valor, taxa, tempo)
print(f"Valor total com juros: R${total:.2f}")
```

---

## 📘 Conclusão Final

Você aprendeu:

* Operações básicas e avançadas
* Uso de bibliotecas matemáticas
* Tratamento de erros
* Aplicações com lógica
* Práticas seguras para cálculos em Python

Com isso, você tem uma base sólida para aplicar a matemática na programação Python de forma prática e funcional.

---

Se quiser agora, posso gerar:

* 📄 Arquivo `.md` com toda a aula
* 📘 PDF formatado
* 🧪 Versão interativa em Jupyter Notebook

