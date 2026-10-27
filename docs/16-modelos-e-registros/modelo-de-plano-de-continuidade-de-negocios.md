# Modelo de Plano de Continuidade de Negócios para Serviços de TI e Segurança da Informação

## 1. Objetivo

Este documento apresenta um modelo para estruturar um Plano de Continuidade de Negócios (PCN), com foco na manutenção ou retomada das atividades prioritárias diante de interrupções que afetem serviços, processos, pessoas, instalações, informações ou recursos tecnológicos.

O plano deve orientar a preparação, a tomada de decisão, a ativação de alternativas operacionais, a comunicação e a recuperação das atividades essenciais.

Sua aplicação deve considerar o contexto organizacional, os riscos, as dependências operacionais e os objetivos de continuidade definidos pela organização.

**Importante:** este documento é um modelo de referência. Sua publicação não comprova que uma organização tenha um plano aprovado, recursos de contingência disponíveis ou capacidade de continuidade efetivamente testada.

## 2. Escopo e aplicabilidade

O plano deve identificar os processos e serviços abrangidos, suas dependências e os critérios para ativação.

**Organização:** [Nome da organização]

**Processos abrangidos:** [Relacionar processos]

**Serviços de TI abrangidos:** [Relacionar serviços]

**Unidades ou localidades abrangidas:** [Relacionar unidades]

**Responsável pelo plano:** [Função ou área]

**Aprovador:** [Função ou autoridade competente]

**Versão:** [Número]

**Data de aprovação:** [AAAA-MM-DD]

As exclusões de escopo devem ser justificadas e avaliadas quanto aos impactos que possam produzir sobre as atividades abrangidas.

## 3. Referências e documentos relacionados

Considerar, conforme aplicabilidade:

- ISO/IEC 27001:2022 — requisitos relacionados ao planejamento, à operação e à melhoria do SGSI.
- ISO/IEC 27001:2022 — controles do Anexo A pertinentes à preparação de TIC para continuidade de negócios e à segurança da informação durante interrupções.
- Política de Segurança da Informação.
- Metodologia de gestão de riscos.
- Plano de resposta a incidentes de segurança da informação.
- Plano de recuperação de desastres de TI.
- Procedimentos de cópia de segurança e restauração.
- Contratos e acordos de nível de serviço de fornecedores críticos.
- Procedimentos de gestão de crises e comunicação.

Este modelo não substitui uma análise de impacto nos negócios, a avaliação de riscos nem os requisitos de continuidade que sejam aplicáveis à organização.

## 4. Conceitos fundamentais

**Continuidade de negócios:** capacidade da organização de manter ou retomar atividades prioritárias em níveis previamente definidos após uma interrupção.

**Análise de Impacto nos Negócios (BIA):** processo de avaliação das consequências da interrupção de atividades e da identificação de prioridades e necessidades de recuperação.

**Tempo Objetivo de Recuperação (RTO):** período-alvo definido para restabelecer uma atividade ou serviço após uma interrupção.

**Ponto Objetivo de Recuperação (RPO):** ponto no tempo até o qual os dados devem ser recuperados, representando a perda de dados temporalmente tolerável definida para a atividade.

**Plano de Recuperação de Desastres (PRD):** conjunto de procedimentos voltados à recuperação de ambientes, sistemas e infraestrutura tecnológica após uma interrupção grave.

**Modo degradado:** forma alternativa de operação que permite manter atividades prioritárias com capacidade reduzida.

Os objetivos de recuperação devem ser estabelecidos a partir das necessidades de negócio e das capacidades reais dos recursos envolvidos. Não devem ser definidos apenas com base em expectativas técnicas sem validação dos responsáveis pelos processos.

## 5. Governança e responsabilidades

| Papel ou função | Responsabilidades |
|---|---|
| Alta direção | Aprovar diretrizes e decisões que exijam autoridade executiva. |
| Coordenador de continuidade | Coordenar a ativação e o acompanhamento do plano. |
| Gestores de processos | Definir prioridades e validar condições para retomada das atividades. |
| Equipe de TI | Recuperar sistemas, infraestrutura, aplicações e serviços tecnológicos. |
| Responsável pelo SGSI | Avaliar riscos de segurança da informação e impactos sobre os controles. |
| Gestão de pessoas | Apoiar a comunicação e a organização das equipes, conforme necessário. |
| Jurídico ou conformidade | Avaliar obrigações legais, regulatórias e contratuais. |
| Comunicação institucional | Coordenar comunicações autorizadas. |
| Fornecedores críticos | Executar as responsabilidades previstas nos contratos e planos acordados. |

A organização deve definir titulares, substitutos, limites de autoridade e mecanismos de acionamento para situações em que os responsáveis habituais não estejam disponíveis.

