## ⚡ **UC-04**: Criação e Gerenciamento de Tarefas
### Objetivo: 
→ Permitir que os usuários criem e gerenciem listas de tarefas diárias ou semanais, com a capacidade de marcar tarefas como concluídas e definir lembretes para tarefas futuras.

### Ator Principal:
→ Usuário Ativo

### Pré-condições:
- O usuário já possui uma conta no aplicativo.

### Fluxo Principal:
- **Passo 1**: O usuário acessa a área de “Tarefas” no aplicativo.
- **Passo 2**: O usuário cria uma nova tarefa:
    - **Passo 2.1**: O usuário insere um título e uma descrição da tarefa.
    - **Passo 2.2**: O usuário define uma data para a tarefa, ou, caso seja uma tarefa repetida:
        - **Passo 2.2.1**: O usuário define a frequência da tarefa, como mensa, semanal, díaria, de dois em dois dias, etc
    - **Passo 2.3**: O usuário escolhe como receber notificações referentes à essa tarefa:
        - **Passo 2.3.1**: O usuário define a frequência dos lembretes, tanto como os horários que deseja recebê-los.
    - **Passo 2.4**: O sistema salva a nova tarefa e exibe a lista de todas as tarefas para o dia ou semana.
- **Passo 3**: O usuário marca a tarefa como concluída após completá-la.
- **Passo 4**: O sistema atualiza o status da tarefa e move-a para a seção de "Concluídas".

### Pós-condições:
- O usuário possui uma lista gerenciada de tarefas, com lembretes e a possibilidade de marcar tarefas como concluídas.

### Fluxo Alternativo:
- Se o usuário não definir lembretes:
    - O sistema salva a tarefa sem lembretes.

### Exceções:
- Falha ao criar tarefa por erro de conexão com o servidor.

### Observações:
- O sistema deve permitir a reabertura de tarefas marcadas como concluídas, caso o usuário deseje revisitar ou ajustar algo.
