## ⚡ **10º Caso de Uso**:  Realizar Busca por Rotinas, Usuários e Templates de Rotina
### Objetivo: 
→ permitir que o usuário realize buscas por rotinas, templates e usuários no sistema utilizando palavras-chave, facilitando a localização de informações relevantes.

### Ator Principal:
→  Usuário

### Pré-condições:
- O sistema deve ter rotinas, usuários e templates cadastrados e disponíveis para busca.

### Fluxo Principal:
- **Passo 1**: O usuário acessa a aba "Pesquisa" no sistema.
- **Passo 2**:O sistema exibe a barra de pesquisa, onde o usuário pode inserir uma ou mais palavras-chave.
- **Passo 3**: O usuário digita uma ou mais palavras-chave na barra de pesquisa e clica no botão "Buscar" ou pressiona Enter.
- **Passo 4**: O sistema processa a consulta e realiza buscas nos seguintes itens:
    - Rotinas personalizadas do usuário: Busca por rotinas que o usuário tenha criado ou adicionado.
    - Templates de rotinas: Busca por templates pré-definidos disponíveis no sistema.
    - Usuários: Busca por usuários registrados no sistema que correspondam às palavras-chave (por nome, email ou outro identificador).
- **Passo 5**: O sistema exibe os resultados organizados em três categorias:
    - Rotinas: Exibe rotinas personalizadas que atendem à busca.
    - Templates: Exibe templates de rotinas que correspondem às palavras-chave.
    - Usuários: Exibe a lista de usuários que atendem à busca.
- **Passo 6**: O usuário pode clicar em qualquer item nos resultados para visualizar mais detalhes.
- **Passo 7**: O sistema exibe os detalhes do item selecionado, seja ele uma rotina, template ou usuário.

### Pós-condições:
- O sistema retorna uma lista de resultados de rotinas, templates e usuários correspondentes às palavras-chave fornecidas.
- O usuário pode visualizar os detalhes dos itens encontrados, como nome, descrição e outros dados relevantes.

### Fluxo Alternativo:
- O sistema não encontra nenhum resultado relevante para a palavra-chave.
    - O sistema exibe a mensagem: "Nenhum resultado encontrado para sua pesquisa. Tente novas palavras-chave."
- O usuário deseja refinar a pesquisa, inserindo palavras-chave mais específicas ou utilizando filtros adicionais.
    - O sistema permite que o usuário refine a busca aplicando filtros por categorias ou tags.
- O sistema pode fornecer sugestões em tempo real enquanto o usuário digita as palavras-chave na barra de pesquisa (opcional).
    - O usuário pode clicar diretamente nas sugestões para realizar a busca.

### Exceções:
- Erro de conexão com o servidor.
- Falha na Busca
- Busca com Termo Inválido

### Observações:
- O sistema pode permitir que o usuário refine a pesquisa utilizando filtros como categoria.
- A barra de pesquisa deve permitir a possibilidade de autocompletar ou sugerir termos de busca.
- Apenas dados públicos de usuários devem ser acessíveis na busca. Informações sensíveis, como dados pessoais ou informações privadas, devem ser ocultadas, conforme as permissões de acesso.
