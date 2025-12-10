# Proposta Inicial de Migração para AWS
Empresa: Lincoln Farmacêutica
Responsável: Douglas
Objetivo: Demonstrar como a adoção de serviços cloud pode reduzir custos e melhorar a eficiência operacional da empresa.
________________________________________
📌 ## Contexto da Empresa
A Lincoln é uma distribuidora farmacêutica que se conecta a várias empresas e farmácias, funcionando como um hub logístico. Atualmente, não existe infraestrutura em nuvem, o que aumenta custos com servidores físicos, manutenção, energia, suporte técnico e limita a escalabilidade.
O objetivo deste relatório é apresentar três serviços da AWS que oferecem redução de custos direta e ganhos operacionais imediatos, adequados ao perfil da Lincoln.
________________________________________
🔧 ## 1. Amazon S3 (Simple Storage Service)
O que é
Um serviço de armazenamento na nuvem extremamente seguro, escalável e com pagamento apenas pelo que for utilizado.
Como reduz custos
•	Elimina a necessidade de servidores físicos e sistemas de backup on-premise.
•	Reduz o custo de armazenamento em até 70% quando comparado a estruturas tradicionais.
•	Remove gastos com manutenção, troca de hardware e expansão de capacidade.
•	Camadas de armazenamento permitem pagar menos para dados acessados raramente (ex.: relatórios históricos).
Ganho para a Lincoln
•	Armazenamento seguro de dados de estoque, relatórios fiscais, notas, integrações, e dados de parceiros.
•	Alta durabilidade (99,999999999%) garante confiabilidade para documentos sensíveis.
•	Permite integração rápida com outros sistemas, acelerando rotinas internas (pedidos, envios, rastreamento).
________________________________________
🖥️ ## 2. Amazon EC2 + Auto Scaling
O que é
Servidores virtuais flexíveis na nuvem, que crescem ou diminuem automaticamente conforme a demanda.
Como reduz custos
•	Paga apenas pelo tempo de uso da máquina — elimina o desperdício de infraestrutura ociosa.
•	Auto Scaling reduz máquinas automaticamente fora do horário comercial, cortando custos em até 50%.
•	Não há investimento inicial em hardware.
•	Permite usar instâncias spot, até 70% mais baratas que instâncias tradicionais.
Ganho para a Lincoln
•	Hospedagem eficiente para APIs, integrações com farmácias, sistemas internos e dashboards.
•	Evita indisponibilidades em horários de pico (ex.: fechamento de pedidos).
•	Reduz drasticamente custos com TI e elimina riscos de falhas físicas.
________________________________________
🗄️ ##  3. Amazon RDS (Relational Database Service)
O que é
Banco de dados gerenciado em nuvem (ex.: PostgreSQL, MySQL) com backups automáticos, alta disponibilidade e escalabilidade.
Como reduz custos
•	Acaba com servidores físicos de banco de dados, manutenção, licenças e profissionais especializados apenas para infraestrutura.
•	Backups são automáticos, eliminando ferramentas de terceiros.
•	Escalabilidade sob demanda evita pagar por capacidade não utilizada.
•	Pagamento 100% proporcional ao uso.
Ganho para a Lincoln
•	Banco de dados confiável para pedidos, estoque, rastreio logístico e integração com parceiros.
•	Menos risco de perda de dados.
•	Melhora o desempenho do sistema de pedidos e comunicação com farmácias.
•	Facilita auditoria e conformidade exigidas no setor farmacêutico.
________________________________________
📊 ##  Conclusão para o Gestor Financeiro
A implementação dos serviços Amazon S3, EC2 com Auto Scaling e Amazon RDS proporciona:
Benefício	Impacto Direto
Redução de custos de infraestrutura	Diminuem despesas em até 50–70% comparado ao modelo físico
Pagamento somente pelo uso	Elimina desperdício
Redução de riscos	Sem falhas físicas ou perda de dados
Escalabilidade imediata	Evita quedas em horários de pico
Menos necessidade de equipe operacional	AWS assume tarefas automáticas (backup, manutenção, segurança)
Com esses três pilares, a Lincoln terá uma base sólida para continuar crescendo sem aumentar proporcionalmente seus custos.

