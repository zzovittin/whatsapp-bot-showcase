
<h1 align="center">WhatsApp Appointment Automation</h1>

<p align="center">
  Healthcare Scheduling System | VHC Soluções
</p>

<p align="center">
  <img src="./bot-badges.svg" alt="Project status"/>
</p>

---

## Overview | Visão geral

Sistema de automação de atendimento e agendamento
de consultas, desenvolvido para clínicas e consultórios.

O projeto tem como objetivo reduzir atividades
administrativas manuais, organizar agendamentos
e automatizar interações com pacientes.

The system focuses on workflow automation, database
integration, session management and healthcare scheduling.

---

## Tech Stack

![n8n](https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)

---

## Functional Scope

| Feature | Description |
|---|---|
| Patient Management | Identificação e cadastro de pacientes |
| Specialties | Consulta de especialidades médicas |
| Scheduling | Agendamento de consultas |
| Availability | Consulta de horários disponíveis |
| Cancellation | Cancelamento e liberação de horários |
| Session Management | Controle do estado do atendimento |
| Business Rules | Validação das operações |

---

## System Architecture

Diagrama conceitual e simplificado da arquitetura
proposta para integração com o WhatsApp.

```mermaid
flowchart TD
    A[WhatsApp] --> B[Integration Layer]
    B --> C[n8n Workflow]
    C --> D[Session Management]
    D --> E[Business Rules]
    E --> F[(PostgreSQL)]
    F --> G[Response Generation]
    G --> B
```

---

## Scheduling Workflow

```mermaid
flowchart TD
    A[Start] --> B[Patient Identification]
    B --> C[Select Specialty]
    C --> D[Select Professional]
    D --> E[Check Availability]
    E --> F[Select Appointment]
    F --> G{Confirmation}
    G -->|Yes| H[Register Appointment]
    G -->|No| E
    H --> I[Send Confirmation]
```

---

## Engineering Principles

- Workflow orchestration
- State management
- Relational database modeling
- SQL queries and data validation
- Business rule implementation
- System integration
- Error handling
- Data consistency

---

## My Responsibilities

- Planejamento e arquitetura da solução.
- Desenvolvimento de fluxos automatizados.
- Modelagem de bancos de dados relacionais.
- Desenvolvimento de consultas SQL.
- Implementação de regras de negócio.
- Gerenciamento de sessões de atendimento.
- Testes e validação de fluxos operacionais.
- Diagnóstico e correção de falhas.
- Desenvolvimento assistido por inteligência artificial.

---

## Project Status

- Current stage: Active development
- Environment: Local development
- Scheduling and cancellation workflows: Implemented
- WhatsApp production integration: Pending
- Source code: Private

---

## Confidentiality

Este repositório possui finalidade exclusivamente
demonstrativa e profissional.

O código-fonte, os workflows proprietários,
as credenciais e os dados de pacientes não são
disponibilizados publicamente.

---

## Author

**Victor Hugo Motta Terraciano**

Software Developer & Co-founder at VHC Soluções

[GitHub Profile](https://github.com/zzovittin) |
[Company Website](https://vhcsolucoes.com.br)
