## ⚡ **8º Caso de Uso**:  Disponibilizar Templates Pré-definidos

### Objetivo: 
→ Permitir que o usuário visualize e utilize templates de rotinas pré-definidas.

### Ator Principal:
→  Usuário

### Pré-condições:
- Templates de rotinas pré-definidas devem estar cadastrados no sistema.

### Fluxo Principal:
- **Passo 1**: O usuário acessa a aba Pesquisa no sistema.
- **Passo 2**: O sistema exibe uma lista de todos os templates de rotinas pré-definidas disponíveis.
    - **Passo 2.1**: Regra de Exibição: A lista deve incluir o nome do template, uma breve descrição e, opcionalmente, tags ou categorias.
- **Passo 3**: O usuário utiliza filtros ou busca para localizar templates específicos (opcional).
- **Passo 4**: O usuário seleciona um template de rotina.
- **Passo 5**:O sistema exibe os detalhes completos do template, incluindo:
    - Nome
    - Descrição detalhada
    - Passos ou tarefas incluídas na rotina
    - Campos configuráveis (exemplo: horários, frequência, responsáveis).
- **Passo 6**: O usuário clica na opção "Adicionar".
- **Passo 7**: O sistema valida a inclusão e adiciona o template ao perfil do usuário.

### Pós-condições:
- O template adicionado fica associado ao perfil do usuário.
- O template fica disponivel para ser personalizado.
- A rotina pré-definida fica acessível para uso futuro.


### Fluxo Alternativo:
- Se não houver templates cadastrados:
    - Exibe uma mensagem informando que não há templates disponíveis no momento.
- Se o usuário decide não adicionar o template, ele pode retornar para a lista de templates sem realizar ações.
- Se o usuário aplica filtros ou realiza uma busca que não retorna resultados, o sistema exibe: "Nenhum resultado encontrado para os critérios selecionados."
    - O usuário pode ajustar os filtros ou redefinir a busca.

### Exceções:
- Erro de conexão com o servidor.
- Falha na comunicação com o banco de dados.
- Template inválido ou indisponível.
- Falha ao adicionar template.
- Nome duplicado ao salvar Template.

### Observações:
- Os templates pré-definidos são protegidos e não podem ser modificados ou excluídos diretamente pelos usuários, garantindo a integridade do sistema.
- A funcionalidade de busca deve ser sensível a palavras-chave e oferecer sugestões baseadas em categorias ou tags, facilitando a localização de templates relevantes.