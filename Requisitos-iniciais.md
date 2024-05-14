## 🎈Requisitos em Linguagem Natural
- RN-01: Os usuários devem poder criar uma conta, fazer login, enviar e aceitar solicitações de amizade, seguir outros usuários, ver uma lista de seus amigos e seguidores, e interagir com as postagens através de curtidas e comentário.
- RN-02: O aplicativo deve oferecer modelos de rotina que os usuários podem personalizar para criar suas próprias rotinas. 
- RN-03: Os usuários devem poder definir a visibilidade de suas rotinas, criar, editar e excluir rotinas personalizadas, e publicar suas rotinas.
- RN-04: O aplicativo deve exibir um feed de notícias com as postagens de todos os usuários, dos usuários seguidos pelo usuário atual e dos amigos do usuário.
- RN-05: O aplicativo deve permitir que os usuários pesquisem rotinas, usuários ou modelos de rotina usando palavras-chave.
- RN-06: O aplicativo deve funcionar offline e enviar lembretes ou notificações para os usuários com base no horário das tarefas em suas rotinas.
- RN-06: O aplicativo deve fornecer análises e insights sobre a produtividade do usuário.
- RN-07: O aplicativo deve ser fácil de usar, com uma interface de usuário intuitiva e uma experiência de usuário agradável.
- RN-08: Os usuários devem poder registrar detalhes sobre sua saúde física, como peso, altura, idade, e outros parâmetros relevantes.
- RN-09: O aplicativo deve permitir que os usuários rastreiem seu progresso em metas de saúde e fitness ao longo do tempo, fornecendo gráficos e estatísticas visuais.
- RN-10: Os usuários devem poder criar e gerenciar listas de tarefas diárias ou semanais, com a capacidade de marcar tarefas como concluídas e definir lembretes para tarefas futuras.
- RN-11: O aplicativo deve permitir que os usuários registrem o que comeram ao longo do dia. Os usuários devem poder adicionar detalhes sobre cada item alimentar, incluindo nome, quantidade, e informações nutricionais, como calorias, proteínas, gorduras, carboidratos, vitaminas, e minerais. O aplicativo deve calcular automaticamente o total de calorias e outros valores nutricionais com base nos itens registrados.
- RN-12: Os usuários devem poder registrar seu consumo de água diário e acompanhar sua ingestão de líquidos ao longo do dia.
- RN-13: O aplicativo deve fornecer recursos de monitoramento do sono, permitindo que os usuários registrem a qualidade e a duração de seu sono, além de receber sugestões para melhorar seus hábitos de sono.
- RN-14: Os usuários devem poder exportar e fazer backup de seus dados pessoais, garantindo a portabilidade e segurança de suas informações.
- RN-15: O aplicativo deve permitir que os usuários adicionem entradas de texto sobre cada tarefa e meta definida para o dia, registrando o que sentiram ao cumprir aquele objetivo, quais foram as dificuldades encontradas, e quaisquer outras observações relevantes.
- RN-16: Os usuários devem poder associar fotos às suas tarefas e metas pré-estabelecidas, fornecendo uma maneira visual de registrar e documentar o progresso e os resultados alcançados.
- RN-17: O aplicativo deve oferecer opções de privacidade para as entradas relacionadas à rotina diária, permitindo que os usuários decidam se desejam manter suas informações privadas, compartilhá-las com amigos selecionados ou torná-las públicas.
- RN-18: Os usuários devem poder categorizar suas entradas relacionadas à rotina diária com tags ou etiquetas personalizadas para facilitar a organização e a busca.
- RN-19: O aplicativo deve fornecer recursos de análise e insights sobre a rotina diária do usuário, incluindo estatísticas sobre a conclusão de tarefas, o cumprimento de metas e o progresso ao longo do tempo.
- RN-20: Os usuários devem poder revisitar e refletir sobre sua rotina diária por meio de uma visualização cronológica ou calendário, que mostra as tarefas concluídas, as metas alcançadas e as experiências associadas a cada dia.
- RN-21: O aplicativo deve incluir recursos de edição para as entradas relacionadas à rotina diária, permitindo que os usuários façam correções, adições ou exclusões conforme necessário;
- RN-22: Os usuários devem poder exportar suas entradas relacionadas à rotina diária em formato de arquivo para backup ou compartilhamento externo;
- RN-23: Os usuários devem poder criar tarefas e objetivos compartilhados com seus amigos, onde ambos têm uma responsabilidade mútua de cumprir a tarefa em conjunto. O usuário que cria a tarefa pode definir sua frequência (diária ou semanal) e convidar seus amigos para participarem. Uma vez aceito o convite, os amigos podem visualizar e acompanhar o progresso da tarefa compartilhada, recebendo notificações sobre atualizações e contribuindo para sua conclusão. Essa funcionalidade promove a colaboração entre os usuários, incentivando o apoio mútuo e a consecução de objetivos comuns.

## 🛠 Requisitos Técnicos

