# Caso de Uso 01: Desbloquear Alunos Bloqueados

**Descrição**: Este caso de uso permite que a secretária desbloqueie alunos que foram automaticamente bloqueados após três faltas, para que possam retomar seus agendamentos. 

**Ator Principal**: Secretária 

**Ator Secundário:**: Sistema de Agendamento de Refeições 

**Pré-condições**:
1.	A secretária deve ter acesso administrativo ao sistema. 

**Pós-condições**:
1.	O aluno é desbloqueado no sistema. 

**Fluxo Principal**:
1.	A secretária acessa o sistema de agendamento de refeições.
2.	Ela seleciona a opção para visualizar alunos bloqueados.
3.	O sistema exibe a lista de alunos bloqueados.
4.	Identifica os alunos que precisam ser desbloqueados e seleciona a opção de desbloqueio.
5.	O sistema solicita confirmação para o desbloqueio.
6.	Realiza o desbloqueio no sistema.
7.	O sistema processa o desbloqueio e atualiza o status do aluno.
8.	O sistema notifica a secretária sobre o sucesso do desbloqueio

**Fluxos Alternativos**:
1.	Erro no Sistema: Se ocorrer um erro, o sistema exibe uma mensagem de erro.
2.	Sessão Expirada: Se a sessão expirar, o sistema retorna à tela de login.
 
# Caso de Uso 02: Cadastrar Dados dos Usuários

**Descrição**: Este caso de uso permite que a secretária cadastre novos usuários no sistema para participarem do processo de agendamento de refeições. 

**Ator Principal**: Secretária 

**Ator Secundário**: Sistema de Agendamento de Refeições 

**Pré-condições**:
1.	A secretária deve ter acesso administrativo ao sistema.
2.	O sistema deve estar operacional. 

**Pós-condições**:
1.	Novos dados de usuário são cadastrados no sistema. 

**Fluxo Principal**:
1.	A secretária acessa o sistema de agendamento de refeições.
2.	O sistema apresenta a interface principal com opções de gerenciamento.
3.	Ela seleciona a opção para cadastrar novos usuários.
4.	O sistema exibe o formulário de cadastro de usuários.
5.	Insere as informações necessárias para o cadastro, como nome, CPF, e status (aluno ou servidor).
6.	O sistema valida as informações inseridas.
7.	Confirma o cadastro no sistema.
8.	O sistema processa o cadastro e cria um novo registro de usuário.
9.	O sistema notifica a secretária sobre o sucesso do cadastro.
10.	Uma mensagem de confirmação é exibida.

**Fluxos Alternativos**:
1.	Erro no Sistema: Se ocorrer um erro, o sistema exibe uma mensagem de erro.
2.	Dados Incompletos ou Inválidos: Se as informações fornecidas estiverem incompletas ou inválidas, o sistema solicita a correção ou complementação dos dados.
3.	Sessão Expirada: Se a sessão expirar, o sistema retorna à tela de login.
 
# Caso de Uso 03: Editar Dados dos Usuários 

**Descrição**: Este caso de uso permite que a secretária edite os dados dos usuários existentes no sistema para manter as informações atualizadas. 

**Ator Principal**: Secretária 

**Ator Secundário**: Sistema de Agendamento de Refeições 

**Pré-condições**:
1.	A secretária deve ter acesso administrativo ao sistema.
2.	O sistema deve estar operacional. 

**Pós-condições**:
1.	Os dados dos usuários são atualizados no sistema.

**Fluxo Principal**:
1.	A secretária acessa o sistema de agendamento de refeições.
2.	O sistema apresenta a interface principal com opções de gerenciamento.
3.	Ela seleciona a opção para editar dados dos usuários existentes.
4.	O sistema exibe a lista de usuários e opções de edição.
5.	Modifica as informações necessárias dos usuários.
6.	O sistema valida as informações modificadas.
7.	Confirma a atualização no sistema.
8.	O sistema processa as alterações e atualiza o registro do usuário.
9.	O sistema notifica a secretária sobre o sucesso da atualização.
10.	Uma mensagem de confirmação é exibida.

