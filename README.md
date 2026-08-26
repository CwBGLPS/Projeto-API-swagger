# LojaApi + loja-front

## 📌 Objetivo do projeto

Sistema de gerenciamento de loja desenvolvido como projeto acadêmico, com o objetivo de simular um cenário real de e-commerce/gestão comercial: um back-end responsável por expor uma API REST para o cadastro e controle de entidades da loja (como produtos, categorias e usuários), com autenticação segura, e um front-end capaz de consumir essa API de forma integrada, permitindo login e operações de CRUD através da interface.

## 🛠️ Tecnologias utilizadas

**Back-end (LojaApi)**
- C# / .NET
- Entity Framework Core (ORM)
- MySQL (banco de dados)
- JWT (JSON Web Token) para autenticação

**Front-end (loja-front)**
- React
- Axios (consumo da API)
- React Router (navegação entre páginas)
- localStorage (persistência do token de autenticação no navegador)

## 📖 Estrutura do projeto

O projeto é dividido em dois repositórios que se comunicam entre si:

- **LojaApi**: expõe os endpoints REST com CRUD completo para as entidades da loja, protegidos por autenticação JWT.
- **loja-front**: consome a API via Axios, gerencia as rotas da aplicação com React Router e mantém o usuário autenticado salvando o token no localStorage.

## 🎓 Aprendizados

Durante o desenvolvimento deste projeto, aprofundei conceitos como:

- Modelagem de entidades e relacionamentos com Entity Framework Core, incluindo geração e aplicação de migrations no MySQL;
- Implementação de autenticação e autorização via JWT, entendendo o fluxo completo de geração, envio e validação de tokens entre front-end e back-end;
- Estruturação de uma API REST organizada em camadas (controllers, models, contexto de dados);
- Consumo de APIs autenticadas no front-end com Axios, incluindo o tratamento de headers de autorização em cada requisição;
- Gerenciamento de estado de autenticação no React, persistindo o token no localStorage e controlando o acesso a rotas protegidas com React Router.

Esse projeto consolidou minha compreensão de como back-end e front-end se conectam em uma aplicação full stack real, desde a modelagem do banco até a experiência final do usuário.
