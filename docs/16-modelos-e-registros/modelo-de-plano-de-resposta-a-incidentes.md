# Modelo de Plano de Resposta a Incidentes de Segurança da Informação

## 1. Objetivo

Este documento apresenta um modelo para estruturar o planejamento da resposta a incidentes de segurança da informação no contexto de um Sistema de Gestão de Segurança da Informação (SGSI).

O plano estabelece diretrizes para preparação, identificação, avaliação, contenção, erradicação, recuperação, comunicação e aprendizado após incidentes.

Seu propósito é orientar a coordenação das ações, definir responsabilidades e facilitar a tomada de decisão durante situações que possam comprometer a confidencialidade, a integridade ou a disponibilidade das informações.

Este documento é um modelo de referência. Sua publicação não comprova que uma organização possua um plano aprovado, equipes preparadas ou capacidade operacional de resposta.

## 2. Aplicabilidade

O plano deve ser adaptado ao contexto e ao escopo do SGSI, considerando:

- Sistemas, serviços, processos e informações abrangidos.
- Estrutura organizacional e responsabilidades.
- Dependências de fornecedores e prestadores de serviços.
- Critérios de classificação e escalonamento de incidentes.
- Requisitos legais, regulatórios e contratuais.
- Relação com continuidade de negócios e recuperação de desastres.
- Recursos técnicos, humanos e financeiros disponíveis.

**Organização:** [Nome da organização]

**Escopo abrangido:** [Descrição]

**Responsável pelo plano:** [Função ou área]

**Aprovador:** [Função ou autoridade competente]

**Data de aprovação:** [AAAA-MM-DD]

**Versão:** [Número da versão]

## 3. Referências e documentos relacionados

Considerar, conforme aplicabilidade:

- ISO/IEC 27001:2022 — requisitos do SGSI relacionados à operação, avaliação de desempenho e melhoria.
- ISO/IEC 27001:2022 — controles do Anexo A relacionados à preparação para incidentes, avaliação de eventos, resposta e aprendizado.
- ISO/IEC 27002 — orientações para implementação de controles de segurança da informação.
- Política de Segurança da Informação.
- Metodologia de gestão de riscos.
- Procedimento de registro e tratamento de incidentes.
- Plano de continuidade de negócios.
- Plano de recuperação de desastres.
- Procedimentos de gestão de crises e comunicação.
- Procedimentos de proteção de dados pessoais, quando aplicáveis.

A seleção dos controles e documentos deve considerar os riscos, o escopo e a Declaração de Aplicabilidade (SoA) da organização.

## 4. Princípios de resposta

A resposta aos incidentes deve observar os seguintes princípios:

1. **Proteção de pessoas e operações críticas:** priorizar a segurança das pessoas e a continuidade das atividades essenciais.
2. **Rapidez com controle:** agir de forma tempestiva, respeitando as autorizações e os procedimentos estabelecidos.
3. **Preservação de evidências:** manter a integridade e a rastreabilidade das informações relevantes para investigação.
4. **Proporcionalidade:** ajustar as ações à severidade, à abrangência e aos impactos identificados.
5. **Comunicação coordenada:** compartilhar informações com os destinatários apropriados, respeitando a necessidade de conhecimento.
6. **Registro das decisões:** documentar decisões relevantes, responsáveis, horários e justificativas.
7. **Aprendizado contínuo:** utilizar os resultados para aprimorar riscos, controles, processos e preparação.

## 5. Papéis e responsabilidades

| Papel ou função | Responsabilidades principais |
|---|---|
| Coordenador do incidente | Coordenar a resposta, acompanhar prioridades e consolidar decisões. |
| Equipe técnica | Investigar, conter, erradicar e recuperar os recursos afetados. |
| Responsável pelo SGSI | Avaliar impactos no SGSI, riscos, controles e necessidades de melhoria. |
| Gestor do serviço afetado | Avaliar impactos operacionais e apoiar a priorização da recuperação. |
| Alta direção | Tomar decisões que exijam autoridade executiva ou recursos extraordinários. |
| Jurídico ou área de conformidade | Avaliar implicações legais, regulatórias e contratuais. |
| Encarregado ou responsável por privacidade | Apoiar a avaliação de incidentes que envolvam dados pessoais, conforme a estrutura aplicável. |
| Comunicação institucional | Coordenar comunicações externas autorizadas, quando necessário. |
| Fornecedores envolvidos | Executar atividades previstas nos contratos e procedimentos acordados. |