**Fluxos Alternativos**:
1.	Erro no Sistema: Se ocorrer um erro, o sistema exibe uma mensagem de erro.
2.	Usuário Não Encontrado: Se o usuário específico não for encontrado, o sistema oferece opções de busca ou filtro para localizar o usuário.
3.	Sessão Expirada: Se a sessão expirar, o sistema retorna à tela de login.
 
# Caso de Uso 04: Excluir Dados dos Usuários

**Descrição**: Este caso de uso permite que a secretária exclua os dados de usuários do sistema quando não são mais necessários. 

**Ator Principal**: Secretária

**Ator Secundário**: Sistema de Agendamento de Refeições 

**Pré-condições**:
1.	A secretária deve ter acesso administrativo ao sistema.
2.	O sistema deve estar operacional. 

**Pós-condições**:
1.	Os dados de um usuário são removidos do sistema. 

**Fluxo Principal**:
1.	A secretária acessa o sistema de agendamento de refeições.
2.	O sistema apresenta a interface principal com opções de gerenciamento.
3.	Ela seleciona a opção para excluir dados de um usuário específico.
4.	O sistema exibe a lista de usuários e opções de exclusão.
5.	A secretária identifica o usuário a ser excluído e seleciona a opção de exclusão.
6.	O sistema solicita confirmação para a exclusão.
7.	Confirma a exclusão no sistema.
8.	O sistema processa a solicitação e remove os dados do usuário.
9.	O sistema notifica a secretária sobre o sucesso da exclusão.
10.	Uma mensagem de confirmação é exibida.

**Fluxos Alternativos**:
1.	Erro no Sistema: Se ocorrer um erro, o sistema exibe uma mensagem de erro.
2.	Sessão Expirada: Se a sessão expirar, o sistema retorna à tela de login.
 
# Caso de Uso 05: Realizar Agendamento

**Descrição**: Este caso de uso permite que um usuário (aluno ou servidor) agende a janta no sistema de agendamento de refeições da escola. 

**Ator Principal**: Aluno ou Servidor 

**Ator Secundário**: Sistema de Agendamento de Refeições 

**Pré-condições**:
1.	O usuário deve estar cadastrado no sistema.
2.	O sistema deve estar operacional.

**Pós-condições**:
1.	A janta é agendada para o usuário.
2.	O sistema atualiza a contagem de refeições para o dia escolhido.

**Fluxo Principal**:
1.	O usuário acessa o sistema de agendamento de refeições.
2.	O sistema apresenta as opções de dias disponíveis para agendar a janta.
3.	O usuário seleciona a opção de agendar a janta para um dia específico.
4.	O sistema verifica a disponibilidade da janta para o dia escolhido.
5.	O sistema solicita a confirmação do usuário para o agendamento.
6.	O usuário confirma o agendamento.
7.	O sistema registra o agendamento e gera um QR Code para a janta do dia escolhido.
8.	O sistema notifica o usuário sobre o sucesso do agendamento.

**Fluxos Alternativos**:
1.	Janta Indisponível: Se a janta para o dia escolhido já estiver esgotada, o sistema notifica o usuário e retorna ao passo 2.
2.	Sessão Expirada: Se a sessão do usuário expirar antes da confirmação, o sistema retorna à tela de login.
3.	Erro no Sistema: Se ocorrer um erro no sistema durante o agendamento, uma mensagem de erro é exibida e o usuário é solicitado a tentar novamente mais tarde.

# Caso de Uso 06: Cancelar Agendamento

**Descrição**: Este caso de uso permite que um usuário (aluno ou servidor) cancele um agendamento de janta previamente feito no sistema de agendamento de refeições da escola. 

**Ator Principal**: Aluno ou Servidor 

**Ator Secundário**: Sistema de Agendamento de Refeições 

**Pré-condições**:
1.	O usuário deve ter um agendamento de janta existente.
2.	O sistema deve estar operacional.

**Pós-condições**:
1.	O agendamento de janta é cancelado no sistema.
2.	O sistema atualiza a contagem de refeições disponíveis para o dia.

