# 📚 Atividades com DOM (JavaScript)

## 📌 Descrição

Este repositório reúne três exercícios práticos utilizando **JavaScript e manipulação do DOM (Document Object Model)**. As atividades têm como objetivo demonstrar como criar, modificar e inserir elementos HTML dinamicamente em uma página.

---

## 🚀 Tecnologias utilizadas

* HTML5
* JavaScript (DOM)

---

## 🧠 Conceitos abordados

* Criação de elementos com `createElement()`
* Manipulação de conteúdo com `textContent`
* Seleção de elementos com `querySelector()` e `getElementById()`
* Uso de `appendChild()`
* Eventos com `addEventListener()`
* Otimização com `DocumentFragment`

---

## 📂 Exercícios

### 🔹 Exercício 1 – Adicionar Item na Lista

Cria dinamicamente um novo item `<li>` ao clicar no botão.

**Funcionamento:**

* Um botão chama a função `adicionarItem()`
* Um novo elemento é criado e inserido na lista `<ul>`

---

### 🔹 Exercício 2 – Criar Lista com Fragmento

Gera múltiplos itens de forma otimizada usando `DocumentFragment`.

**Funcionamento:**

* Um loop cria 5 itens de lista
* Os itens são armazenados em um fragmento
* O fragmento é inserido de uma só vez na `<ul>`

💡 *Vantagem:* melhora o desempenho ao evitar várias atualizações no DOM.

---

### 🔹 Exercício 3 – Listar Nomes com Evento

Exibe uma lista de nomes ao clicar em um botão.

**Funcionamento:**

* Um array contém os nomes
* Ao clicar no botão:

  * A lista é limpa
  * Os nomes são percorridos com `forEach`
  * Cada nome é inserido como `<li>` usando `DocumentFragment`

---

## ▶️ Como executar

1. Baixe ou clone o repositório
2. Abra os arquivos `.html` no navegador
3. Interaja com os botões para ver o comportamento do DOM

---

## 📈 Objetivo educacional

Essas atividades servem como prática para entender:

* Como o JavaScript interage com o HTML
* Como tornar páginas web dinâmicas
* Boas práticas de performance na manipulação do DOM
