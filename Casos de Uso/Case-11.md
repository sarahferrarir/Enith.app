## ⚡ **UC-11**: Criar Rotinas
### Objetivo:
→ Permitir que o usuário crie novas rotinas do zero, de maneira intuitiva e personalizada.

### Ator Principal:
→ Usuário do sistema

### Pré-condições:
- O usuário está autenticado no sistema.

### Fluxo Principal:
- **Passo 1**: O usuário acessa a tela de criação de rotinas.
- **Passo 2**: O sistema exibe um formulário para o usuário configurar os detalhes da rotina, incluindo:
    - Nome da rotina.
    - Horários e frequência.
    - Tarefas associadas à rotina.
- **Passo 3**: O usuário preenche os campos do formulário com as informações desejadas.
- **Passo 4**: O sistema valida as informações inseridas.
- **Passo 5**: O usuário confirma a criação da rotina.
- **Passo 6**: O sistema salva a nova rotina e a exibe na lista de rotinas do usuário.

### Pós-condições:
- A rotina é criada e armazenada no sistema, ficando disponível para consulta e edição.

### Fluxo Alternativo:
- Se o usuário não preencher campos obrigatórios:
    - O sistema exibe uma mensagem de erro destacando os campos pendentes.

### Exceções:
- Erro de conexão ao salvar a rotina.
- Dados inválidos no formulário.