**Fluxo Principal**:
1.	O usuário acessa o sistema de agendamento de refeições.
2.	O sistema exibe os agendamentos de janta existentes do usuário.
3.	O usuário seleciona a opção de cancelar um agendamento específico.
4.	O sistema solicita a confirmação do usuário para o cancelamento.
5.	O usuário confirma o cancelamento do agendamento.
6.	O sistema processa o cancelamento e atualiza a disponibilidade de refeições para o dia.
7.	O sistema notifica o usuário sobre o sucesso do cancelamento.

**Fluxos Alternativos**:
1.	Sem Agendamentos Existentes: Se o usuário não tiver agendamentos existentes, o sistema informa que não há agendamentos para cancelar e retorna ao menu principal.
2.	Sessão Expirada: Se a sessão do usuário expirar antes da confirmação do cancelamento, o sistema retorna à tela de login.
3.	Erro no Sistema: Se ocorrer um erro no sistema durante o cancelamento, uma mensagem de erro é exibida e o usuário é solicitado a tentar novamente mais tarde.
 
# Caso de Uso 07: Receber Notificações 

**Descrição**: Este caso de uso permite que os usuários (alunos ou servidores) recebam notificações automáticas do sistema de agendamento de refeições da escola sobre mudanças importantes, como alterações no cardápio, cancelamento de refeições ou lembretes de agendamento. 

**Ator Principal**: Aluno ou Servidor 

**Ator Secundário**: Sistema de Agendamento de Refeições 

**Pré-condições**:
1.	O usuário deve estar cadastrado e logado no sistema.
2.	O sistema deve estar operacional e configurado para enviar notificações.

**Pós-condições**:
1.	O usuário recebe notificações relevantes sobre o serviço de refeições.

**Fluxo Principal**:
1.	O usuário se inscreve para receber notificações durante o cadastro ou nas configurações de perfil.
2.	O sistema processa as preferências de notificação do usuário.
3.	Quando há uma mudança relevante (como alteração no cardápio ou cancelamento de refeição), o sistema gera uma notificação automática.
4.	O sistema envia a notificação para o usuário, que pode ser via e-mail, SMS ou notificação no aplicativo, dependendo das preferências definidas.
5.	O usuário recebe a notificação e fica informado sobre as mudanças ou lembretes importantes.

**Fluxos Alternativos**:
1.	Falha no Envio de Notificações: Se o sistema encontrar um erro ao enviar notificações (por exemplo, e-mail não entregue), ele registra a falha e pode tentar reenviar.
2.	Preferências de Notificação Não Definidas: Se o usuário não tiver definido preferências de notificação, o sistema pode enviar notificações por um canal padrão ou lembrar o usuário de definir suas preferências.
3.	Usuário Opta por Não Receber Notificações: Se o usuário optar por não receber notificações, o sistema respeita essa escolha e não envia notificações automáticas.
 
# Caso de Uso 08: Visualizar Cardápio Semanal

**Descrição**: Este caso de uso permite que os usuários (alunos ou servidores), administradores e membros da equipe da cozinha visualizem o cardápio semanal disponível no sistema de agendamento de refeições da escola. 

Atores Principais: Aluno ou Servidor, Administrador, Membro da Equipe da Cozinha 

**Ator Secundário**: Sistema de Agendamento de Refeições 

**Pré-condições**:
1.	O usuário deve estar cadastrado e logado no sistema.
2.	O sistema deve estar operacional e com o cardápio semanal atualizado. 

**Pós-condições**:
1.	O usuário visualiza as opções de refeições disponíveis para a semana.

**Fluxo Principal**:
1.	O usuário acessa o sistema de agendamento de refeições.
2.	O sistema apresenta a interface principal com várias opções, incluindo a visualização do cardápio semanal.
3.	O usuário seleciona a opção para visualizar o cardápio.
4.	O sistema exibe o cardápio semanal, mostrando as refeições disponíveis para cada dia da semana.
5.	O usuário consulta as opções de refeições e planeja seus agendamentos com base nas informações fornecidas.
6.	Após a consulta, o usuário pode optar por realizar um agendamento ou retornar à interface principal. 