### Funcionais
- RF-01:  O aplicativo deve permitir que os usuários se registrem e façam login usando um endereço de e-mail ou através de plataformas de mídia social.
- RF-02:  O aplicativo deve oferecer templates de rotina pré-definidos que os usuários podem usar como ponto de partida para criar suas próprias rotinas. Os usuários devem ser capazes de personalizar esses templates de acordo com suas necessidades.
- RF-03: O aplicativo deve exibir um feed de notícias que mostra as publicações de todos os usuários.
- RF-04: O aplicativo deve exibir um feed de notícias que mostra as publicações dos usuários que ele segue.
- RF-05: O aplicativo deve exibir um feed de notícias que mostra as publicações dos usuários que são amigos dele.
- RF-06: Os usuários devem ser capazes de enviar e receber solicitações de amizade, seguir outros usuários, e ver uma lista de seus amigos e seguidores.
- RF-07: Os usuários devem ser capazes de seguir outros usuários, curtir, comentar as postagens de rotina.
- RF-08: O aplicativo deve permitir que os usuários pesquisem por outras rotinas, usuários ou templates de rotina usando palavras-chave.
- RF-09: Os usuários devem ser capazes de definir suas rotinas como públicas, privadas ou visíveis apenas para certos usuários.
- RF-10: Os usuários devem ser capazes de criar, editar e excluir rotinas personalizadas. As rotinas podem incluir várias tarefas, cada uma com seu próprio horário.
- RF-11: Os usuários devem ser capazes de publicar sua rotina, que podem incluir texto, fotos, vídeos e links. Eles também devem ser capazes de editar ou excluir suas próprias publicações.
- RF-12: O aplicativo deve funcionar offline, permitindo que os usuários visualizem e editem suas rotinas mesmo sem conexão à internet.
- RF-13: O aplicativo deve enviar lembretes ou notificações para os usuários com base no horário das tarefas em suas rotinas.
- RF-14: O aplicativo deve fornecer análises e insights sobre a produtividade do usuário, como tarefas concluídas, tempo gasto em cada tarefa, etc.
- RF-15: Implementar funcionalidades de diário, onde os usuários podem registrar eventos diários, sentimentos e pensamentos. Eles devem poder associar fotos a essas entradas de diário.
- RF-16: Desenvolver recursos de planejamento de refeições, permitindo que os usuários registrem suas refeições diárias, incluindo detalhes nutricionais como calorias, proteínas, carboidratos, etc.
- RF-17: Integrar um sistema de monitoramento de atividades físicas, onde os usuários podem registrar os exercícios realizados, duração e intensidade, além de acompanhar seu progresso ao longo do tempo.
- RF-18: Implementar funcionalidades de planejamento de metas e tarefas diárias, onde os usuários podem definir objetivos e acompanhar seu progresso. Eles devem poder associar sentimentos e dificuldades enfrentadas ao realizar essas tarefas.
- RF-19: Implementar um sistema de armazenamento de dados escalável e resiliente para lidar com o aumento do volume de usuários e informações.
- RF-20: Integrar serviços de análise de dados para gerar insights sobre o uso da plataforma, padrões de comportamento dos usuários e melhorias potenciais na experiência do usuário.
- RF-20: Desenvolver recursos de sincronização em tempo real para garantir que as atualizações feitas em um dispositivo sejam refletidas imediatamente em outros dispositivos associados à mesma conta de usuário.
- RF-21: Implementar técnicas de cache para otimizar o desempenho e reduzir o tempo de carregamento, especialmente para recursos frequentemente acessados, como feeds de notícias e calendários.
- RF-22: Utilizar tecnologias de compressão de imagem para reduzir o tamanho das fotos enviadas pelos usuários, minimizando o consumo de largura de banda e o tempo de carregamento.
- RF-23: Integrar ferramentas de monitoramento de desempenho para acompanhar a utilização de recursos do servidor, identificar gargalos de desempenho e realizar ajustes conforme necessário.
- RF-24: Desenvolver um sistema de convites e permissões que permita aos usuários criar tarefas compartilhadas e convidar amigos para participarem. Isso inclui a criação de uma interface de usuário intuitiva para criar e gerenciar tarefas compartilhadas, bem como a implementação de lógica de permissões para garantir que apenas os participantes autorizados possam visualizar e contribuir para as tarefas compartilhadas. Além disso, o sistema deve ser capaz de enviar notificações aos participantes sobre atualizações e lembretes relacionados às tarefas compartilhadas.

### Não Funcionais
- RNF-01: Utilização de tecnologia Framework;
- RNF-03: Garantir a compatibilidade multiplataforma, garantindo que o aplicativo funcione de maneira consistente em diferentes dispositivos móveis (iOS e Android).
- RNF-04: Implementar testes de usabilidade e conduzir testes beta com usuários reais para garantir uma experiência de usuário otimizada.
- RNF-05: Garantir que o aplicativo seja leve e responsivo, mesmo em dispositivos móveis com recursos limitados de hardware.
- RNF-06: Utilizar boas práticas de segurança da informação para proteger os dados dos usuários, como criptografia de dados em repouso e em trânsito, além de garantir conformidade com regulamentações de privacidade, como GDPR e LGPD.
- RNF-07: Garantir alta disponibilidade e tolerância a falhas, implementando estratégias de redundância e failover para minimizar o tempo de inatividade e manter a continuidade do serviço.
- RNF-08: Realizar testes de segurança regulares e análises de vulnerabilidades para identificar e corrigir potenciais brechas de segurança na aplicação.
- RNF-09: Adotar práticas de desenvolvimento ágil e integração contínua para garantir entregas frequentes e atualizações de software sem interrupções significativas para os usuários.

    → ***React Native***
- RNF-02: O aplicativo deve ser fácil de usar, com uma interface intuitiva e uma experiência de usuário agradável.

