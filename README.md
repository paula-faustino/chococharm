# 🏘️ Aluga-Lá - Sistema de Aluguel e Venda de Imóveis

Sistema de gestão e intermediação de imóveis para locação temporária ou venda, inspirado em plataformas como Airbnb, com foco na usabilidade, integração de pagamento e funcionalidades intuitivas para usuários e anfitriões.

---
## 👥 Desenvolvedores
- KaueAlvess - [GitHub](https://github.com/KaueAlvess )
- Mayara Santana - [GitHub](https://github.com/mayara8666 )
- Paula Faustino - [GitHub](https://github.com/paula-faustino )
---

## 🎯 Objetivo do Sistema

Criar uma plataforma web para aluguel e venda de imóveis, com recursos para:

* Cadastro e gerenciamento de usuários (anfitriões e hóspedes)
* Cadastro de imóveis com fotos, descrição e disponibilidade
* Busca e filtros de imóveis por localização, datas e preços
* Sistema de reservas com integração de pagamento
* Avaliação dos imóveis e usuários
* Painel administrativo para monitoramento das operações

---

## 🔧 Tecnologias Utilizadas

Linguagem: C#
Banco de Dados: MySQL
IDE: Visual Studio
Controle de Versão: Git + GitHub/GitLab

---

## 📅 Planejamento de Desenvolvimento (Equipe: 3 pessoas)

### Etapa 1: Levantamento de Requisitos (1 semana)

**Todos os membros**

* Discussão de funcionalidades
* Criação de fluxos de usuários
* Documento de requisitos

**Entregáveis:**

* Lista de funcionalidades
* Diagrama de fluxo de usuário
* Documento de requisitos técnicos

---

### Etapa 2: Arquitetura e Design do Sistema (2 semanas)

**KaueAlvess (UI/UX + Frontend)**
**Mayara Santana (Backend + Lógica de Negócio)**
**Paula Faustino (Modelagem de Banco de Dados)**

**Atividades:**

* Modelagem do banco de dados (ER)
* Design de interfaces principais (mockups)
* Definição da arquitetura backend (REST API)

**Entregáveis:**

* Diagrama ER
* Protótipos das telas principais
* Estrutura do backend (pastas, endpoints iniciais)

---

### Etapa 3: Desenvolvimento (4 semanas)

#### 🧑‍💻 Dev 1 – Backend & Banco de Dados

**- Paula Faustino - [GitHub](https://github.com/paula-faustino )**
**Responsabilidades:**

* Modelagem e criação das tabelas: `Usuarios`, `Imoveis`, `Reservas`, `Pagamentos`, `Avaliacoes`
* Criação de APIs RESTful
* Segurança (hash de senhas, autenticação JWT)

**Entregáveis:**

* Banco de dados funcional
* APIs para CRUD completo

---

#### 🧑‍💻 Dev 2 – Frontend e Interface

**- KaueAlvess - [GitHub](https://github.com/KaueAlvess )**
**Responsabilidades:**

* Telas: Login, Cadastro, Listagem de Imóveis, Detalhes, Reserva
* Navegação entre páginas
* Responsividade e design amigável
* Consumo das APIs backend

**Entregáveis:**

* Páginas principais funcionando
* Validação de formulários
* Layouts responsivos (mobile/desktop)

---

#### 🧑‍💻 Dev 3 – Lógica de Negócio & Integração

**- Mayara Santana - [GitHub](https://github.com/mayara8666 )**
**Responsabilidades:**

* Classes de domínio: Usuário, Imóvel, Reserva, Avaliação
* Validações de regras de negócio: disponibilidade, datas, conflito de reservas
* Integração frontend-backend
* Geração de logs e mensagens de erro

**Entregáveis:**

* Classes modelo completas
* Controle de reservas com regras aplicadas
* APIs conectadas ao frontend

---

### Etapa 4: Testes e Validação (2 semanas)

**Todos (com foco em QA – Mayara Santana)**

**Atividades:**

* Testes unitários e de integração
* Testes de interface e usabilidade
* Correção de bugs

**Entregáveis:**

* Relatórios de testes
* Correções aplicadas
* Plataforma funcional sem bugs críticos

---

### Etapa 5: Lançamento e Feedback (1 semana)

**Todos (liderança por KaueAlvess)**

**Atividades:**

* Deploy da aplicação
* Coleta de feedback com usuários reais
* Ajustes finais

**Entregáveis:**

* Sistema online
* Relatório de feedback
* Melhorias com base nas sugestões

---

## 🧱 Módulos do Sistema

1. **Cadastro e Login**

   * Usuário anfitrião ou hóspede
   * Autenticação JWT
2. **Gerenciamento de Imóveis**

   * Cadastro com fotos, descrição, localização
   * Edição e exclusão de imóveis
3. **Busca e Filtros**

   * Localização, tipo, faixa de preço, disponibilidade
4. **Sistema de Reservas**

   * Escolha de datas
   * Cálculo de valor
   * Confirmação e pagamento online
5. **Avaliações**

   * Avaliação do imóvel pelo hóspede
   * Avaliação do hóspede pelo anfitrião
6. **Painel Administrativo**

   * Visualização de reservas, usuários, imóveis
   * Gerenciamento de conflitos e suporte

---
