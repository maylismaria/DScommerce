# 🛒 **E-commerce API – Spring Boot**


API REST desenvolvida com **Java + Spring Boot**, integrada ao **MySQL**, utilizando **JPA/Hibernate** e **JWT** para autenticação e autorização.
Projeto inspirado no **DSCommerce**, com foco em boas práticas, arquitetura limpa, segurança e modelo de domínio sólido.

<p align="center">
  <img src="https://img.shields.io/badge/Java-17-orange?logo=openjdk">
  <img src="https://img.shields.io/badge/Spring_Boot-3.0-green?logo=springboot">
  <img src="https://img.shields.io/badge/JPA-Hibernate-blue">
  <img src="https://img.shields.io/badge/MySQL-8.0-blue?logo=mysql">
  <img src="https://img.shields.io/badge/JWT-Security-purple">
</p>

---


# 🚀 **Sobre o Projeto**

A API implementa o backend completo de um sistema de e-commerce, incluindo:

* Cadastro, autenticação e gerenciamento de usuários
* Catálogo de produtos com busca e paginação
* Controle de categorias
* Carrinho de compras
* Registro e gerenciamento de pedidos
* Controle de acesso por perfis (CLIENT / ADMIN)
* Camada de segurança com Spring Security + JWT

---

# 🔒 **Autenticação e Autorização**

* Login com geração de JWT
* Controle de acesso baseado em perfil
* Rotas públicas e privadas
* Administradores possuem acesso total à área de gestão

---

# 👤 **Usuários**

* Cadastro e login
* Atualização de perfil
* Acesso ao histórico de pedidos
* CRUD completo para administradores

---

# 🛍️ **Produtos e Categorias**

* Listagem pública com paginação (12 itens por página)
* Filtro por nome
* CRUD completo para administradores

---

# 📦 **Pedidos**

* Criar pedido a partir do carrinho
* Controle de status:
  *Aguardando pagamento*, *Pago*, *Enviado*, *Entregue*, *Cancelado*
* Registro de pagamento
* Histórico de pedidos do usuário

---

# 🛠️ **Tecnologias Utilizadas**

* Java 17
* Spring Boot 3
* Spring Web
* Spring Data JPA
* Spring Security
* JSON Web Token (JWT)
* MySQL
* Maven

---





