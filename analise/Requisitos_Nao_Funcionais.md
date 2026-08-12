# Requisitos Não Funcionais – Sistema de Gestão de Eventos

## RNF-01 – Segurança e Controle de Acesso
O sistema deve exigir autenticação para acesso às funcionalidades restritas.

## RNF-02 – Perfis de Usuário
O sistema deve possuir perfis distintos de acesso para Participantes, Organizadores, Equipe Financeira, Palestrantes e Administradores.

## RNF-03 – Proteção de Senhas
As senhas dos usuários devem ser armazenadas utilizando algoritmos de hash seguros e criptografados.

## RNF-04 – Criptografia de Dados
Toda comunicação entre cliente e servidor deve utilizar protocolo HTTPS/TLS.

## RNF-05 – Conformidade com LGPD
O sistema deve coletar, armazenar e tratar os dados pessoais em conformidade com a Lei Geral de Proteção de Dados (LGPD).

## RNF-06 – Disponibilidade
O sistema deverá possuir disponibilidade mínima de 99,5% ao mês, excetuando janelas programadas de manutenção.

## RNF-07 – Recuperação de Falhas
O sistema deve possuir mecanismos de backup diário e recuperação de desastres.

## RNF-08 – Desempenho de Navegação
O tempo médio de carregamento das páginas não deve ultrapassar 3 segundos para 95% das transações.

## RNF-09 – Processamento de Inscrição
O sistema deve concluir uma solicitação de inscrição em até 5 segundos em condições normais de operação.

## RNF-10 – Atualização em Tempo Real
As informações de vagas e inscrições devem ser atualizadas em até 30 segundos após uma alteração.

## RNF-11 – Escalabilidade
O sistema deve suportar simultaneamente pelo menos 2.000 usuários conectados durante períodos de pico.

## RNF-12 – Usabilidade
As funcionalidades principais devem estar acessíveis em no máximo 3 cliques a partir da página inicial.

## RNF-13 – Responsividade
O sistema deve funcionar adequadamente em computadores, tablets e smartphones.

## RNF-14 – Acessibilidade
O sistema deve atender às recomendações WCAG 2.1 nível AA.

## RNF-15 – Compatibilidade
O sistema deve ser compatível com as duas versões mais recentes dos navegadores Chrome, Edge, Firefox e Safari.

## RNF-16 – Auditabilidade
O sistema deve registrar logs de operações críticas, incluindo inscrições, cancelamentos, pagamentos e reembolsos.

## RNF-17 – Rastreabilidade
Todas as alterações realizadas por usuários administrativos devem ser rastreáveis por data, hora e responsável.

## RNF-18 – Integração com Serviços de E-mail
O sistema deve ser capaz de enviar comprovantes, notificações e certificados eletrônicos automaticamente.

## RNF-19 – Manutenibilidade
O sistema deve possuir documentação técnica e APIs documentadas para facilitar manutenção e evolução.

## RNF-20 – Monitoramento
O ambiente deve possuir monitoramento contínuo de disponibilidade, desempenho e erros de aplicação.