**Fluxos Alternativos**:
1.	Cardápio Não Disponível: Se o cardápio da semana ainda não estiver disponível ou atualizado, o sistema informa o usuário e sugere que verifique novamente mais tarde.
2.	Sessão Expirada: Se a sessão do usuário expirar durante a visualização do cardápio, o sistema retorna à tela de login.
3.	Erro no Sistema: Se ocorrer um erro no sistema ao tentar acessar o cardápio, uma mensagem de erro é exibida e o usuário é aconselhado a tentar novamente mais tarde.
 
# Caso de Uso 09: Cadastrar Cardápio Semanal

**Descrição**: Este caso de uso permite que a equipe da cozinha ou os administradores cadastrem um novo cardápio semanal no sistema de agendamento de refeições da escola. 

**Ator Principal**: Membro da Equipe da Cozinha/Administrador 

**Ator Secundário**: Sistema de Agendamento de Refeições 

**Pré-condições**:
1.	O ator deve ter permissões de acesso para gerenciar o cardápio no sistema.
2.	O sistema deve estar operacional. 

**Pós-condições**:
1.	Um novo cardápio semanal é cadastrado no sistema. 

**Fluxo Principal**:
1.	O ator acessa o sistema de agendamento de refeições.
2.	O sistema apresenta a opção de cadastrar um novo cardápio semanal.
3.	O ator insere as informações do novo cardápio para os dias da semana.
4.	O sistema solicita a confirmação do cadastro.
5.	O ator confirma o cadastro do novo cardápio.
6.	O sistema processa e salva o novo cardápio.
7.	O sistema notifica o ator sobre o sucesso do cadastro. 

**Fluxos Alternativos**:
1.	Erro no Sistema: Se ocorrer um erro, o sistema exibe uma mensagem de erro.
2.	Dados Incompletos ou Inválidos: Se as informações fornecidas estiverem incompletas ou inválidas, o sistema solicita a correção ou complementação dos dados.

# Caso de Uso 10: Editar Cardápio Semanal

**Descrição**: Este caso de uso permite que a equipe da cozinha ou os administradores editem o cardápio semanal existente no sistema de agendamento de refeições da escola. 

**Ator Principal**: Membro da Equipe da Cozinha/Administrador 

**Ator Secundário**: Sistema de Agendamento de Refeições 

**Pré-condições**:
1.	O ator deve ter permissões de acesso para gerenciar o cardápio no sistema.
2.	O sistema deve estar operacional. 

**Pós-condições**:
1.	O cardápio semanal é atualizado no sistema. 
**Fluxo Principal**:
1.	O ator acessa o sistema de agendamento de refeições.
2.	O sistema apresenta a opção de editar o cardápio semanal existente.
3.	O ator modifica as informações do cardápio conforme necessário.
4.	O sistema solicita a confirmação das alterações.
5.	O ator confirma as alterações no cardápio.
6.	O sistema processa e salva as alterações.
7.	O sistema notifica o ator sobre o sucesso da atualização. 

**Fluxos Alternativos**:
1.	Erro na Atualização: Se ocorrer um erro, o sistema exibe uma mensagem de erro.
 
# Caso de Uso 11: Excluir Cardápio

**Descrição**: Este caso de uso permite que a equipe da cozinha ou os administradores excluam um cardápio semanal existente no sistema de agendamento de refeições da escola. 

**Ator Principal**: Membro da Equipe da Cozinha/Administrador 

**Ator Secundário**: Sistema de Agendamento de Refeições 

**Pré-condições**:
1.	O ator deve ter permissões de acesso para gerenciar o cardápio no sistema.
2.	O sistema deve estar operacional. 

**Pós-condições**:
1.	O cardápio semanal é removido do sistema. 

**Fluxo Principal**:
1.	O ator acessa o sistema de agendamento de refeições.
2.	O sistema apresenta a opção de excluir um cardápio semanal existente.
3.	O ator seleciona o cardápio a ser excluído.
4.	O sistema solicita a confirmação da exclusão.
5.	O ator confirma a exclusão do cardápio.
6.	O sistema processa e remove o cardápio.
7.	O sistema notifica o ator sobre o sucesso da exclusão. 