Os nomes das funções, a composição das equipes e os níveis de autoridade devem ser definidos pela organização. Uma mesma pessoa pode exercer mais de um papel, desde que os conflitos de interesse e as limitações operacionais sejam avaliados.

## 6. Preparação para incidentes

Antes da ocorrência de incidentes, a organização deve definir e manter, conforme aplicabilidade:

- Processo de comunicação e acionamento.
- Critérios de identificação, classificação e escalonamento.
- Lista de contatos internos e externos.
- Responsáveis e substitutos.
- Ferramentas de monitoramento e investigação.
- Procedimentos de contenção e recuperação.
- Mecanismos de preservação de evidências.
- Recursos de comunicação alternativos.
- Acesso controlado a cópias de segurança e recursos de recuperação.
- Capacitação e exercícios de simulação.
- Dependências críticas e contatos de fornecedores.
- Critérios de ativação de continuidade de negócios ou gestão de crises.

Os contatos e detalhes operacionais sensíveis devem ser mantidos em local apropriado, com acesso restrito e revisão periódica.

## 7. Identificação e registro

Todo evento suspeito deve ser avaliado conforme o processo definido pela organização.

Quando houver critérios para classificá-lo como incidente, deve ser criado ou atualizado o registro correspondente.

Informações iniciais recomendadas:

- Identificador do incidente.
- Data e hora da detecção.
- Origem do alerta.
- Descrição preliminar.
- Sistemas, ativos ou informações potencialmente afetados.
- Responsável pelo registro.
- Classificação preliminar.
- Ações iniciais realizadas.
- Evidências ou referências disponíveis.

As informações iniciais podem estar incompletas. Hipóteses devem ser identificadas como tais e revisadas à medida que surgirem novas evidências.

## 8. Classificação e escalonamento

A organização deve estabelecer critérios objetivos para determinar a severidade e a prioridade dos incidentes.

Podem ser considerados:

- Impacto sobre a confidencialidade, integridade e disponibilidade.
- Quantidade e criticidade dos ativos afetados.
- Interrupção de serviços essenciais.
- Possível comprometimento de credenciais ou privilégios.
- Abrangência do incidente.
- Impactos financeiros, legais, regulatórios ou reputacionais.
- Possível envolvimento de dados pessoais.
- Capacidade de contenção e recuperação.

### 8.1 Matriz ilustrativa

A matriz abaixo é apenas um exemplo de estrutura. Os critérios, prazos e autoridades devem ser aprovados e ajustados pela organização.

| Severidade | Caracterização ilustrativa | Tratamento esperado |
|---|---|---|
| Crítica | Impacto grave ou ameaça relevante a serviços essenciais, informações críticas ou múltiplos ambientes. | Acionamento prioritário da coordenação e avaliação de escalonamento executivo. |
| Alta | Impacto significativo em sistemas, informações ou processos importantes. | Resposta prioritária e acompanhamento frequente. |
| Média | Impacto limitado, com necessidade de investigação e tratamento coordenado. | Tratamento conforme prioridade e prazo definidos. |
| Baixa | Ocorrência de baixo impacto, sem evidência de comprometimento relevante. | Registro, avaliação e tratamento conforme procedimento. |

A severidade inicial deve ser revista quando novas evidências alterarem a compreensão do impacto ou da abrangência.

## 9. Fluxo de resposta

O fluxo de resposta pode ser organizado nas seguintes etapas:

1. Identificação e registro.
2. Triagem e classificação.
3. Acionamento dos responsáveis.
4. Investigação inicial e delimitação do incidente.
5. Contenção.
6. Erradicação, quando aplicável.
7. Recuperação controlada.
8. Monitoramento após a recuperação.
9. Comunicação e avaliação de obrigações aplicáveis.
10. Encerramento e lições aprendidas.

As etapas podem ocorrer parcialmente em paralelo, conforme a natureza do incidente. A sequência efetiva deve preservar a segurança das pessoas, a integridade das evidências e a continuidade das operações críticas.

## 10. Contenção

A contenção busca limitar a propagação e reduzir os impactos do incidente.

Exemplos de ações possíveis, dependendo do cenário e das autorizações aplicáveis:

- Isolar um equipamento ou segmento de rede.
- Bloquear temporariamente uma conta comprometida.
- Revogar sessões ou credenciais suspeitas.
- Restringir acessos a recursos afetados.
- Desabilitar temporariamente uma integração.
- Aplicar regras emergenciais de proteção.
- Acionar fornecedores responsáveis por serviços críticos.

