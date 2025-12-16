# 👤 Profile Card – React

Projeto desenvolvido em **React** com o objetivo de criar um **card de perfil reutilizável**, exibindo informações pessoais e profissionais de forma organizada e moderna.

Este projeto é ideal para uso em **portfólios**, **páginas pessoais** ou como base para aplicações maiores que trabalham com perfis de usuários.

---

## 🌐 Descrição do Projeto

A aplicação renderiza um componente `Profile que recebe dados via **props** e exibe:

* Avatar do usuário
* Nome
* Biografia profissional
* Informações de contato
* Links para redes sociais

O foco principal do projeto é a **componentização**, **reutilização de código** e passagem correta de dados no React.

---

## 🚀 Tecnologias Utilizadas

* **React.js** – Biblioteca principal da aplicação
* **JavaScript (ES6+)** – Lógica e estrutura
* **JSX** – Sintaxe declarativa para componentes
* **CSS** – Estilização do layout
* **Vite** – Ambiente de desenvolvimento
* **Node.js / npm** – Gerenciamento de dependências

---


## 🧩 Componente Profile

O componente `Profile` é totalmente reutilizável e recebe as seguintes **props**:

jsx
avatar: string (URL da imagem)
name: string
bio: string
email: string
phone: string
githubUrl: string
linkedinUrl: string
instagramUrl: string


Essas propriedades permitem que o mesmo componente seja utilizado para diferentes perfis, alterando apenas os dados.

---

## 📄 App.jsx

O componente `App é responsável por:

* Importar o componente `Profile
* Definir os dados do perfil
* Passar as informações via props

Exemplo de uso:

jsx
<Profile
  avatar="URL"
  name="Nome"
  bio="Descrição"
  email="email@email.com"
/>


---

## 🎯 Objetivos do Projeto

* Praticar **React básico**
* Trabalhar com **props**
* Criar **componentes reutilizáveis**
* Organizar um projeto React com Vite
* Desenvolver um card de perfil profissional

---

## 🚀 Possíveis Melhorias Futuras

* Tornar o layout responsivo
* Adicionar tema claro/escuro
* Tornar os links configuráveis via JSON
* Integração com API (GitHub, LinkedIn)
* Animações com CSS ou Framer Motion

---

## 👨‍💻 Autor

**Leonardo Schloesser**
Desenvolvedor Full Stack 🚀

* 📧 Email: [devwebschloesser@gmail.com](mailto:devwebschloesser@gmail.com)
* 💻 GitHub: [https://github.com/devwebschloesser](https://github.com/devwebschloesser)
* 🔗 LinkedIn: [https://www.linkedin.com/in/leonardo-schloesser-pinheiro-github-devwebschloesser-a0311b303/](https://www.linkedin.com/in/leonardo-schloesser-pinheiro-github-devwebschloesser-a0311b303/)
* 📸 Instagram: [https://www.instagram.com/_77catarina/](https://www.instagram.com/_77catarina/)

---

⭐ Projeto desenvolvido para fins educacionais e portfólio.
