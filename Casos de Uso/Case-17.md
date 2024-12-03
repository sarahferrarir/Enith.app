## ⚡ **Caso de Uso UC-17**: Registro de Sentimentos e Dificuldades em Tarefas

### Objetivo:  
→ Permitir que o usuário associe sentimentos e dificuldades às tarefas realizadas, como parte do acompanhamento do progresso pessoal.  

### Ator Principal:  
→ Usuário  

### Pré-condições:  
- O usuário deve ter concluído ou interagido com uma tarefa cadastrada.  

### Fluxo Principal:  
1. O usuário conclui ou marca uma tarefa como realizada.  
2. O sistema exibe um formulário para o usuário registrar seus sentimentos (ex.: "feliz", "ansioso") e dificuldades enfrentadas (ex.: "distração", "falta de tempo").  
3. O usuário preenche o formulário e confirma o registro.  
4. O sistema salva os dados e os associa à tarefa concluída.  

### Pós-condições:  
- Os sentimentos e dificuldades do usuário ficam registrados para consulta futura.  

### Fluxo Alternativo:  
- Caso o usuário opte por não registrar sentimentos ou dificuldades:
  - O sistema marca a tarefa como concluída sem coletar informações adicionais.  

### Exceções:  
- Erro de conexão ao tentar salvar os registros.