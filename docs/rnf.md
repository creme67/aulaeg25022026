## Requisitos Não Funcionais (RNF)

### RNF01 — Tempo de resposta
O sistema deve carregar telas principais em até **2 segundos**.

### RNF02 — Segurança
As senhas devem ser armazenadas usando hash seguro (ex.: bcrypt).

### RNF03 — Compatibilidade
O sistema deve funcionar nos navegadores Chrome, Edge e Firefox.

### RNF04 — Disponibilidade
O sistema deve estar disponível e operacional (uptime) durante 99,9% do tempo, considerando o período de 24/7.

### RNF05 — Responsividade
A interface do sistema deve ser adaptável a diferentes tamanhos de tela, garantindo uma boa experiência tanto em desktops quanto em dispositivos móveis (smartphones e tablets).

### RNF06 — Escalabilidade
O sistema deve ser capaz de suportar um aumento de até 500 usuários simultâneos sem perda de desempenho ou queda de conexão.

### RNF07 — Conformidade com a LGPD
O tratamento de dados pessoais dos usuários deve seguir rigorosamente as diretrizes da Lei Geral de Proteção de Dados (LGPD), incluindo a criptografia de dados sensíveis em repouso.

### RNF08 — Backup e Recuperação
O sistema deve realizar backups automáticos diários de todo o banco de dados. Em caso de falha crítica, o tempo de recuperação (RTO) não deve ultrapassar 4 horas.

### RNF09 — Usabilidade
O sistema deve ser intuitivo o suficiente para que um novo usuário consiga realizar as funções básicas (como o login e atualização de perfil) sem a necessidade de consultar um manual técnico.

### RNF10 — Manutenibilidade
O código-fonte deve seguir padrões de desenvolvimento consolidados (como Clean Code ou SOLID) e possuir documentação técnica para facilitar futuras atualizações e correções de bugs.