Cada ação deve considerar os riscos de interromper serviços legítimos, afetar evidências ou agravar o incidente.

**Responsável pela decisão de contenção:** [Função]

**Autoridade de aprovação emergencial:** [Função]

**Procedimento de registro das ações:** [Referência]

## 11. Investigação e preservação de evidências

A investigação deve buscar compreender a natureza, a origem provável, a abrangência e os impactos do incidente.

Conforme aplicabilidade, considerar:

- Registros de eventos e alertas.
- Atividades de contas e privilégios.
- Alterações de configuração.
- Comunicação entre sistemas.
- Integridade de arquivos e aplicações.
- Evidências fornecidas por ferramentas de segurança.
- Informações de fornecedores.
- Registros de decisões e ações realizadas.

A coleta e o armazenamento das evidências devem seguir procedimentos apropriados, com controle de acesso e rastreabilidade.

Não realizar alterações desnecessárias nos recursos afetados antes de avaliar a necessidade de preservar evidências. Quando houver investigação formal ou possível implicação jurídica, acionar as áreas competentes.

## 12. Erradicação

Após a contenção e a investigação suficiente para orientar a ação, a organização deve avaliar as medidas necessárias para eliminar a causa técnica ou a condição que permitiu o incidente.

Exemplos possíveis:

- Remover artefatos maliciosos.
- Corrigir vulnerabilidades exploradas.
- Corrigir configurações inseguras.
- Revogar ou substituir credenciais comprometidas.
- Atualizar sistemas e componentes vulneráveis.
- Eliminar acessos indevidos.
- Ajustar regras de segurança e monitoramento.

A erradicação deve ser validada antes da retomada plena dos serviços, sempre que a natureza do incidente exigir essa verificação.

## 13. Recuperação

A recuperação deve ocorrer de forma controlada, considerando a integridade dos recursos, a criticidade dos serviços e os critérios definidos pela organização.

Atividades possíveis:

- Restaurar dados a partir de cópias de segurança verificadas.
- Reconstruir sistemas afetados.
- Validar configurações e controles de segurança.
- Testar a integridade e o funcionamento dos serviços.
- Confirmar a autorização para retorno à operação.
- Acompanhar os sistemas após a retomada.
- Manter medidas temporárias de proteção enquanto persistirem riscos residuais.

**Critérios de recuperação:** [Definir]

**Responsável pela validação técnica:** [Função]

**Responsável pela autorização de retorno:** [Função]

**Plano de monitoramento pós-recuperação:** [Definir]

## 14. Comunicação durante o incidente

A comunicação deve ser coordenada e baseada em informações verificadas.

| Destinatário | Gatilho para comunicação | Responsável | Canal aprovado |
|---|---|---|---|
| Coordenação do incidente | [Critério] | [Função] | [Canal] |
| Alta direção | [Critério] | [Função] | [Canal] |
| Áreas operacionais afetadas | [Critério] | [Função] | [Canal] |
| Jurídico ou conformidade | [Critério] | [Função] | [Canal] |
| Responsável por privacidade | [Critério] | [Função] | [Canal] |
| Fornecedores envolvidos | [Critério] | [Função] | [Canal] |
| Clientes ou outras partes externas | [Critério e aprovação] | [Função] | [Canal] |

Devem ser estabelecidos critérios para comunicação externa, aprovação das mensagens e proteção de informações sensíveis.

A avaliação de notificações legais, regulatórias ou contratuais deve ser feita tempestivamente pelas pessoas competentes, considerando os fatos, os prazos e as obrigações aplicáveis.

## 15. Continuidade de negócios e recuperação de desastres

Quando o incidente afetar atividades críticas, a coordenação deve avaliar a necessidade de acionar os planos de continuidade de negócios ou de recuperação de desastres.

A decisão deve considerar:

- Criticidade dos serviços afetados.
- Tempo tolerável de interrupção definido pela organização.
- Dependências tecnológicas e operacionais.
- Capacidade de operação alternativa.
- Disponibilidade e integridade das cópias de segurança.
- Riscos associados às alternativas de recuperação.

O acionamento e o encerramento desses planos devem ser registrados, incluindo os responsáveis pelas decisões.

## 16. Encerramento do incidente

O incidente poderá ser encerrado conforme critérios definidos pela organização, após avaliação das condições de contenção, recuperação, comunicação e acompanhamento.

O encerramento deve considerar:

