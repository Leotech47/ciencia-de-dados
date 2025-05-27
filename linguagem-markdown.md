### 📝 O que é **Markdown**?

**Markdown** é uma linguagem de marcação leve e simples criada para facilitar a escrita e a formatação de textos que possam ser convertidos em HTML. É muito usada em plataformas como **GitHub**, **GitLab**, **Bitbucket**, blogs, documentações técnicas e arquivos `README.md`.

---

### ✅ Vantagens do Markdown:

* **Fácil de aprender** e usar.
* Permite escrever **texto formatado** sem depender de editores complexos.
* Funciona em diversos ambientes (navegadores, editores, terminais).
* É amplamente usado em **documentação de projetos**.

---

### 📘 Estrutura Básica do Markdown

Abaixo, os **principais elementos** usados para escrever um bom `README.md` no GitHub:

---

#### 1. **Títulos**

```markdown
# Título nível 1
## Título nível 2
### Título nível 3
```

#### 2. **Parágrafos e Quebras de linha**

* Parágrafos são separados por **linhas em branco**.
* Para quebrar linha sem novo parágrafo, adicione dois espaços no final da linha.

---

#### 3. **Negrito e Itálico**

```markdown
**negrito**
*itálico*
***negrito e itálico***
```

---

#### 4. **Listas**

* **Listas não ordenadas:**

```markdown
- Item 1
- Item 2
  - Subitem
```

* **Listas ordenadas:**

```markdown
1. Passo 1
2. Passo 2
```

---

#### 5. **Links e Imagens**

```markdown
[Texto do link](https://exemplo.com)
![Texto alternativo da imagem](caminho/para/imagem.png)
```

---

#### 6. **Códigos e Blocos de Código**

* Código em linha:

```markdown
Use o comando `npm install`.
```

* Bloco de código:

<pre><code>```linguagem
console.log("Olá Mundo");
```</code></pre>

---

#### 7. **Citações e Observações**

```markdown
> Esta é uma citação
```

---

#### 8. **Tabelas**

```markdown
| Nome     | Idade | Cidade     |
|----------|-------|------------|
| João     | 30    | São Paulo  |
| Maria    | 25    | Curitiba   |
```

---

### 📌 Estrutura Sugerida para um `README.md` no GitHub

````markdown
# Nome do Projeto

Descrição breve do que o projeto faz e sua finalidade.

## 🚀 Funcionalidades

- ✅ Funcionalidade 1
- ✅ Funcionalidade 2
- ✅ Funcionalidade 3

## 💻 Tecnologias utilizadas

- Node.js
- React
- Express
- PostgreSQL

## 📦 Instalação

```bash
git clone https://github.com/seu-usuario/repositorio.git
cd repositorio
npm install
npm start
````

## 🧪 Como usar

Instruções para rodar o projeto localmente ou executar testes.

## 📝 Licença

Este projeto está licenciado sob a licença MIT.

```

