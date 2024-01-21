# Levantamento de Requisitos
* **Período:** 
    08/01 a 12/01
* **Conteúdo:** 
    Levantamento, Documentação e Priorização de Requisitos.

# Link Trello
https://trello.com/invite/b/YGT2miiQ/ATTIe568c2ed0944b1cd9502c529dc1ab2c5DC0423FE/rp1-2024-jessica

# Sistema de Agendamento de Refeição Escolar
Este sistema permite:
* Gerenciamento de cadastros e desbloqueios de usuários pela **Secretária**;
* Agendamentos e cancelamentos de agendamentos de refeições pelos **Usuários**; 
* O gerenciamento do cadastro de usuários, agendamentos e cardápios pelos **Administradores**;
* O gerenciamento de cardápios para a **Equipe da Cozinha**.

# User Stories

### Para Secretaria
* **HU01:** **Como secretária**, quero registrar e atualizar os dados dos usuários no sistema para manter o processo de agendamento de refeições organizado e eficiente.
* **HU02:** **Como secretária**, quero desbloquear alunos que foram automaticamente bloqueados após três faltas, para que possam retomar seus agendamentos.

### Para Usuários
* **HU03:** **Como aluno ou servidor**, quero agendar minhas refeições no sistema para garantir minha janta no refeitório.
* **HU04:** **Como aluno ou servidor**, quero visualizar o cardápio semanal no sistema para decidir se farei o agendamento de refeições.
* **HU05:** **Como aluno ou servidor**, quero cancelar meu agendamento de refeição no sistema para evitar desperdícios e não ser penalizado por faltas.
* **HU06:** **Como aluno ou servidor**, desejo receber notificações sobre mudanças no cardápio para ajustar meus agendamentos conforme necessário.
* **HU07:** **Como aluno ou servidor**, desejo ser notificado se a refeição do dia for cancelada para evitar idas desnecessárias ao refeitório.
* **HU08:** **Como aluno ou servidor**, desejo ser notificado se for bloqueado para poder solicitar desbloqueio junto a secretaria.

### Para Administrador
* **HU09:** **Como administrador escolar**, quero acessar e gerenciar os cadastros dos usuários para manter o sistema atualizado e funcional.
* **HU10:** **Como administrador escolar**, quero acessar e modificar o cardápio no sistema conforme necessário para garantir a atualização das opções de refeições.
* **HU11:** **Como administrador escolar**, quero visualizar todos os agendamentos, bloqueios e registros de faltas para monitorar a demanda e planejar recursos adequadamente.
* **HU12:** **Como administrador escolar**, desejo acessar e analisar o estoque no sistema para tomar decisões informadas sobre a compra de mais produtos.

### Para Equipe da Cozinha
* **HU13:** **Como membro da equipe da cozinhar**, quero cadastrar o cardápio semanal no sistema para que os usuários possam verificar as opções disponíveis.
* **HU14:** **Como membro da equipe da cozinhar**, quero atualizar informações do cardápio no sistema sempre que houver mudanças, para manter os usuários informados.
* **HU15:** **Como membro da equipe da cozinhar**, quero que o sistema me forneça o total de agendamentos até às 19:30 de cada dia para planejar a quantidade necessária de alimentos, evitando desperdícios.
* **HU16:** **Como membro da equipe da cozinhar**, quero validar os QR Codes dos agendamentos para confirmar a presença dos usuários.
* **HU17:** **Como membro da equipe da cozinhar**, quero visualizar todos os agendamentos do dia para gerenciar a disponibilidade de refeições para usuários não agendados.
* **HU18:** **Como membro da equipe da cozinhar**, quero atualizar o cardápio no sistema em dias sem refeição disponível para evitar agendamentos desnecessários.
* **HU19:** **Como membro da equipe da cozinhar**, quero registrar o estoque de alimentos no sistema para que a administração possa monitorar e gerenciar os recursos disponíveis.
* **HU20:** **Como membro da equipe da cozinhar**, desejo poder revalidar QR Codes em caso de repetição de alimentação, para assegurar um controle rigoroso sobre o consumo de refeições e manter a precisão dos registros.

# Requisitos Não-Funcionais (RNFs) 

