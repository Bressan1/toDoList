# ✅ To‑Do List (JavaScript) — DOM + LocalStorage

Uma aplicação simples de lista de tarefas feita em **JavaScript puro**, manipulando o **DOM** e salvando as tarefas no **LocalStorage**, para que elas permaneçam mesmo após recarregar a página.

---

## 🎯 Funcionalidades

* Adicionar tarefas digitando no input e pressionando **Enter**
* Adicionar tarefas clicando no botão **Adicionar**
* Remover tarefas com botão **Apagar**
* Persistência de dados com **LocalStorage**
* Carregamento automático das tarefas salvas ao abrir a página

---

## 🧩 Estrutura do projeto

```text
todo-list/
├─ index.html
├─ style.css
└─ script.js
```

---

## ▶️ Como executar

1. Baixe/clone o projeto
2. Abra o `index.html` no navegador
3. Digite uma tarefa e pressione **Enter** ou clique em **Adicionar**

---

## 🧠 Como funciona (visão geral)

O projeto seleciona três elementos do HTML:

* `.input-tarefa` → campo de texto onde você digita a tarefa
* `.btn-tarefa` → botão para adicionar tarefa
* `.tarefas` → lista (container) onde os `<li>` são inseridos

Fluxo:

1. Usuário cria tarefa (Enter ou botão)
2. Criamos um `<li>` com o texto
3. Adicionamos um botão **Apagar** dentro do `<li>`
4. Salvamos a lista no LocalStorage
5. Ao abrir a página, carregamos as tarefas do LocalStorage