- Situação dos ativos e serviços afetados.
- Evidências disponíveis e lacunas remanescentes.
- Impactos identificados.
- Obrigações de comunicação avaliadas.
- Riscos residuais.
- Ações pendentes e seus responsáveis.
- Necessidade de monitoramento adicional.
- Necessidade de abertura de registro de não conformidade ou ação corretiva.

A conclusão administrativa não significa necessariamente que todos os riscos foram eliminados. Pendências devem permanecer registradas e ser acompanhadas até a conclusão ou aceitação formal do risco pela autoridade competente.

## 17. Lições aprendidas e melhoria

Após o tratamento, a organização deve avaliar a resposta e identificar oportunidades de melhoria.

Perguntas orientadoras:

- A detecção ocorreu em tempo adequado?
- Os responsáveis foram acionados corretamente?
- A classificação refletiu a gravidade observada?
- As decisões de contenção foram eficazes?
- As evidências foram preservadas adequadamente?
- A recuperação foi validada?
- As comunicações foram tempestivas e apropriadas?
- Os procedimentos e treinamentos precisam ser atualizados?
- Os riscos e controles precisam ser reavaliados?
- Há ações corretivas necessárias para evitar recorrência?

As melhorias devem possuir responsáveis, prazos, critérios de conclusão e evidências de implementação.

## 18. Treinamento e exercícios

A organização deve definir como o plano será divulgado, treinado, exercitado e revisado.

Exemplos de exercícios:

- Simulação de comprometimento de credenciais.
- Exercício de indisponibilidade de serviço crítico.
- Simulação de incidente envolvendo dados pessoais.
- Exercício de comunicação e escalonamento.
- Teste de coordenação com fornecedores.
- Simulação de recuperação a partir de cópias de segurança.

Os exercícios devem ter objetivos, escopo, participantes, critérios de avaliação e registro dos resultados. As conclusões devem alimentar o processo de melhoria.

## 19. Indicadores possíveis

Podem ser definidos indicadores como:

- Tempo entre detecção e registro.
- Tempo entre registro e acionamento.
- Tempo até contenção.
- Tempo de recuperação.
- Percentual de incidentes com classificação documentada.
- Percentual de incidentes com análise posterior.
- Percentual de ações de melhoria concluídas no prazo.
- Recorrência de incidentes por categoria.
- Resultados dos exercícios de resposta.

Cada indicador deve possuir definição, método de cálculo, fonte de dados, responsável e periodicidade. Os indicadores devem ser interpretados considerando o contexto e a qualidade dos registros.

## 20. Aprovação e manutenção do plano

O plano deve ser aprovado pelas autoridades definidas pela organização e revisado quando houver mudanças relevantes, como:

- Alterações no escopo do SGSI.
- Mudanças organizacionais ou tecnológicas.
- Alterações significativas nos riscos.
- Mudanças legais, regulatórias ou contratuais.
- Incidentes relevantes.
- Resultados de auditorias ou exercícios.
- Identificação de falhas no processo de resposta.

**Responsável pela manutenção:** [Função]

**Periodicidade de revisão:** [Definir]

**Local oficial de publicação:** [Referência controlada]

**Data da última revisão:** [AAAA-MM-DD]

## 21. Checklist de validação

- [ ] O escopo do plano está definido.
- [ ] Os papéis e as autoridades foram designados.
- [ ] Os critérios de classificação e escalonamento foram estabelecidos.
- [ ] Os canais de acionamento estão disponíveis e protegidos.
- [ ] Os procedimentos de contenção e recuperação estão definidos.
- [ ] A preservação de evidências foi considerada.
- [ ] A comunicação interna e externa foi planejada.
- [ ] As interfaces com continuidade e recuperação foram definidas.
- [ ] Os critérios de encerramento e acompanhamento foram estabelecidos.
- [ ] O treinamento e os exercícios foram planejados.
- [ ] A aprovação e a revisão periódica estão definidas.

## 22. Limitações e orientações de uso

Este modelo deve ser adaptado, aprovado, comunicado e exercitado antes de ser tratado como plano operacional de uma organização.

A existência deste documento, isoladamente, não comprova que os procedimentos funcionem, que as equipes estejam preparadas ou que os requisitos da ISO/IEC 27001:2022 estejam integralmente atendidos.

Os exemplos de severidade, papéis, ações e indicadores são ilustrativos. A organização deve definir seus próprios critérios, responsabilidades, recursos e procedimentos com base no contexto e nos riscos.

## 23. Histórico de revisão

| Versão | Data | Descrição da alteração | Responsável |
|---|---|---|---|
| 1.0 | [AAAA-MM-DD] | Criação do modelo para adaptação | [Responsável] |
