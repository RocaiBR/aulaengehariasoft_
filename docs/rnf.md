 Requisitos Não Funcionais (RNF)

### RNF01 — Tempo de resposta
O sistema deve carregar telas principais em até **2 segundos**.

### RNF02 — Segurança
As senhas devem ser armazenadas usando hash seguro (ex.: bcrypt).

### RNF03 — Compatibilidade
O sistema deve funcionar nos navegadores Chrome, Edge e Firefox.

### RNF04 — Disponibilidade
O sistema deve garantir um tempo de atividade (uptime) mínimo de 99,9% mensalmente, não contando manutenções programadas.

### RNF05 — Escalabilidade
A infraestrutura do sistema deve ser capaz de suportar até 1.000 usuários simultâneos sem degradação do tempo de resposta definido no RNF01.

### RNF06 — Responsividade
A interface da aplicação web deve se adaptar adequadamente a diferentes tamanhos de tela, incluindo desktops, tablets e smartphones (Mobile First).

### RNF07 — Conformidade legal (LGPD)
O sistema deve estar em total conformidade com a Lei Geral de Proteção de Dados (LGPD), garantindo a gestão adequada de consentimento e proteção de dados sensíveis.

### RNF08 — Rotina de Backup
O banco de dados deve possuir uma rotina de backup automatizada a cada 24 horas, com retenção segura dos dados por no mínimo 30 dias.

### RNF09 — Manutenibilidade do código
O código-fonte do repositório deve estar documentado e seguir padrões de código limpo (Clean Code) para facilitar futuras integrações e manutenções pela equipe.