**Fluxos Alternativos**:
1.	Erro na Exclusão: Se ocorrer um erro, o sistema exibe uma mensagem de erro.

 
# Caso de Uso 12: Visualizar Relatório de Faltas 

**Descrição**: Este caso de uso permite que o administrador escolar visualize um relatório detalhado de todas as faltas registradas no sistema de agendamento de refeições da escola. 

**Ator Principal**: Administrador Escolar

**Ator Secundário**: Sistema de Agendamento de Refeições 

**Pré-condições**: 
1.	O administrador deve ter acesso ao sistema com permissões para visualizar relatórios de faltas.
2.	O sistema deve estar operacional. 

**Pós-condições**: 
1.	O administrador obtém um relatório detalhado das faltas. 

**Fluxo Principal**:
1.	O administrador acessa o sistema de agendamento de refeições.
2.	O sistema apresenta a opção de relatórios.
3.	O administrador seleciona a opção para visualizar o relatório de faltas.
4.	O sistema gera e exibe o relatório detalhado de faltas.
5.	O administrador analisa o relatório para monitorar a demanda e planejar recursos.
6.	O sistema oferece a opção de imprimir ou salvar o relatório.
7.	O administrador opta por imprimir ou salvar o relatório, ou retorna à interface principal. 

**Fluxos Alternativos**:
1.	Erro no Sistema: Se ocorrer um erro na geração do relatório, o sistema exibe uma mensagem de erro e oferece a opção de tentar novamente.
 
# Caso de Uso 13: Visualizar Relatório de Bloqueios

**Descrição**: Este caso de uso permite que o administrador escolar visualize um relatório detalhado de todos os bloqueios de usuários no sistema de agendamento de refeições da escola. 

**Ator Principal**: Administrador Escolar 

**Ator Secundário**: Sistema de Agendamento de Refeições 

**Pré-condições**: 
1.	O administrador deve ter acesso ao sistema com permissões para visualizar relatórios de bloqueios.
2.	O sistema deve estar operacional. 

**Pós-condições**: 
1.	O administrador obtém um relatório detalhado dos bloqueios. 

**Fluxo Principal**:
1.	O administrador acessa o sistema de agendamento de refeições.
2.	O sistema apresenta a opção de relatórios.
3.	O administrador seleciona a opção para visualizar o relatório de bloqueios.
4.	O sistema gera e exibe o relatório detalhado de bloqueios.
5.	O administrador analisa o relatório para entender os padrões de bloqueio e tomar decisões informadas.
6.	O sistema oferece a opção de imprimir ou salvar o relatório.
7.	O administrador opta por imprimir ou salvar o relatório, ou retorna à interface principal. 

**Fluxos Alternativos**:
1.	Erro no Sistema: Se ocorrer um erro na geração do relatório, o sistema exibe uma mensagem de erro e oferece a opção de tentar novamente.
 
# Caso de Uso 14: Visualizar Relatório de Agendamentos

**Descrição**: Este caso de uso permite que o administrador escolar visualize um relatório detalhado de todos os agendamentos de refeições no sistema de agendamento de refeições da escola. 

**Ator Principal**: Administrador Escolar 

**Ator Secundário**: Sistema de Agendamento de Refeições 

**Pré-condições**: 
1.	O administrador deve ter acesso ao sistema com permissões para visualizar relatórios de agendamentos.
2.	O sistema deve estar operacional. 

**Pós-condições**: 
1.	O administrador obtém um relatório detalhado dos agendamentos. 

**Fluxo Principal:**:
1.	O administrador acessa o sistema de agendamento de refeições.
2.	O sistema apresenta a opção de relatórios.
3.	O administrador seleciona a opção para visualizar o relatório de agendamentos.
4.	O sistema gera e exibe o relatório detalhado de agendamentos.
5.	O administrador analisa o relatório para monitorar a demanda e planejar recursos.
6.	O sistema oferece a opção de imprimir ou salvar o relatório.
7.	O administrador opta por imprimir ou salvar o relatório, ou retorna à interface principal. 

**Fluxos Alternativos:**:
1.	Erro no Sistema: Se ocorrer um erro na geração do relatório, o sistema exibe uma mensagem de erro e oferece a opção de tentar novamente.


