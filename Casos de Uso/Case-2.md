## ⚡ **UC-02**: Login de Usuário
### Objetivo: 
→ Permitir que usuários existentes acessem o aplicativo, utilizando um endereço de e-mail e senha ou uma plataforma de mídia social, de forma segura e eficiente

### Ator Principal:
→ Usuário

### Pré-condições:
- O usuário possui uma conta no aplicativo.

### Fluxo Principal:
- **Passo 1**: O usuário acessa a tela de login.
- **Passo 2**: O usuário pode escolher entre fazer login usando um endereço de e-mail ou através de uma plataforma de mídia social.
- **Passo 3**: Se o usuário escolher o login por e-mail:
    - **Passo 3.1**: O usuário insere seu endereço de e-mail e senha.
    - **Passo 3.2**: O sistema valida os dados inseridos.
    - **Passo 3.3**: O sistema verifica se o usuário existe e se a senha está correta.
    - **Passo 3.4**: Se os dados estiverem corretos, o sistema autentica o usuário.
    - **Passo 3.5**: O usuário é redirecionado para a tela inicial do aplicativo.

- **Passo 4**: Se o usuário escolher o login por plataforma de mídia social:
    - **Passo 4.1**: O usuário seleciona a plataforma de mídia social desejada (ex: Google).
    - **Passo 4.2**: O sistema redireciona o usuário para a plataforma de mídia social escolhida.
    - **Passo 4.3**: O usuário autoriza o aplicativo a acessar suas informações da plataforma de mídia social.
    - **Passo 4.4**: O sistema autentica o usuário utilizando as informações da plataforma de mídia social.
    - **Passo 4.5**: O usuário é redirecionado para a tela inicial do aplicativo.

### Pós-condições:
- O usuário está autenticado no aplicativo.

### Fluxo Alternativo:
- Se o usuário inserir dados inválidos:
    - O sistema exibe uma mensagem de erro informando o problema.
- Se o usuário não existir ou a senha estiver incorreta:
    - O sistema exibe uma mensagem de erro informando que as credenciais estão incorretas.
- Se o usuário não autorizar o aplicativo a acessar suas informações da plataforma de mídia social:
    - O processo de login é cancelado.

### Exceções:
- Erro de conexão com o servidor.
- Erro de conexão com a plataforma de mídia social.

### Observações:
- O aplicativo deve oferecer opções de recuperação de senha para usuários que esqueçam suas senhas.
- O sistema deve garantir a segurança das informações dos usuários durante o processo de login.
- O aplicativo deve permitir que os usuários façam logout a qualquer momento.