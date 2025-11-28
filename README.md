## Projeto Associação da Saúde Bucal Infatil

Esse projeto foi criado almejando alcançar crianças em situações carentes que não conseguem ter acompanhamento na saúde bucal, criado inteiramente com PHP e Javascript.  

Dentistas voluntários podem se cadastrar no nosso site e liberar horários através da tabela de agendamento. Depois que é liberado o horário pelo dentista o usuário tem acesso na sua tabela e pode marcar o horário liberado. Depois na tabela do dentista aparece uma opção de finalizar a consulta onde ele escreve o procedimento e as observações.
Também temos uma carteirinha para dentistas quanto para usuários. 
Na carteirinha do dentista temos opções de relatórios, feita com char.js, os pacientes já antendidos por ele e os pacientes gerais onde todos os usuários com consultas finalizadas estão, onde o destista pode pesquisar nome e procedimento para dar continuidade no tratamento do paciente. 
Na carteirinha do paciente temos o seu histórico de atendimento onde mostra quem o atendeu e qual o procedimento feito e que observações o dentista fez.

## Requisitos

Certifique-se de ter instalado:
*   PHP >= 8.0
*   Servidor Web (Apache ou Nginx)
*   Por favor mude a porta do seu xaamp ou Nginx para 3316, infelizmente o projeto foi feito todo encima dessa porta e não houve tempo de alterar

## Banco de Dados

Crie um banco MySQL chamado `clinica_1`.

Importe o arquivo `database.sql` que está na pasta na raiz do projeto  .

Esse arquivo contém apenas a estrutura das tabelas necessárias.

## Alguns contra tempos
É necessário criar um arquivo chamado conexão.php na pasta raiz do projeto e um projeto chamado db.php na pasta de agendamento, infelizmente contra tempos que eu planejo consertar no futuro, vou deixar exemplos de ambos onde eles devem estar




