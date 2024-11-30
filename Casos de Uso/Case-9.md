## ⚡ **8º Caso de Uso**:  Personalizar Template Pré-Definido

### Objetivo: 
→ O sistema permite que o usuário personalize um template previamente adicionado ao seu perfil, ajustando os campos configuráveis de acordo com suas necessidades.

### Ator Principal:
→  Usuário

### Pré-condições:
- O usuário deve ter adicionado o template ao seu perfil anteriormente.

### Fluxo Principal:
- **Passo 1**: O usuário acessa a aba "Meus Templates" (ou equivalente) no sistema.
- **Passo 2**: O sistema exibe a lista de templates adicionados ao perfil do usuário.
- **Passo 3**: O usuário seleciona o template que deseja personalizar.
- **Passo 4**: O sistema exibe os detalhes do template, incluindo os campos configuráveis.
- **Passo 5**: O usuário clica na opção "Editar".
- **Passo 6**: O sistema abre o template em uma interface de edição.
- **Passo 7**: O usuário ajusta os campos configuráveis, como:
    - Nome da rotina
    - Passos ou tarefas
    - Horários ou frequência
    - Responsáveis ou tags associadas
- **Passo 8**: O usuário clica em "Salvar" para concluir a personalização.
- **Passo 9**: O sistema valida os dados inseridos e salva a rotina personalizada no perfil do usuário.

### Pós-condições:
- A rotina personalizada é salva no perfil do usuário com as alterações realizadas.
- A lista de templates do usuário é atualizada com a rotina personalizada.

### Fluxo Alternativo:
- Durante a edição, o usuário opta por cancelar a personalização.
    - O sistema descarta as alterações feitas e retorna à lista de templates.
- O sistema detecta campos inválidos ou ausentes.
    - O sistema destaca os campos com erros e exibe uma mensagem como: "Preencha todos os campos obrigatórios antes de salvar."
    - O usuário corrige os erros e tenta salvar novamente.
- O sistema detecta que já existe uma rotina personalizada com o mesmo nome no perfil do usuário.
    - O sistema exibe a mensagem: "Já existe uma rotina personalizada com este nome. Por favor, escolha outro nome."
    - O usuário altera o nome e tenta salvar novamente.


### Exceções:
- Erro de conexão com o servidor.
- Falha na comunicação com o banco de dados.
- Falha ao Salvar Rotina Personalizada.
- Template Não Encontrado.

### Observações:
- As alterações são salvas apenas após o usuário clicar em "Salvar".
- As altereções são salvas apenas no perfil do usuário.