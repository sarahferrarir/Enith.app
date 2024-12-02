## ⚡ **UC-03**:  Interação Social
### Objetivo: 
→ Permitir que os usuários se conectem e interajam no aplicativo, criando amizades e seguindo outros usuários para receber atualizações e conteúdo.

### Ator Principal:
→  Usuário

### Pré-condições:
- O usuário possui uma conta no aplicativo.

### Fluxo Principal:
- **Passo 1**: O usuário visualiza o perfil de outro usuário.
- **Passo 2**: O usuário pode optar por enviar uma solicitação de amizade ou seguir o outro usuário.
- **Passo 3**: Se o usuário escolher enviar uma solicitação de amizade:
    - **Passo 3.1**: Usuário seleciona o botão "Adicionar como amigo".
    - **Passo 3.2**: O sistema envia uma notificação ao outro usuário sobre a solicitação de amizade.
    - **Passo 3.4**: O sistema automaticamente registra o usuário como seguidor do outro usuário.
    - **Passo 3.3**: O outro usuário pode aceitar ou recusar a solicitação de amizade.
- **Passo 4**: Se o outro usuário aceitar a solicitação de amizade:
    - **Passo 4.1**: O sistema registra o outro usuário como amigo do usuário.
    - **Passo 4.2**: O sistema automaticamente registra o outro usuário como seguidor do usuário.
    - **Passo 4.3**: O sistema notifica o Usuário sobre o nova amizade.
- **Passo 5**: Se o usuário escolher seguir o outro usuário:
    - **Passo 5.1**: Usuário seleciona o botão "Seguir".
    - **Passo 5.2**: O sistema registra o usuário como seguidor do outro usuário.
    - **Passo 5.3**: O usuário passa a receber atualizações do outro usuário em seu feed.
    - **Passo 5.4**: O sistema notifica outro Usuário sobre o novo seguidor.

### Pós-condições:
- Se a solicitação de amizade foi aceita, o usuário e o outro usuário são amigos e se seguem mutuamente.
- Se a solicitação de amizade foi recusada. o usuário segue o outro usuário.
- Se o usuário escolheu seguir o outro usuário, o usuário segue o outro usuário.


### Fluxo Alternativo:
- Se o usuário já estiver conectado ao outro usuário como amigo ou seguidor:
    - O sistema exibe uma mensagem informando que o usuário já está conectado.

### Exceções:
- Erro de conexão com o servidor.

### Observações:
- O aplicativo deve permitir que os usuários desfaçam a amizade ou deixem de seguir outros usuários.
- O sistema deve notificar o usuário sobre novas solicitações de amizade e novas pessoas que passaram a segui-lo.
- O aplicativo deve oferecer opções de privacidade para os usuários, como a possibilidade de bloquear outros usuários.
- Ao enviar uma solicitação de amizade, o usuário automaticamente segue o outro usuário, e ao aceitar a solicitação, ambos se seguem mutuamente.