* **RNF1:** **Como usuário**, desejo uma interface intuitiva e fácil de usar no sistema de agendamento de refeições, para que eu possa realizar minhas tarefas sem dificuldades. 
* **RNF2:** **Como usuário**, espero que o sistema responda rapidamente, idealmente em menos de 2 segundos, para que eu possa fazer buscas e reservas de forma eficiente. 
* **RNF3:** **Como desenvolvedor**, quero garantir que o sistema seja seguro e proteja os dados pessoais dos usuários, implementando medidas de segurança robustas como criptografia e autenticação.
* **RNF4:** **Como administrador**, preciso que o sistema suporte até 400 usuários simultâneos sem degradar o desempenho, para garantir um serviço estável e confiável.
* **RNF5:** **Como administrador**, desejo que o sistema tenha uma disponibilidade de 99% e uma baixa taxa de erros, com mecanismos para rápida recuperação em caso de falhas, para assegurar um serviço contínuo e confiável. 
* **RNF6:** **Como usuário**, quero que o sistema seja compatível com diferentes dispositivos e sistemas operacionais, para que eu possa acessá-lo de qualquer lugar e a qualquer momento. 
* **RNF7:** **Como administrador**, desejo que o sistema se integre eficientemente com a base de dados existente da escola, para facilitar a automação do agendamento e a sincronização de dados.
* **RNF08:** **Como administrador**, quero que o sistema implemente um mecanismo de backup automático diário, para garantir a integridade e a recuperação de dados.
* **RNF09:** **Como administrador**, preciso que o acesso ao sistema seja restrito a professores e servidores da escola, com controles de acesso apropriados, para manter a segurança dos dados. 
* **RNF10:** **Como desenvolvedor**, desejo que o sistema seja desenvolvido em Java, para garantir compatibilidade e facilidade de manutenção.
* **RNF11:** **Como desenvolvedor**, quero que o sistema seja confiável e impeça o vazamento de informações dos usuários, para manter a confiança e a segurança dos dados.
* **RNF12:** **Como administrador**, desejo que o sistema receba atualizações regulares para segurança, novas funcionalidades e melhorias, para manter o sistema atualizado e eficiente.

# Regras de Negócio (RNs) 

* **RN01:**	**Serviço de Refeição Mediante Confirmação de QR Code:** Refeições são servidas somente após a confirmação do QR Code gerado pelo sistema de agendamento.
* **RN02:**	**Política de Bloqueio por Ausências:** Usuários que não comparecerem ao agendamento por três vezes serão bloqueados, necessitando de desbloqueio pela secretaria.
* **RN03:**	**Cancelamento de Agendamento com Notificação Obrigatória:** Usuários têm a opção de cancelar agendamentos, sendo obrigatória a notificação à cozinha sobre tais cancelamentos.
* **RN04:**	**Atualização Antecipada do Cardápio Semanal:** O cardápio para a semana seguinte deve ser atualizado no sistema pela equipe da cozinha/administração até o domingo anterior.
* **RN05:**	**Limites de Tempo para Agendamentos Diários:** Agendamentos para refeições do dia são permitidos até às 19:30. Após este horário, o sistema só aceita agendamentos para o dia seguinte.
* **RN06:**	**Geração Automática de Listas de Agendamento Pós-19:30:** Listas com todos os agendamentos são geradas automaticamente após as 19:30, sendo enviadas para a cozinha e administração.
* **RN07:**	**Validação de QR Code para Acesso à Refeição:** Acesso à refeição é concedido mediante apresentação e validação do QR Code de agendamento.
* **RN08:**	**Coleta de Dados no Agendamento para Segurança: ** Informações como nome, CPF, são coletadas durante o agendamento para fins de identificação e segurança.
* **RN09:**	**Sincronização com Base de Dados da Secretaria:** O sistema de agendamentos deve sincronizar-se com a base de dados da secretaria para consistência e verificação de informações.
* **RN10:**	**Disponibilidade do Cardápio Publicado para Todos:** Uma vez publicado, o cardápio fica disponível para visualização por todos os usuários do sistema.
* **RN11:**	**Penalidades por Falta de Comparecimento:** Usuários que faltarem ao refeitório após marcar presença por três vezes serão submetidos a penalidades.
* **RN12:**	**Fila Prioritária para Usuários com Agendamento:** Usuários sem agendamento que comparecerem ao refeitório devem aguardar todos os usuários agendados passarem primeiro.
* **RN13:**	**Informações sobre Mudanças no Cardápio:** O sistema comunica aos usuários qualquer alteração no cardápio.
* **RN14:**	**Resumo Diário de Agendamentos para a Cozinha:** O sistema fornece um resumo diário dos agendamentos à cozinha às 19:30 e encerra a possibilidade de novos agendamentos para o dia.
* **RN15:**	**Refeições de Última Hora não agendadas:** Refeições podem ser concedidas para usuários sem agendamento de última hora conforme a disponibilidade de refeições.