## 6. Análise de Impacto nos Negócios

A BIA deve identificar atividades prioritárias, impactos da interrupção e necessidades de recuperação.

### 6.1 Registro das atividades críticas

| Processo ou atividade | Responsável | Impacto da interrupção | Prioridade | Dependências principais |
|---|---|---|---|---|
| [Atividade] | [Responsável] | [Descrição] | [Classificação] | [Dependências] |
| [Atividade] | [Responsável] | [Descrição] | [Classificação] | [Dependências] |

A avaliação pode considerar impactos financeiros, operacionais, legais, regulatórios, contratuais, reputacionais e sobre clientes ou usuários.

### 6.2 Evolução dos impactos

| Tempo de interrupção | Impacto esperado | Consequência para o negócio | Limite ou marco de decisão |
|---|---|---|---|
| [Período inicial] | [Descrição] | [Descrição] | [Critério] |
| [Período intermediário] | [Descrição] | [Descrição] | [Critério] |
| [Período prolongado] | [Descrição] | [Descrição] | [Critério] |

Os períodos devem ser definidos conforme as características reais de cada atividade. Não utilizar valores genéricos como se fossem objetivos aprovados pela organização.

## 7. Objetivos de recuperação

| Processo ou serviço | RTO aprovado | RPO aprovado | Nível mínimo de operação | Responsável pela validação |
|---|---|---|---|---|
| [Serviço] | [Tempo] | [Tempo] | [Capacidade mínima] | [Responsável] |
| [Serviço] | [Tempo] | [Tempo] | [Capacidade mínima] | [Responsável] |

O RTO e o RPO devem ser documentados com suas premissas e aprovados pelos responsáveis competentes.

A organização deve verificar se a arquitetura, os contratos, as cópias de segurança e os procedimentos de recuperação permitem atender aos objetivos estabelecidos.

Se houver diferença entre a necessidade do negócio e a capacidade técnica, registrar a lacuna, o risco associado e as ações planejadas.

## 8. Dependências críticas

| Dependência | Tipo | Atividades dependentes | Alternativa disponível | Responsável |
|---|---|---|---|---|
| [Sistema ou serviço] | [Tecnologia / Pessoas / Fornecedor / Instalação] | [Atividades] | [Alternativa] | [Responsável] |
| [Recurso] | [Categoria] | [Atividades] | [Alternativa] | [Responsável] |

Avaliar, conforme aplicabilidade:

- Pessoas e conhecimentos essenciais.
- Sistemas, aplicações e infraestrutura.
- Identidades, credenciais e mecanismos de autenticação.
- Conectividade e comunicação.
- Instalações e energia.
- Fornecedores e serviços terceirizados.
- Dados e cópias de segurança.
- Equipamentos e recursos de trabalho alternativos.
- Serviços compartilhados e integrações.

As dependências devem ser avaliadas também quanto a pontos únicos de falha e à possibilidade de falhas simultâneas.

## 9. Cenários de interrupção

O plano deve considerar cenários relevantes para o contexto da organização.

| Cenário | Impacto potencial | Estratégia de continuidade | Plano relacionado |
|---|---|---|---|
| Indisponibilidade de sistema crítico | Interrupção de atividade prioritária | [Estratégia] | [Referência] |
| Falha de infraestrutura ou conectividade | Perda de acesso a serviços | [Estratégia] | [Referência] |
| Incidente cibernético relevante | Comprometimento de sistemas ou informações | [Estratégia] | [Referência] |
| Indisponibilidade de fornecedor crítico | Interrupção de serviço terceirizado | [Estratégia] | [Referência] |
| Indisponibilidade de instalação | Restrição de acesso às equipes | [Estratégia] | [Referência] |
| Indisponibilidade de pessoas-chave | Redução da capacidade operacional | [Estratégia] | [Referência] |

Os cenários são exemplos para análise, não uma lista exaustiva nem evidência de que os riscos tenham sido avaliados.

## 10. Critérios de ativação

A ativação do plano deve seguir critérios objetivos e autoridades previamente definidas.

Possíveis gatilhos:

- Interrupção de atividade crítica além do limite definido.
- Previsão de que o RTO não será atendido.
- Indisponibilidade simultânea de recursos essenciais.
- Incidente que exija operação alternativa.
- Indisponibilidade prolongada de fornecedor crítico.
- Decisão formal de gestão de crise.

**Autoridade para ativação:** [Função]

**Substituto autorizado:** [Função]

**Canal de acionamento:** [Canal controlado]

**Informações mínimas para decisão:** [Definir]

**Registro da decisão:** [Local ou sistema]

A ativação deve ser registrada, incluindo horário, justificativa, responsável, escopo e recursos mobilizados.

