# 🧾 Atividade prática ATViv – Sistema Web Distribuído (SPA)

**Professor:** [Gerson da Penha Neto](https://github.com/gerson-pn)

---

## 🚀 Tecnologias utilizadas

<div style="display: flex; gap: 10px;">
<img align="center" alt="TypeScript" height="30" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/typescript/typescript-original.svg"/>

<img align="center" alt="React" height="30" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/react/react-original.svg"/>

<img align="center" alt="Node.js" height="30" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/nodejs/nodejs-original.svg"/>

<img align="center" alt="Express" height="30" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/express/express-original.svg"/>

<img align="center" alt="MySQL" height="30" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/mysql/mysql-original.svg"/>

<img align="center" alt="VSCode" height="30" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/vscode/vscode-original.svg"/>
</div>

---

## ☕ Contextualização

Com a crescente necessidade de modernização digital, a empresa fictícia **WB** decidiu investir em uma arquitetura **distribuída** para seu sistema, visando alcançar alta disponibilidade, escalabilidade e uma experiência de usuário aprimorada.

Após a criação dos módulos CLI e a integração parcial entre front-end e back-end nas atividades anteriores, chegou o momento da **implementação completa de uma aplicação web SPA (Single Page Application)**.

---

## 💡 Atividade proposta

Você é o(a) responsável por projetar e desenvolver uma aplicação web moderna, distribuída, utilizando React no front-end e Node.js com Express no back-end. A comunicação entre as camadas é feita de forma assíncrona, por meio de API REST.

### 🎯 Objetivo:

Entregar uma aplicação web **SPA distribuída**, com integração completa entre front-end e back-end, capaz de atender às demandas da empresa WB.

O sistema deve permitir a gestão de clientes, produtos e serviços, além de possibilitar o cadastro, edição e visualização de dados com uma interface amigável.

---

## 🛠️ Funcionalidades obrigatórias

* Comunicação entre **clientes e servidores distribuídos**
* Aplicação estruturada como **SPA (Single Page Application)**
* Front-end desenvolvido em React
* Back-end com Node.js e Express
* Banco de dados relacional (MySQL ou MariaDB)
* Funcionalidades completas de CRUD para clientes, produtos e serviços
* Interface amigável, responsiva e intuitiva

---

## ✅ Pré-requisitos

Antes de rodar o sistema, certifique-se de ter instalado:

* [Node.js](https://nodejs.org/) (versão 16 ou superior)
* [MySQL](https://www.mysql.com/)
* npm (vem com o Node.js)

Verifique com:

```bash
node -v
npm -v
```

---

## ▶️ Como executar o projeto

1. **Clone este repositório:**

```bash
git clone https://github.com/raphaelamonteiro/ATVV-WB.git
cd ATVIV-WB
```

2. **Configure o banco de dados:**

Crie um banco de dados com o nome indicado no `.env` ou no arquivo de configuração da aplicação e atualize os dados de acesso conforme necessário.

3. **Instale as dependências do back-end:**

```bash
cd wb-backend
npm install
```

4. **Inicie o servidor back-end:**

```bash
npm run dev
```

5. **Instale as dependências do front-end:**

```bash
cd ../wb-frontend
npm install
```

6. **Inicie o front-end:**

```bash
npm run dev
```

7. **Acesse no navegador:**

```bash
http://localhost:3000
```

---

### 🧩 *Materiais de Apoio*

* 📚 [Documentação do React](https://reactjs.org)
* 📘 [Node.js + Express Guide](https://expressjs.com/)
* 🛢️ [MySQL Documentation](https://dev.mysql.com/doc/)

---

> Por [Raphaela Monteiro](https://github.com/raphaelamonteiro)

