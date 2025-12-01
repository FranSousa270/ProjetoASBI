📘 Projeto — Associação da Saúde Bucal Infantil

Este projeto foi criado com o objetivo de atender crianças em situação de vulnerabilidade, oferecendo acompanhamento de saúde bucal através de uma plataforma simples e eficiente.

O sistema foi desenvolvido inteiramente em PHP e JavaScript.

Dentistas voluntários podem se cadastrar no site, liberar horários e atender pacientes inscritos. Os associados (pacientes) conseguem visualizar horários disponíveis, fazer agendamentos e acompanhar seu histórico de atendimentos.

🚀 Funcionalidades do Sistema
👨‍⚕️ Para Dentistas

Cadastro e login como Dentista

Carteirinha com informações pessoais

Liberação de horários disponíveis

Finalização de consultas com:

Procedimento realizado

Observações

Relatórios gerados com Chart.js

Lista de pacientes atendidos

Pesquisa por nome e procedimento para dar continuidade ao tratamento

👤 Para Associados (Pacientes)

Cadastro e login como Associado

Carteirinha do paciente

Histórico completo de atendimentos

Acesso aos horários liberados pelos dentistas

Realização de agendamentos diretamente pela plataforma

🛠️ Requisitos

Certifique-se de ter instalado:

PHP >= 8.0

Servidor Web (Apache ou Nginx)

MySQL

IMPORTANTE:

O projeto foi desenvolvido utilizando a porta 3316 do XAMPP.
Por favor, altere a porta do seu MySQL para 3316 para evitar erros de conexão.

🗄️ Banco de Dados

Crie um banco MySQL chamado:

clinica_1


Importe o arquivo:

database.sql


Este arquivo contém apenas a estrutura das tabelas necessárias.

⚠️ Ajustes Necessários (Contratempos)

Infelizmente, por falta de tempo, duas conexões ficaram fora da padronização.
Por isso, você precisa criar manualmente:

1. conexao.php (na raiz do projeto)

Arquivo responsável pela conexão geral ao banco.

2. db.php (dentro da pasta /agendamento)

Arquivo responsável pela conexão específica usada no sistema de agendamento.

No futuro, será feita a padronização de ambos.
Exemplos de como devem ser esses arquivos estão incluídos no repositório.

🧭 Como Navegar pelo Sistema
👨‍⚕️ Dentista

Cadastre-se como Dentista no menu "Cadastro".

Faça login como Dentista.

Acesse sua Carteirinha.

Vá até Agenda no menu lateral.

Libere seus horários disponíveis.

Aguarde os associados realizarem agendamentos.

Após a consulta, acesse "Finalizar Consulta" e registre:

Procedimento

Observações

👤 Associado (Paciente)

Cadastre-se como Associado.

Faça login.

Acesse sua Carteirinha.

Vá em Agendamentos no menu lateral.

Veja os horários liberados pelos dentistas.

Escolha um horário e confirme o agendamento.

Veja todo seu histórico de atendimentos na Carteirinha