## 11. Estratégias de continuidade

As estratégias devem ser escolhidas com base na BIA, na avaliação de riscos, na viabilidade técnica e nos recursos disponíveis.

Exemplos:

- Operação temporária em modo degradado.
- Utilização de infraestrutura alternativa.
- Redirecionamento para recursos redundantes.
- Procedimentos manuais temporários.
- Trabalho remoto ou uso de instalações alternativas, quando viável.
- Acionamento de fornecedor alternativo.
- Priorização de serviços e atividades.
- Restauração a partir de cópias de segurança.
- Uso de recursos de comunicação alternativos.

Para cada estratégia, documentar:

- Atividades e serviços atendidos.
- Condições de ativação.
- Recursos necessários.
- Responsáveis.
- Limitações conhecidas.
- Riscos associados.
- Critérios para retorno à operação normal.

## 12. Procedimentos de ativação e execução

### 12.1 Avaliação inicial

1. Confirmar a ocorrência e as informações disponíveis.
2. Identificar as atividades e os recursos afetados.
3. Avaliar impactos e estimativa de duração.
4. Determinar a necessidade de ativação.
5. Registrar a decisão e acionar os responsáveis.

### 12.2 Mobilização

1. Acionar as equipes e os substitutos definidos.
2. Estabelecer canal de coordenação.
3. Confirmar a disponibilidade de recursos e contatos.
4. Definir prioridades e responsáveis por cada frente.
5. Comunicar as partes interessadas conforme os critérios aprovados.

### 12.3 Operação alternativa

1. Ativar as estratégias aprovadas.
2. Validar os requisitos mínimos de segurança.
3. Confirmar a capacidade de execução das atividades prioritárias.
4. Monitorar impactos e riscos adicionais.
5. Registrar limitações, decisões e mudanças de prioridade.

### 12.4 Recuperação e retorno

1. Confirmar a disponibilidade dos recursos recuperados.
2. Validar integridade, segurança e funcionamento.
3. Obter aprovação dos responsáveis pelos serviços e processos.
4. Planejar a transição da operação alternativa.
5. Comunicar o retorno à operação normal.
6. Manter acompanhamento após a retomada.

Os procedimentos detalhados e os contatos operacionais devem ser mantidos em documentos controlados, com acesso adequado.

## 13. Segurança da informação durante a continuidade

As medidas de continuidade não devem introduzir riscos desnecessários à segurança da informação.

Durante a operação alternativa, avaliar:

- Controle de acesso e autenticação.
- Proteção de informações em trânsito e em armazenamento.
- Uso de dispositivos e ambientes autorizados.
- Gestão de privilégios emergenciais.
- Registro de atividades relevantes.
- Proteção de cópias de segurança.
- Tratamento e descarte de informações temporárias.
- Riscos introduzidos por procedimentos manuais.
- Segurança dos fornecedores e recursos alternativos.

Qualquer flexibilização emergencial de controles deve ser autorizada, limitada, registrada e revista assim que possível.

## 14. Comunicação de continuidade

| Público | Informação necessária | Responsável | Canal alternativo | Critério de comunicação |
|---|---|---|---|---|
| Equipes internas | Orientações operacionais e prioridades | [Responsável] | [Canal] | [Critério] |
| Gestores | Impactos, decisões e previsão de recuperação | [Responsável] | [Canal] | [Critério] |
| Clientes ou usuários | Impactos e orientações aplicáveis | [Responsável] | [Canal] | [Critério] |
| Fornecedores | Solicitações e coordenação de recuperação | [Responsável] | [Canal] | [Critério] |
| Autoridades ou órgãos competentes | Informações exigidas, quando aplicável | [Responsável autorizado] | [Canal] | [Critério] |

A comunicação deve ser coordenada e consistente, protegendo informações confidenciais e observando as obrigações legais, regulatórias e contratuais aplicáveis.

## 15. Recursos e fornecedores

| Recurso ou fornecedor | Finalidade | Disponibilidade necessária | Contato controlado | Alternativa |
|---|---|---|---|---|
| [Recurso] | [Finalidade] | [Necessidade] | [Referência] | [Alternativa] |
| [Fornecedor] | [Serviço] | [Necessidade] | [Referência] | [Alternativa] |

A organização deve avaliar a dependência de fornecedores críticos, as condições contratuais, os compromissos de recuperação e os mecanismos de escalonamento.

Informações sensíveis de contato, acesso e configuração devem ser mantidas em local restrito, e não necessariamente no repositório público do projeto.

## 16. Testes e exercícios

O plano deve ser validado por meio de exercícios adequados ao risco, à complexidade e aos recursos disponíveis.

Exemplos:

