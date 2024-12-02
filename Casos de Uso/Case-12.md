## ⚡ **UC-12**: Editar Rotinas
### Objetivo:
→ Permitir que o usuário edite rotinas previamente criadas.

### Ator Principal:
→ Usuário do sistema

### Pré-condições:
- O usuário está autenticado no sistema.
- A rotina já foi criada e está disponível no sistema.

### Fluxo Principal:
- **Passo 1**: O usuário acessa a lista de rotinas.
- **Passo 2**: O usuário seleciona a rotina que deseja editar.
- **Passo 3**: O sistema exibe os detalhes da rotina em um formulário.
- **Passo 4**: O usuário edita as informações desejadas.
- **Passo 5**: O sistema valida as alterações realizadas.
- **Passo 6**: O usuário confirma as alterações.
- **Passo 7**: O sistema atualiza a rotina com as novas informações e retorna o usuário para a lista de rotinas.

### Pós-condições:
- A rotina é atualizada com as alterações realizadas.

### Fluxo Alternativo:
- Se o usuário cancelar a edição:
    - As alterações não são salvas, e a rotina permanece como estava.
- Se o usuário inserir dados inválidos:
    - O sistema exibe uma mensagem de erro e solicita correções.

### Exceções:
- Erro de conexão ao salvar as alterações.