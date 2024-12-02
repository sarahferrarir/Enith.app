## ⚡ **UC-01**: Registro de Usuário
### Objetivo: 
→ Permitir que novos usuários criem contas no aplicativo, utilizando um endereço de e-mail ou uma plataforma de mídia social, de forma segura e eficiente.

### Ator Principal:
→ Novo Usuário

### Pré-condições:
- O usuário não possui um conta no aplicativo

### Fluxo Principal:
- **Passo 1**: O usuário acessa a tela de registro.
- **Passo 2**: O usuário pode escolher entre registrar-se usando um endereço de e-mail ou através de uma plataforma de mídia social.
- **Passo 3**: Se o usuário escolher o registro por e-mail:
    - **Passo 3.1**: O usuário insere seu endereço de e-mail, nome de usuário, senha e confirma a senha.
    - **Passo 3.2**: O sistema valida os dados inseridos.
    - **Passo 3.3**: O sistema envia um email de verificação para o endereço de e-mail do usuário.
    - **Passo 3.4**: O usuário clica no link de verificação no email.
    - **Passo 3.5**: O sistema cria a conta do usuário.
    - **Passo 3.6**: O usuário é redirecionado para a tela inicial do aplicativo.

- **Passo 4**: Se o usuário escolher o registro por plataforma de mídia social:
    - **Passo 4.1**: O usuário seleciona a plataforma de mídia social desejada (ex: Google).
    - **Passo 4.2**: O sistema redireciona o usuário para a plataforma de mídia social escolhida.
    - **Passo 4.3**: O usuário autoriza o aplicativo a acessar suas informações da plataforma de mídia social.
    - **Passo 4.4**: O sistema cria a conta do usuário utilizando as informações da plataforma de mídia social.
    - **Passo 4.5**: O usuário é redirecionado para a tela inicial do aplicativo.

### Pós-condições:
- O usuário possui uma conta no aplicativo.

### Fluxo Alternativo:
- Se o usuário inserir dados inválidos:
    - O sistema exibe uma mensagem de erro informando o problema.
- Se o usuário não clicar no link de verificação do email:
    - A conta não é criada.
- Se o usuário não autorizar o aplicativo a acessar suas informações da plataforma de mídia social:
    - O processo de registro é cancelado.

### Exceções:
- Erro de conexão com o servidor de email.
- Erro de conexão com a plataforma de mídia social.
- Endereço de e-mail já utilizado.

### Observações:
- O aplicativo deve oferecer opções de recuperação de senha para usuários que esqueçam suas senhas.
- O sistema deve garantir a segurança das informações dos usuários durante o processo de registro.
- O aplicativo deve permitir que os usuários excluam suas contas a qualquer momento.