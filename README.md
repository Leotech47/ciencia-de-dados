Claro! Aqui está um resumo em **Markdown**:

---

# 📌 Filtrando Números Pares e Múltiplos de 4 (1 a 100)

## 📝 Descrição

O objetivo é gerar uma lista com os números de **1 a 100** que sejam **pares** e **múltiplos de 4**. Isso é feito utilizando a técnica de **list comprehension** em Python. Antes, também representamos essa lógica em **pseudocódigo** para facilitar o entendimento da estrutura algorítmica.

---

## 🔄 Pseudocódigo

```plaintext
INÍCIO
  CRIAR lista numeros VAZIA
  PARA x DE 1 ATÉ 100 FAÇA
    SE x MÓDULO 2 IGUAL A 0 E x MÓDULO 4 IGUAL A 0 ENTÃO
      ADICIONAR x NA lista numeros
    FIM SE
  FIM PARA
  IMPRIMIR lista numeros
FIM
```

### ✅ Leitura:

> Para cada número de 1 a 100, verifique se ele é par e múltiplo de 4. Se for, adicione à lista. Ao final, imprima a lista.

---

## 🐍 Código em Python (List Comprehension)

```python
numeros = [x for x in range(1, 101) if x % 2 == 0 and x % 4 == 0]
print(numeros)
```

### 💡 Observação:

Como todo número múltiplo de 4 já é par, o código pode ser simplificado para:

```python
numeros = [x for x in range(1, 101) if x % 4 == 0]
print(numeros)
```

---

## ✅ Resultado Esperado

```plaintext
[4, 8, 12, 16, 20, 24, 28, 32, 36, 40, 44, 48, 52, 56, 60, 64, 68, 72, 76, 80, 84, 88, 92, 96, 100]
```

---
