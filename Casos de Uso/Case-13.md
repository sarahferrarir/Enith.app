## ⚡ **UC-13**: Excluir Rotinas
### Objetivo:
→ Permitir que o usuário exclua rotinas que não sejam mais necessárias.

### Ator Principal:
→ Usuário do sistema

### Pré-condições:
- O usuário está autenticado no sistema.
- A rotina já foi criada e está disponível no sistema.

### Fluxo Principal:
- **Passo 1**: O usuário acessa a lista de rotinas.
- **Passo 2**: O usuário seleciona a rotina que deseja excluir.
- **Passo 3**: O sistema exibe uma mensagem de confirmação de exclusão.
- **Passo 4**: O usuário confirma a exclusão.
- **Passo 5**: O sistema remove a rotina da lista de rotinas do usuário.

### Pós-condições:
- A rotina é excluída permanentemente do sistema.

### Fluxo Alternativo:
- Se o usuário cancelar a exclusão:
    - A rotina permanece no sistema sem alterações.

### Exceções:
- Erro de conexão ao tentar excluir a rotina.

### Observações:
- O sistema deve exibir mensagens de confirmação e sucesso para garantir que o usuário esteja ciente das ações realizadas.
- As rotinas excluídas não devem ser recuperáveis.