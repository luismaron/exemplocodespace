---
marp: true
theme: ifpr
title: Tutorial Básico – GitHub Codespaces
paginate: true
---

# GitHub Codespaces

### Um ambiente de programação na nuvem

---

## O que é o Codespaces?

- VS Code rodando no navegador
- Não precisa instalar nada
- Roda HTML, CSS, JS, Node, Python, Java etc.
- Inclui terminal Linux
- Permite instalar extensões

---

## Requisitos

- Ter uma conta no **GitHub**
- Ter acesso a um repositório (use o que criamos em aula)

> Você pode usar um repositório próprio ou de outra pessoa.

---

## Criando seu primeiro Codespace

1. Abra a página de um repositório no GitHub
2. Clique no botão verde **<> Code**
3. Vá até a aba **Codespaces**
4. Clique em **Create codespace on main**

O ambiente abre no navegador.

---

## Interface do Codespaces

Você terá:

- **VS Code completo**
- **Explorer** (arquivos)
- **Search**
- **Source Control**
- **Terminal Linux**
- **Extensions**
- Visualização de portas (para rodar sites)

---

## Fazendo upload de seus arquivos
Você pode fazer upload de seus arquivos arrastando para dentro do explorador de arquivos

## Criando arquivos HTML/CSS/JS

1. Clique em **New File**
2. Crie arquivos como:
   - `index.html`
   - `style.css`
   - `script.js`
3. O autosave funciona normalmente
4. O preview abre quando você rodar o projeto

---

## ▶ Rodando um site com Live Server

1. Abra a aba **Extensions**
2. Instale **Live Server**
3. Abra o arquivo **index.html**
4. Clique em **Go Live**

O Codespaces abre uma URL para acessar seu site.

---

## 🧪 Rodando aplicações Node.js

1. Abra o terminal
2. Execute:
   ```bash
   npm install
   npm start
   ```
3. O Codespaces detecta a porta
4. Clique na porta → "Open in Browser"

---

## 🔁 Usando Git no Codespaces

Painel **Source Control**:

- Ver modificações
- Dar **Stage** nos arquivos
- Escrever mensagem de commit
- **Commit**
- Clique em **Sync Changes** para enviar ao GitHub

---

## 🌿 Criando branches

1. Clique no nome da branch atual (ex.: main)
2. Selecione **Create new branch**
3. Nomeie a branch
4. Comece a editar normalmente

---

## 📦 Encerrando ou apagando o Codespace

No GitHub:

1. Vá em **Your Codespaces**
2. Clique nos três pontinhos
3. Você pode:
   - **Stop** (pausar)
   - **Delete** (apagar)

---

# 🎉 Fim!

## Agora você já consegue usar o Codespaces para desenvolver direto no navegador.

Dúvidas? Bora praticar! 🚀
