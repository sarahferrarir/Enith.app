## ⚡ **Caso de Uso UC-18**: Gerenciamento de Tarefas com o Modelo Pomodoro

### Objetivo:  
→ Permitir que o usuário utilize o modelo Pomodoro para gerenciar tarefas, com sessões de trabalho de 25 minutos, intervalos curtos de 5 minutos e intervalos longos após quatro sessões.  

### Ator Principal:  
→ Usuário  

### Pré-condições:  
- O usuário deve ter uma tarefa cadastrada no sistema.  

### Fluxo Principal:  
1. O usuário seleciona uma tarefa e inicia o modo Pomodoro.  
2. O sistema inicia um cronômetro de 25 minutos.  
3. Após 25 minutos, o sistema notifica o usuário sobre o término da sessão de trabalho e inicia um intervalo curto de 5 minutos.  
4. O usuário é notificado ao término do intervalo curto.  
5. O sistema alterna entre sessões de trabalho e intervalos curtos até completar quatro ciclos.  
6. Após o quarto ciclo, o sistema inicia um intervalo longo (ex.: 15 ou 30 minutos).  

### Pós-condições:  
- A tarefa é marcada como em progresso ou concluída ao término das sessões Pomodoro.  

### Fluxo Alternativo:  
- Caso o usuário pause ou interrompa o cronômetro:
  - O sistema registra o tempo acumulado e aguarda a retomada.  

### Exceções:  
- O cronômetro é reiniciado caso o dispositivo ou sistema seja reiniciado inesperadamente.  

### Observações:  
- O sistema deve permitir que o usuário ajuste a duração das sessões e intervalos.  