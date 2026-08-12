# README.md

# Engenharia de Requisitos Aplicada com Apoio de GenAI

## Ferramenta de GenAI Utilizada

Para a execução desta atividade foi utilizada a ferramenta **Microsoft 365 Copilot (baseada em modelos GPT)** como apoio à análise de requisitos, identificação de lacunas de especificação, elaboração de artefatos e refinamento da documentação produzida.

A GenAI foi utilizada como ferramenta de suporte à engenharia de requisitos, não substituindo a análise crítica do aluno nem as decisões de engenharia tomadas ao longo da atividade.

---

## Como a IA apoiou as diferentes etapas da atividade

### 1. Análise das informações levantadas
A IA apoiou a interpretação das informações obtidas durante a etapa de elicitação, identificando:

- Requisitos funcionais;
- Requisitos não funcionais;
- Regras de negócio;
- Ambiguidades;
- Inconsistências;
- Lacunas de informação.

### 2. Organização dos requisitos
A ferramenta auxiliou na estruturação dos requisitos em artefatos separados, facilitando a rastreabilidade e a compreensão do sistema.

### 3. Identificação de riscos de especificação
Foram identificadas informações não definidas pelos stakeholders, tais como:

- critérios de reembolso;
- prazo de cancelamento;
- funcionamento da lista de espera;
- critérios para emissão de certificados;
- tratamento de conflitos de agenda.

### 4. Complementação dos requisitos não funcionais
A IA também foi utilizada para propor requisitos não funcionais que não haviam sido levantados durante a elicitação inicial.

### 5. Apoio na seleção dos artefatos
Foram avaliados diferentes artefatos de engenharia de requisitos considerando valor agregado, esforço de produção e adequação ao contexto do projeto.

---

## Sugestões aceitas

### Complementação dos Requisitos Não Funcionais

A principal sugestão aceita foi a elaboração de um conjunto completo de requisitos não funcionais.

Inicialmente o documento de elicitação informava que não haviam sido levantados requisitos relacionados a:

- segurança;
- desempenho;
- disponibilidade;
- acessibilidade;
- privacidade.

Ao invés de tratar esta lacuna apenas de forma acadêmica, optou-se por uma abordagem mais próxima de um projeto real.

Foram então definidos requisitos objetivos para:

- autenticação e controle de acesso;
- criptografia de comunicação;
- conformidade com LGPD;
- disponibilidade mínima do sistema;
- desempenho e tempo de resposta;
- escalabilidade;
- acessibilidade;
- monitoramento;
- auditoria;
- backup e recuperação de falhas.

Essa decisão tornou a especificação mais aderente a um cenário real de desenvolvimento de software.

### Aplicação do princípio de Pareto (80/20)

Também foi aceita a recomendação de selecionar apenas os artefatos com maior retorno em relação ao esforço investido.

---

## Sugestões descartadas ou modificadas

### Utilização de um SRS completo

Inicialmente foi sugerida a elaboração de um SRS (Software Requirements Specification).

Entretanto, após a consolidação dos requisitos funcionais, requisitos não funcionais, regras de negócio e ambiguidades em documentos independentes, observou-se que o SRS passaria a reproduzir grande parte das informações já documentadas.

Por esse motivo, o SRS foi considerado redundante para os objetivos do trabalho.

### Inclusão de diagramas complexos

Foram avaliados artefatos como:

- diagramas de classes;
- BPMN detalhado;
- diagramas de sequência;
- documentação arquitetural.

Esses artefatos foram descartados por exigirem maior esforço e agregarem pouco valor para os objetivos específicos da atividade.

### Substituição do SRS por Product Backlog

No lugar do SRS foi adotado um Product Backlog contendo:

- épicos;
- user stories;
- critérios de aceite.

Essa substituição gerou um artefato mais prático, mais alinhado com abordagens ágeis e menos redundante.

---

## Justificativa dos artefatos escolhidos

Os artefatos selecionados foram:

1. Requisitos Funcionais;
2. Requisitos Não Funcionais;
3. Regras de Negócio;
4. Ambiguidades e Pendências;
5. Casos de Uso;
6. Wireframes;
7. Product Backlog.

A escolha foi baseada no princípio de Pareto (80/20), buscando maximizar o valor entregue e minimizar o esforço de produção.

### Requisitos Funcionais
Descrevem o comportamento esperado do sistema.

### Requisitos Não Funcionais
Estabelecem critérios de qualidade e restrições técnicas.

### Regras de Negócio
Documentam decisões e políticas operacionais do negócio.

### Ambiguidades e Pendências
Evidenciam riscos e necessidades de refinamento junto aos stakeholders.

### Casos de Uso
Representam os principais fluxos de interação dos usuários com o sistema.

### Wireframes
Facilitam a validação das funcionalidades e da experiência do usuário.

### Product Backlog
Traduz os requisitos para uma visão orientada à implementação e planejamento ágil.

---

## Conclusão

A utilização da GenAI permitiu acelerar a análise dos requisitos, identificar lacunas importantes e apoiar a produção dos artefatos necessários para a especificação do sistema.

A seleção dos artefatos foi guiada pelo princípio 80/20, priorizando documentos capazes de representar a maior parte do conhecimento do sistema com o menor esforço possível. Dessa forma, obteve-se um conjunto enxuto, consistente e aderente tanto aos objetivos acadêmicos da disciplina quanto às práticas utilizadas em projetos reais de desenvolvimento de software.
