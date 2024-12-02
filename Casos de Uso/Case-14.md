## ⚡ **UC-14: Envio de Lembretes e Notificações**

### Objetivo: 
→ Notificar os usuários sobre suas tarefas com base nos horários definidos, garantindo que as atividades sejam realizadas no prazo.

### Ator Principal:
→ Usuário

### Pré-condições:
- O usuário possui uma conta no sistema.
- O usuário definiu horários para suas tarefas nas rotinas.

### Fluxo Principal:
- **Passo 1**: O sistema verifica as tarefas do usuário para o dia atual.
- **Passo 2**: O sistema identifica as tarefas com horários definidos.
- **Passo 3**: O sistema envia lembretes ou notificações ao usuário no horário correspondente a cada tarefa.
- **Passo 4**: O usuário recebe a notificação em seu dispositivo.

### Pós-condições:
- O usuário é notificado no horário correto sobre suas tarefas.

### Fluxo Alternativo:
- Se o dispositivo do usuário estiver offline:
    - O sistema armazena a notificação localmente e tenta enviá-la quando o dispositivo estiver online novamente.
- Se o horário da tarefa já passou:
    - O sistema envia um lembrete atrasado ou exibe uma notificação de tarefa pendente.

### Exceções:
- Falha no envio de notificações devido a problemas de conectividade.
- Configurações do dispositivo impedem o recebimento de notificações.

### Observações:
- As notificações devem incluir lembretes sobre metas próximas ao vencimento