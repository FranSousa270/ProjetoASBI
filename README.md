## 📘 Projeto — Associação da Saúde Bucal Infantil

Este projeto foi criado com o objetivo de atender crianças em situação de vulnerabilidade, oferecendo acompanhamento de saúde bucal através de uma plataforma simples e eficiente.

O sistema foi desenvolvido inteiramente em PHP e JavaScript.

Dentistas voluntários podem se cadastrar no site, liberar horários e atender pacientes inscritos.
Os associados (pacientes) conseguem visualizar horários disponíveis, realizar agendamentos e acompanhar seu histórico de atendimentos.

## 🚀 Funcionalidades do Sistema
👨‍⚕️ Para Dentistas

Cadastro e login como Dentista

Carteirinha com informações pessoais

Liberação de horários disponíveis

Finalização de consultas com:

Procedimento realizado

Observações

Relatórios com Chart.js

Lista de pacientes atendidos

Pesquisa por nome e procedimento para continuidade de tratamento

---


👤 Para Associados (Pacientes)

Cadastro e login como Associado

Carteirinha personalizada

Histórico completo de atendimentos

Visualização dos horários liberados pelos dentistas

Realização de agendamentos

## 🛠️ Requisitos

Certifique-se de ter instalado:

PHP >= 8.0

Servidor Web (Apache ou Nginx)

MySQL

## ⚠️ IMPORTANTE:
O projeto foi desenvolvido utilizando a porta 3316 do MySQL (XAMPP).
Altere a porta do seu MySQL para 3316 para evitar erros de conexão.

## 🗄️ Banco de Dados

Crie um banco MySQL chamado:
clinica_1


Importe o arquivo localizado na raiz do projeto:

database.sql


Esse arquivo contém apenas a estrutura das tabelas.

## ⚠️ Ajustes Necessários

Devido a contratempos, duas conexões ficaram fora da padronização.
Você precisa criar manualmente os seguintes arquivos:

📌 conexao.php (na raiz do projeto)

Responsável pela conexão principal com o banco.

📌 db.php (na pasta /agendamento)

Responsável pela conexão usada no sistema de agendamentos.

Exemplos de ambos arquivos estão incluídos no repositório, para facilitar a criação.

## 🧭 Como Navegar pelo Sistema

👨‍⚕️ Como usar como Dentista

Cadastre-se como Dentista no menu "Cadastro".

Faça login como Dentista.

Acesse sua Carteirinha.

No menu lateral, vá até Agenda.

Libere horários disponíveis.

Aguarde os associados agendarem.

Após cada consulta, finalize registrando:

Procedimento realizado

Observações

---

👤 Como usar como Associado

Cadastre-se como Associado.

Faça login.

Acesse sua Carteirinha.

Acesse o menu Agendamentos.

Veja os horários disponíveis.

Escolha um horário e confirme o agendamento.

Consulte seu Histórico de Atendimentos na Carteirinha.

## (English version)

## 📘 Project — Children's Oral Health Association

This project was developed to support children in vulnerable situations by providing oral healthcare through a simple and efficient platform.

The system was built entirely with PHP and JavaScript.

Volunteer dentists can register on the website, make their available time slots accessible, and treat registered patients.

Members (patients) can view available time slots, schedule appointments, and track their appointment history.

## 🚀 System Features

### 👨‍⚕️ For Dentists

- Dentist registration and login
- Personalized ID card with personal information
- Availability management for appointments
- Appointment completion with:
  - Procedure performed
  - Notes and observations
- Reports and charts using Chart.js
- List of treated patients
- Search by patient name and procedure to support continuity of treatment

---

### 👤 For Members (Patients)

- Member registration and login
- Personalized membership card
- Complete appointment history
- View time slots made available by dentists
- Schedule appointments

## 🛠️ Requirements

Make sure the following are installed:

- PHP >= 8.0
- Web server (Apache or Nginx)
- MySQL

## ⚠️ IMPORTANT

The project was developed using MySQL port `3316` with XAMPP.

Change your MySQL port to `3316` to avoid connection errors.

## 🗄️ Database Setup

Create a MySQL database named:

`clinica_1`

Import the file located in the project root directory:

`database.sql`

This file contains only the table structure.

## ⚠️ Required Configuration

Due to unforeseen issues, two database connections were not standardized.

You must manually create the following files:

### 📌 `conexao.php` (in the project root directory)

Responsible for the main database connection.

### 📌 `db.php` (inside the `/agendamento` directory)

Responsible for the database connection used by the appointment scheduling system.

Examples of both files are included in the repository to make configuration easier.

## 🧭 How to Use the System

### 👨‍⚕️ Using the System as a Dentist

1. Register as a dentist through the **"Registration"** menu.
2. Log in as a dentist.
3. Access your personalized ID card.
4. Navigate to **"Schedule"** in the sidebar.
5. Make your available time slots accessible for booking.
6. Wait for members to schedule appointments.
7. After each appointment, complete the record by entering:
   - Procedure performed
   - Notes and observations

---

### 👤 Using the System as a Member (Patient)

1. Register as a member.
2. Log in to the system.
3. Access your personalized membership card.
4. Navigate to the **"Appointments"** menu.
5. View the available time slots.
6. Select a time slot and confirm your appointment.
7. Check your appointment history through your membership card.
