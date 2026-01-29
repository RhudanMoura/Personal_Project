# Personal_Project

readme do projeto:

# Plataforma de Gestão de Eventos e Bilheteira

Aplicação web full stack desenvolvida como **projeto final de curso**, com foco em
organização de código, segurança e integridade de dados.

O sistema contempla tanto a **área pública (front-office)** quanto um
**painel administrativo (back-office)**, cobrindo todo o ciclo de criação,
gestão e venda de bilhetes para eventos.

---

##  Objetivo do Projeto

Desenvolver uma plataforma completa para gestão de eventos, permitindo que
administradores criem e gerenciem eventos e que utilizadores possam visualizar,
comprar e gerir bilhetes de forma segura e eficiente.

O projeto foi pensado para simular um **cenário real de aplicação web**, indo
além de um CRUD simples.

---

##  Tecnologias Utilizadas

### Front-end
- HTML5
- CSS3
- Bootstrap
- JavaScript (Vanilla)
- Fetch API / AJAX

### Back-end
- PHP 8
- MySQL / MariaDB
- PDO (Prepared Statements)

### Outros
- Git & GitHub
- Sessões PHP
- JSON

---

##  Funcionalidades

### Área Pública (Front-office)
- Visualização de eventos disponíveis
- Consulta de detalhes dos eventos
- Carrinho de compras persistente
- Compra de bilhetes
- Interface dinâmica sem recarregamento de página

### Painel Administrativo (Back-office)
- Autenticação e controle de acesso
- Criação, edição e remoção de eventos
- Gestão de categorias
- Gestão de bilhetes
- Upload e gestão de imagens
- Visualização de dados administrativos

---

##  Segurança e Boas Práticas

- Autenticação com `password_hash()` e `password_verify()`
- Uso de **Prepared Statements** para prevenção de SQL Injection
- Controle de sessões e permissões
- Separação entre lógica de negócio e apresentação
- Validação de dados no servidor

---

##  Banco de Dados

O banco de dados foi estruturado com foco em **integridade e consistência**:

- Uso de **transações SQL** para evitar inconsistências em operações críticas
- **Triggers** para controlo automático de stock de bilhetes
- **Stored Procedures** para encapsular regras de negócio
- **Views** para facilitar consultas e relatórios

---

##  Arquitetura do Projeto

- Separação clara entre:
  - front-office
  - back-office
  - camada de acesso a dados
- Código modular e organizado
- Estrutura pensada para facilitar manutenção e evolução futura

---

## Como Executar o Projeto

1. Clonar este repositório
2. Importar o ficheiro SQL do banco de dados
3. Configurar as credenciais de acesso ao banco
4. Executar o projeto em ambiente local (ex: XAMPP, WAMP ou similar)

As instruções detalhadas de instalação estão descritas na documentação do projeto.

---

##  Aprendizados

Durante o desenvolvimento deste projeto, foram consolidados conhecimentos em:
- Desenvolvimento web full stack
- Comunicação assíncrona entre front-end e back-end
- Estruturação e normalização de banco de dados
- Segurança em aplicações web
- Organização de projetos em ambiente realista

---

##  Observações

Este projeto foi desenvolvido com fins **acadêmicos**, como parte da formação em
desenvolvimento web, representando meu nível técnico atual e minha evolução na área.

Sugestões e feedbacks são bem-vindos.

