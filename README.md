# 🛫 Planner

O projeto Planner tem como objetivo ajudar o usuário para criar uma viagem com nome, data de início e fim. Dentro da viagem o usuário pode planejar sua viagem adicionando atividades para realizar em cada dia, links para facilitar.

## ⚙️ Como executar localmente
Após clonar o projeto com git clone, siga os passos:

1. Utilize o IntelliJ IDEA Community, abra-o;
2. Na tela inicial escolha a opção para abrir o projeto;
3. Selecione a pasta clonada;
4. Entre no arquivo PlannerApplication.java, note que aparece um botão para execução do arquivo no canto superior direito;
5. Clique no botão para executar o projeto.

Utilize o Postman ou Insomnia para testar as requisições da aplicação.


## ✨ Requisitos funcionais

1. O usuário cadastra uma viagem informando o local de destino, data de início, data de término, e-mails dos convidados e também seu nome completo e endereço de e-mail;
2. O criador da viagem recebe um e-mail para confirmar a nova viagem através de um link. Ao clicar no link, a viagem é confirmada, os convidados recebem e-mails de confirmação de presença e o criador é redirecionado para a página da viagem;
3. Os convidados, ao clicarem no link de confirmação de presença, são redirecionados para a aplicação onde devem inserir seu nome (além do e-mail que já estará preenchido) e então estarão confirmados na viagem;
4. Na página do evento, os participantes da viagem podem adicionar links importantes da viagem como reserva do AirBnB, locais para serem visitados, etc...
5. Ainda na página do evento, o criador e os convidados podem adicionar atividades que irão ocorrer durante a viagem com título, data e horário;
6. Novos participantes podem ser convidados dentro da página do evento através do e-mail e assim devem passar pelo fluxo de confirmação como qualquer outro convidado

## 🗃️ Features Extras

- [ ]  Adicionar uma validação nos campos de data
    - [ ]  A data de começo da viagem, é inferior a data de término viagem
    - [ ]  A data de uma atividade está entre as datas da viagem
        
        **Exemplo:**
        Viagem entre os dias 20 á 25 de julho no Rio de Janeiro
        
        ⇒ Atividade 19 de julho
        
        ⇒ Atividade 21 de julho
        
- [ ]  Extração do core das trips pra dentro de uma classe Service
- [ ]  Mapeamento das exceções da nossa aplicação
    - [ ]  Com tratativas de erro personalizadas