- Revisão de contatos e responsabilidades.
- Exercício de mesa baseado em cenário de interrupção.
- Teste controlado de recuperação de serviço.
- Restauração de cópia de segurança em ambiente apropriado.
- Simulação de indisponibilidade de fornecedor.
- Exercício de comunicação e escalonamento.
- Teste de operação alternativa.

Cada exercício deve registrar objetivo, escopo, participantes, premissas, resultados, limitações e ações de melhoria.

Testes que possam afetar serviços produtivos devem ser previamente autorizados e planejados para evitar impactos indevidos.

## 17. Registro dos testes

| Campo | Preenchimento |
|---|---|
| Identificador do exercício | [ID] |
| Data | [AAAA-MM-DD] |
| Cenário | [Descrição] |
| Objetivo | [Objetivo] |
| Participantes | [Funções ou equipes] |
| Resultado esperado | [Critério] |
| Resultado observado | [Resultado] |
| RTO/RPO atendidos? | [Sim / Não / Não aplicável] |
| Lacunas identificadas | [Descrição] |
| Ações de melhoria | [Referências] |
| Responsável pelo relatório | [Responsável] |

Os resultados devem ser utilizados para atualizar o plano, corrigir lacunas e reavaliar a capacidade de recuperação.

## 18. Indicadores possíveis

A organização pode definir indicadores como:

- Percentual de atividades críticas com estratégias de continuidade documentadas.
- Percentual de planos testados no período.
- Percentual de testes com critérios atendidos.
- Percentual de ações corretivas concluídas no prazo.
- Tempo real de recuperação comparado ao RTO.
- Ponto real de recuperação comparado ao RPO.
- Disponibilidade de contatos e recursos críticos.
- Quantidade de lacunas relevantes identificadas em exercícios.

Cada indicador deve possuir definição, fonte de dados, responsável, periodicidade e critério de avaliação.

## 19. Encerramento da ativação

O encerramento da ativação deve ocorrer quando as condições definidas para o retorno à operação normal forem atendidas ou quando houver decisão formal fundamentada.

Registrar:

- Data e hora do encerramento.
- Autoridade responsável pela decisão.
- Situação dos serviços e processos.
- Pendências remanescentes.
- Riscos residuais.
- Necessidade de monitoramento adicional.
- Lições aprendidas.
- Ações de melhoria e responsáveis.

O encerramento da ativação não elimina automaticamente as pendências de recuperação ou as ações corretivas que ainda precisem ser acompanhadas.

## 20. Revisão e manutenção do plano

O plano deve ser revisado periodicamente e após mudanças relevantes, tais como:

- Alterações em processos críticos.
- Mudanças tecnológicas ou de infraestrutura.
- Alterações no escopo do SGSI.
- Mudanças significativas nos riscos.
- Modificações em fornecedores críticos.
- Resultados de testes e exercícios.
- Incidentes reais e interrupções relevantes.
- Mudanças legais, regulatórias ou contratuais.

**Responsável pela manutenção:** [Função]

**Periodicidade de revisão:** [Definir]

**Local oficial de publicação:** [Referência controlada]

**Data da última revisão:** [AAAA-MM-DD]

## 21. Checklist de validação

- [ ] O escopo e os processos críticos estão identificados.
- [ ] A BIA foi realizada e validada pelos responsáveis.
- [ ] Os objetivos de recuperação foram aprovados.
- [ ] As dependências críticas estão documentadas.
- [ ] Os critérios de ativação e encerramento estão definidos.
- [ ] As responsabilidades e os substitutos estão identificados.
- [ ] As estratégias de continuidade foram avaliadas.
- [ ] Os requisitos de segurança da informação foram considerados.
- [ ] Os canais de comunicação alternativos estão definidos.
- [ ] As interfaces com resposta a incidentes e recuperação de desastres estão claras.
- [ ] Os testes e exercícios foram planejados.
- [ ] As ações de melhoria possuem responsáveis e prazos.
- [ ] A aprovação e a revisão periódica estão definidas.

## 22. Limitações e orientações de uso

Este modelo deve ser adaptado ao contexto real da organização, validado pelos responsáveis pelos processos e aprovado conforme a governança estabelecida.

A existência do documento não comprova que os objetivos de recuperação sejam viáveis, que os recursos estejam disponíveis ou que os procedimentos tenham sido testados com sucesso.

Os exemplos são ilustrativos. A definição de estratégias, prioridades, RTO, RPO e critérios de ativação exige análise das necessidades de negócio, avaliação de riscos e validação das capacidades técnicas e operacionais.

## 23. Histórico de revisão

| Versão | Data | Descrição da alteração | Responsável |
|---|---|---|---|
| 1.0 | [AAAA-MM-DD] | Criação do modelo para adaptação | [Responsável] |
