# Metodologia de Gestão de Riscos de Segurança da Informação

## 1. Objetivo

Este documento estabelece uma metodologia de referência para identificar, analisar, avaliar e tratar riscos de segurança da informação no contexto de um Sistema de Gestão de Segurança da Informação (SGSI).

A metodologia tem como objetivos:

- estabelecer critérios consistentes para a gestão de riscos;
- identificar riscos relacionados à confidencialidade, integridade e disponibilidade da informação;
- apoiar decisões sobre aceitação, tratamento e priorização dos riscos;
- manter rastreabilidade entre riscos identificados, decisões tomadas e controles selecionados;
- fornecer subsídios para a Declaração de Aplicabilidade (SoA) e o Plano de Tratamento de Riscos;
- apoiar a melhoria contínua do SGSI.

Este documento apresenta uma metodologia de referência que deve ser adaptada ao contexto, aos objetivos, às obrigações e aos critérios de risco de cada organização.

## 2. Referências normativas e metodológicas

A metodologia considera como referências principais:

- **ISO/IEC 27001:2022**, incluindo a Emenda 1:2024 — requisitos para sistemas de gestão de segurança da informação, especialmente as cláusulas 6.1.2, relativa à avaliação de riscos de segurança da informação, e 6.1.3, relativa ao tratamento desses riscos.
- **ISO/IEC 27005:2022** — orientação específica para a gestão de riscos de segurança da informação.
- **ISO/IEC 27002:2022** — orientações de referência para controles de segurança da informação.
- **ISO 31000:2018** — princípios e orientações gerais para gestão de riscos, quando adotada como referência complementar.

A Emenda 1:2024 da ISO/IEC 27001 introduz considerações relacionadas às mudanças climáticas no contexto dos sistemas de gestão. A organização deve avaliar se as mudanças climáticas constituem questão relevante para seu contexto e se as partes interessadas pertinentes possuem requisitos relacionados a esse tema. A relevância deve ser determinada e documentada com base nas circunstâncias da organização, sem presumir que esse fator seja automaticamente um risco de segurança da informação em todos os contextos.

A organização deve verificar as edições e emendas aplicáveis das normas e assegurar que os requisitos utilizados na implementação correspondam às versões oficialmente adotadas.

Este documento não reproduz o texto integral das normas. A consulta às publicações oficiais é necessária para confirmar os requisitos normativos.

## 3. Princípios da metodologia

A gestão de riscos deve observar os seguintes princípios.

### 3.1. Adequação ao contexto

Os critérios e processos de avaliação devem refletir o contexto organizacional, o escopo do SGSI, os objetivos de negócio, as obrigações aplicáveis e as características dos ativos e processos envolvidos.

### 3.2. Consistência e repetibilidade

A metodologia deve permitir que avaliações realizadas por pessoas diferentes produzam resultados comparáveis, considerando os mesmos critérios e premissas.

### 3.3. Rastreabilidade

Cada risco deve possuir identificação única e informações suficientes para relacionar o cenário de risco, os critérios utilizados, a avaliação realizada, a decisão tomada e as ações de tratamento.

A rastreabilidade deve permitir identificar a relação entre a avaliação de riscos, as opções de tratamento selecionadas, os controles necessários, a Declaração de Aplicabilidade (SoA), o Plano de Tratamento de Riscos e as decisões de aceitação dos riscos residuais.

### 3.4. Fundamentação em evidências

As avaliações devem ser apoiadas, sempre que possível, por informações verificáveis, como inventários, registros de incidentes, resultados de auditoria, avaliações técnicas, requisitos contratuais e análises de processos.

Quando forem utilizadas estimativas ou julgamentos especializados, as premissas e limitações devem ser documentadas.

### 3.5. Participação das partes relevantes

A identificação e a avaliação dos riscos devem envolver as pessoas que conhecem os processos, ativos, tecnologias, obrigações e objetivos relacionados ao cenário avaliado.

### 3.6. Revisão contínua

Os riscos devem ser reavaliados quando ocorrerem mudanças relevantes no contexto, nos ativos, nas ameaças, nas vulnerabilidades, nos controles ou nos requisitos aplicáveis.

## 4. Conceitos fundamentais

Para aplicação desta metodologia, são utilizados os seguintes conceitos:

- **Ativo:** informação, recurso, serviço, processo ou componente relevante para a organização e que necessita de proteção.
- **Ameaça:** circunstância, evento ou agente capaz de provocar um impacto adverso.
- **Vulnerabilidade:** fragilidade que pode ser explorada ou contribuir para a materialização de um cenário de risco.
- **Evento de risco:** ocorrência potencial que pode afetar os objetivos ou a segurança da informação.
- **Impacto:** consequência de um evento sobre a organização, seus processos, informações, pessoas, obrigações ou objetivos.
- **Probabilidade:** estimativa da possibilidade de ocorrência de um evento ou cenário, conforme os critérios adotados.
- **Risco:** efeito da incerteza sobre os objetivos, avaliado no contexto da segurança da informação.
- **Risco inerente:** risco avaliado considerando o cenário antes da consideração dos controles existentes, conforme a convenção metodológica adotada.
- **Risco residual:** risco remanescente após a consideração dos controles existentes ou das medidas de tratamento implementadas.
- **Proprietário do risco:** pessoa ou função com responsabilidade atribuída para assegurar que o risco seja avaliado e tratado ou aceito dentro de sua autoridade.
- **Tratamento do risco:** processo de selecionar e implementar opções para modificar o risco.
- **Critério de aceitação:** condição ou limite previamente estabelecido para determinar quando um risco pode ser aceito.

As definições devem ser harmonizadas com o vocabulário normativo e com as regras internas da organização. Os termos “risco inerente” e “risco residual”, bem como suas formas de cálculo, devem ser definidos explicitamente na metodologia adotada.

## 5. Governança da gestão de riscos

A organização deve estabelecer responsabilidades para a gestão de riscos de segurança da informação.

Como referência metodológica, podem ser consideradas as seguintes atribuições:

| Papel | Atribuição de referência |
|---|---|
| Alta direção | Assegurar o direcionamento e os recursos necessários ao SGSI e às decisões de risco que estejam sob sua autoridade. |
| Responsável pelo SGSI | Coordenar a aplicação da metodologia, consolidar informações e acompanhar o processo de avaliação. |
| Proprietário do risco | Validar o cenário, participar da avaliação e acompanhar o tratamento ou a aceitação formal dentro dos limites de autoridade definidos. |
| Responsável pelo processo | Fornecer informações sobre processos, impactos, dependências e requisitos operacionais. |
| Responsável técnico | Contribuir com análises de ameaças, vulnerabilidades, arquitetura, exposição e eficácia dos controles. |
| Jurídico, privacidade ou conformidade | Apoiar a identificação e a interpretação de obrigações legais, regulatórias e contratuais pertinentes. |
| Auditoria interna | Avaliar, com independência apropriada, a conformidade e a eficácia dos processos e controles auditados. |

Os papéis acima são referências metodológicas, não uma estrutura organizacional obrigatória estabelecida pela ISO/IEC 27001:2022.

A organização deve documentar quem pode aprovar planos de tratamento, aceitar riscos e autorizar exceções, considerando a relevância do risco e os limites de autoridade definidos.

A responsabilidade pela avaliação técnica de um risco não significa, por si só, autoridade para aceitá-lo. A organização deve estabelecer e documentar os limites de decisão e a autoridade dos proprietários dos riscos e das demais funções envolvidas.

## 6. Etapas do processo de gestão de riscos

O processo de referência compreende as seguintes etapas:

1. estabelecer o contexto e os critérios de risco;
2. identificar riscos;
3. analisar riscos;
4. avaliar e priorizar riscos;
5. selecionar opções de tratamento;
6. determinar os controles necessários e realizar a comparação com o Anexo A;
7. documentar as decisões na SoA e no Plano de Tratamento de Riscos;
8. aprovar o plano de tratamento e obter as aprovações pertinentes;
9. implementar e acompanhar o tratamento;
10. reavaliar os riscos residuais;
11. obter e registrar a aceitação formal dos riscos residuais pelos proprietários dos riscos, conforme aplicável;
12. monitorar, comunicar e revisar os riscos.

Essas etapas formam um fluxo metodológico. A organização pode integrá-las aos processos de gestão existentes, desde que preserve os requisitos aplicáveis e a rastreabilidade das decisões.

A sequência representa uma referência de trabalho e não deve ser interpretada como substituta dos requisitos específicos da ISO/IEC 27001:2022.

## 7. Estabelecimento dos critérios de risco

Antes de iniciar as avaliações, devem ser definidos e aprovados os critérios que serão utilizados.

Os critérios devem contemplar, no mínimo:

- critérios para avaliação de riscos de segurança da informação;
- critérios para aceitação de riscos;
- critérios para classificar impacto e probabilidade;
- regras de priorização;
- limites de autoridade para aprovação e aceitação;
- condições que exigem escalonamento;
- critérios para revisão e reavaliação.

A metodologia deve ser suficientemente clara para que as avaliações sejam consistentes e comparáveis.

### 7.1. Escala de impacto

Como exemplo didático, pode ser adotada uma escala de cinco níveis:

| Nível | Classificação | Descrição ilustrativa |
|---|---|---|
| 1 | Insignificante | Consequência limitada, sem comprometimento relevante dos objetivos ou processos. |
| 2 | Baixo | Consequência localizada, administrável pelos procedimentos operacionais habituais. |
| 3 | Moderado | Interrupção, perda ou exposição que exige atuação coordenada e pode afetar objetivos relevantes. |
| 4 | Alto | Consequência significativa sobre processos críticos, obrigações, clientes, informações ou continuidade operacional. |
| 5 | Crítico | Consequência severa, com comprometimento expressivo dos objetivos, operações, obrigações ou partes interessadas. |

A classificação deve considerar dimensões relevantes ao contexto, tais como:

- confidencialidade;
- integridade;
- disponibilidade;
- continuidade operacional;
- impacto financeiro;
- impacto legal, regulatório ou contratual;
- impacto reputacional;
- segurança física de pessoas, quando pertinente.

A organização deve definir como consolidar impactos de diferentes dimensões. Não se deve presumir que todas as dimensões tenham o mesmo peso.

### 7.2. Escala de probabilidade

Como exemplo didático, pode ser utilizada a seguinte escala:

| Nível | Classificação | Descrição ilustrativa |
|---|---|---|
| 1 | Rara | A ocorrência é considerada excepcional no contexto avaliado. |
| 2 | Improvável | A ocorrência é possível, mas não é esperada nas condições consideradas. |
| 3 | Possível | A ocorrência pode acontecer e existem condições plausíveis para sua materialização. |
| 4 | Provável | A ocorrência é esperada ou existem evidências relevantes de possibilidade elevada. |
| 5 | Quase certa | A ocorrência é muito provável no horizonte de avaliação considerado. |

As classificações devem ser acompanhadas de critérios verificáveis sempre que possível. A organização pode utilizar frequência histórica, exposição, inteligência de ameaças, vulnerabilidades conhecidas, mudanças recentes e eficácia dos controles como elementos de análise.

Não se deve atribuir uma probabilidade apenas com base na percepção subjetiva quando houver informações relevantes disponíveis.

### 7.3. Matriz ilustrativa de risco

Uma matriz didática pode utilizar o produto entre impacto e probabilidade:

**Pontuação ilustrativa = Impacto × Probabilidade**

| Probabilidade \ Impacto | 1 | 2 | 3 | 4 | 5 |
|---|---:|---:|---:|---:|---:|
| 5 | 5 | 10 | 15 | 20 | 25 |
| 4 | 4 | 8 | 12 | 16 | 20 |
| 3 | 3 | 6 | 9 | 12 | 15 |
| 2 | 2 | 4 | 6 | 8 | 10 |
| 1 | 1 | 2 | 3 | 4 | 5 |

A pontuação resultante não constitui uma exigência específica da ISO/IEC 27001:2022. Trata-se de uma opção metodológica ilustrativa.

A organização deve estabelecer os intervalos de classificação e as respectivas regras de decisão. Não existe uma classificação universal de risco baixo, médio, alto ou crítico que deva ser aplicada indistintamente a todas as organizações.

A multiplicação também não representa necessariamente uma medida estatística do risco. Ela é uma técnica simplificada de priorização e deve ser utilizada com as limitações devidamente compreendidas.

## 8. Identificação dos riscos

A identificação deve considerar o escopo do SGSI, os processos, as informações, os ativos, as interfaces, os fornecedores, as dependências e os requisitos aplicáveis.

Para cada risco identificado, devem ser registrados, conforme pertinente:

- identificador único;
- processo, ativo ou informação afetada;
- proprietário do risco;
- descrição do cenário;
- causa ou condição relevante;
- ameaça ou fonte potencial;
- vulnerabilidade ou fator de exposição;
- evento potencial;
- consequências possíveis;
- controles existentes conhecidos;
- fonte das informações e evidências;
- data da identificação.

A descrição deve ser suficientemente específica para permitir compreender como o cenário pode ocorrer e quais consequências pode produzir.

### 8.1. Estrutura sugerida para descrever um risco

Uma estrutura útil para documentação é:

**Devido a [causa, ameaça ou condição], pode ocorrer [evento], resultando em [consequências para os objetivos ou a segurança da informação].**

Exemplo hipotético:

“Devido à ausência de revisão periódica dos privilégios de acesso, uma conta pode manter permissões incompatíveis com a função atual de seu titular, resultando em acesso indevido a informações restritas.”

O exemplo é ilustrativo e não representa constatação sobre uma organização real.

A formulação deve evitar tratar uma vulnerabilidade isolada como se ela descrevesse integralmente o risco. É importante registrar o evento potencial e suas consequências.

## 9. Análise dos riscos

A análise deve estimar o nível de risco segundo os critérios estabelecidos.

Devem ser considerados, conforme aplicável:

- características do cenário;
- exposição dos ativos e processos;
- ameaças relevantes;
- vulnerabilidades conhecidas;
- controles existentes;
- evidências sobre a operação e a eficácia dos controles;
- probabilidade de ocorrência;
- magnitude das consequências;
- incertezas e limitações da avaliação.

A organização deve definir se sua avaliação inicial representa o risco inerente, o risco considerando controles existentes ou outra condição claramente especificada.

Se houver análise de risco residual, a documentação deve identificar quais controles foram considerados e qual é a evidência de sua implementação e eficácia.

A mera existência de uma política, procedimento ou ferramenta não comprova, por si só, que o controle está implementado ou que opera eficazmente.

A metodologia deve distinguir claramente:

- **risco inerente:** estimativa do risco antes de considerar os controles existentes, conforme a convenção adotada;
- **risco atual ou avaliado:** risco estimado considerando as condições e os controles existentes, quando essa abordagem for utilizada;
- **risco residual após tratamento:** risco remanescente após a implementação e a avaliação das medidas de tratamento.

A organização deve definir qual dessas avaliações será utilizada em cada etapa e evitar comparações entre resultados calculados com premissas diferentes.

## 10. Avaliação e priorização

A avaliação compara os resultados da análise com os critérios de risco aprovados.

O processo deve permitir:

- determinar quais riscos necessitam de tratamento;
- identificar riscos que podem ser aceitos conforme os critérios definidos;
- priorizar ações conforme a relevância do cenário;
- identificar riscos que exigem decisão da alta direção;
- documentar justificativas e exceções;
- estabelecer prazos e responsáveis para as decisões necessárias.

A priorização não deve considerar apenas a pontuação calculada. Obrigações legais, regulatórias ou contratuais, impactos sobre pessoas, compromissos com clientes e outras condições relevantes podem exigir tratamento ou escalonamento independentemente do resultado numérico.

A decisão de aceitar um risco deve ser registrada e aprovada por pessoa ou função com autoridade apropriada. A aceitação não elimina o risco nem substitui obrigações aplicáveis.

Quando o risco estiver fora dos critérios de aceitação, a organização deve avaliar opções de tratamento ou escalonar a decisão conforme a governança estabelecida. Uma decisão de aceitação excepcional não deve ser usada para afastar obrigações legais, regulatórias ou contratuais aplicáveis.

## 11. Registro de riscos

O registro de riscos é o instrumento de rastreabilidade da avaliação e das decisões tomadas.

Como estrutura de referência, recomenda-se manter os seguintes campos:

| Campo | Finalidade |
|---|---|
| ID do risco | Identificador único e persistente. |
| Data de identificação | Registrar quando o cenário foi identificado. |
| Processo ou ativo | Indicar o contexto afetado. |
| Proprietário do risco | Identificar a responsabilidade pela gestão do risco. |
| Cenário de risco | Descrever causa, evento e consequências. |
| Controles existentes | Registrar controles considerados na análise. |
| Impacto | Documentar a classificação e sua justificativa. |
| Probabilidade | Documentar a classificação e sua justificativa. |
| Nível de risco | Registrar o resultado segundo a metodologia adotada. |
| Base da avaliação | Indicar se o resultado representa risco inerente, risco atual ou outra condição definida. |
| Critério de aceitação | Identificar o critério aplicado à decisão. |
| Decisão | Registrar tratamento, aceitação ou outra decisão fundamentada. |
| Plano de tratamento | Referenciar as ações necessárias, quando aplicável. |
| Responsável pela ação | Identificar quem executará a ação. |
| Prazo | Registrar a data-alvo aprovada. |
| Risco residual | Registrar a avaliação após o tratamento, quando realizada. |
| Aprovação | Identificar a autoridade que aprovou a decisão. |
| Aceitação do risco residual | Registrar a decisão formal do proprietário do risco, quando aplicável. |
| Situação | Indicar o estado atual do risco e das ações. |
| Histórico de revisão | Preservar alterações e decisões relevantes. |

A organização deve adaptar os campos à sua realidade, preservando as informações necessárias para demonstrar a aplicação consistente do processo.

O registro pode ser mantido em planilha, sistema de gestão de riscos ou outra ferramenta controlada. A ferramenta escolhida não substitui a necessidade de critérios claros, governança e evidências.

## 12. Relação com o tratamento de riscos

A avaliação de riscos deve fornecer entradas para a seleção das opções de tratamento.

Entre as opções metodológicas possíveis estão:

- modificar o risco por meio de controles ou outras medidas;
- evitar a atividade ou condição que origina o risco;
- compartilhar ou transferir parte do risco, quando apropriado;
- aceitar o risco, desde que a decisão seja compatível com os critérios e a autoridade estabelecidos.

Essas opções devem ser avaliadas considerando sua adequação ao cenário, seus custos, seus efeitos esperados, as obrigações aplicáveis e os riscos remanescentes.

A seleção de controles deve considerar os requisitos da ISO/IEC 27001:2022, incluindo a emenda aplicável, os resultados da avaliação de riscos e as necessidades da organização.

A aplicação desta metodologia deve ser integrada ao documento específico de tratamento de riscos e à elaboração da Declaração de Aplicabilidade (SoA). Esses documentos devem manter rastreabilidade entre os riscos, as decisões de tratamento e os controles selecionados.

A aprovação do plano de tratamento, a implementação das ações, a verificação dos controles e a aceitação do risco residual são etapas distintas. A organização deve registrar cada decisão pertinente e identificar seus responsáveis.

## 13. Monitoramento e revisão

Os riscos devem ser monitorados e reavaliados de acordo com critérios previamente definidos.

Eventos que podem justificar revisão incluem:

- mudanças significativas no contexto organizacional;
- introdução ou alteração de sistemas e serviços;
- mudanças relevantes em processos ou fornecedores;
- incidentes de segurança da informação;
- identificação de novas ameaças ou vulnerabilidades;
- falhas ou alterações nos controles;
- resultados de auditorias e avaliações;
- alterações em obrigações legais, regulatórias ou contratuais;
- mudanças relevantes no escopo do SGSI;
- alterações no contexto climático, quando identificadas como relevantes para o contexto organizacional ou para os riscos de segurança da informação.

A organização deve definir periodicidade, responsáveis e gatilhos de revisão compatíveis com a criticidade dos riscos.

O encerramento de uma ação de tratamento não deve ser confundido com o encerramento automático do risco. A necessidade de acompanhamento deve ser determinada conforme o cenário, os controles implementados e os critérios aplicáveis.

Quando a reavaliação indicar que o risco residual permanece acima dos critérios de aceitação, devem ser avaliadas medidas adicionais ou o escalonamento da decisão.

## 14. Evidências e registros do processo

A organização deve determinar quais informações documentadas são necessárias para demonstrar a aplicação do processo de avaliação e tratamento de riscos.

Como exemplos de registros que podem ser mantidos, conforme aplicável:

- metodologia e critérios de risco aprovados;
- registro de riscos;
- evidências e premissas utilizadas nas avaliações;
- atas ou registros de decisões;
- aprovações de aceitação de riscos;
- planos de tratamento;
- resultados de reavaliações;
- histórico de alterações;
- comunicações sobre riscos relevantes;
- registros de acompanhamento das ações;
- evidências que sustentem a avaliação dos controles existentes;
- registros de aprovação do plano de tratamento;
- registros de aceitação dos riscos residuais pelos respectivos proprietários, conforme aplicável.

Esses itens constituem exemplos de evidências. A seleção e a extensão dos registros devem considerar os requisitos normativos aplicáveis, o contexto e as necessidades de demonstração de conformidade.

Os registros devem possuir controles adequados de acesso, integridade, versionamento, retenção e recuperação.

## 15. Critérios de qualidade da metodologia

Antes de considerar a metodologia apta para utilização, devem ser avaliados os seguintes pontos:

- [ ] Os critérios de avaliação e aceitação de riscos estão definidos.
- [ ] A metodologia permite produzir resultados consistentes e comparáveis.
- [ ] Os critérios consideram o contexto e os objetivos da organização.
- [ ] Os riscos possuem identificadores únicos.
- [ ] Os cenários descrevem eventos e consequências compreensíveis.
- [ ] As premissas e limitações relevantes são documentadas.
- [ ] Os controles existentes são considerados com base em informações disponíveis.
- [ ] A base da avaliação — inerente, atual ou residual — está identificada.
- [ ] As decisões de tratamento e aceitação possuem justificativas.
- [ ] As responsabilidades e autoridades estão definidas.
- [ ] A aprovação do plano e a aceitação dos riscos residuais são tratadas como decisões distintas.
- [ ] A metodologia prevê monitoramento e revisão.
- [ ] Existe rastreabilidade entre avaliação, tratamento, SoA e controles selecionados.
- [ ] Os registros necessários estão sujeitos a controles apropriados.
- [ ] As referências normativas e suas edições aplicáveis foram verificadas.

A conclusão dessa verificação indica que a metodologia foi revisada segundo os critérios estabelecidos. Não representa, isoladamente, evidência de que o SGSI esteja implementado ou em conformidade integral com a norma.

## 16. Limitações e adaptação

Esta metodologia é um modelo de referência para fins educacionais e de estruturação profissional.

Ela não representa uma avaliação de riscos efetivamente realizada para uma organização específica, nem comprova a implementação ou a eficácia de controles.

Antes de utilizar o modelo em um SGSI real, a organização deve:

1. definir e aprovar seus critérios de risco;
2. adaptar as escalas e regras de decisão ao seu contexto;
3. identificar os riscos associados ao escopo efetivo do SGSI;
4. designar responsáveis e autoridades;
5. documentar as evidências e premissas das avaliações;
6. integrar os resultados ao processo de tratamento de riscos e à SoA;
7. definir como aprovar o plano de tratamento e registrar a aceitação dos riscos residuais;
8. revisar a metodologia à luz dos requisitos normativos e das necessidades organizacionais.

Nenhuma escala, matriz ou exemplo deste documento deve ser interpretado como uma exigência universal da ISO/IEC 27001:2022.

## 17. Documentos relacionados

Este documento deve ser articulado com os demais componentes da documentação do SGSI, especialmente:

- Documento Mestre de Implementação do SGSI;
- Análise de Contexto e Partes Interessadas;
- Definição do Escopo do SGSI;
- Política de Segurança da Informação;
- Papéis, Responsabilidades e Autoridades do SGSI;
- Declaração de Aplicabilidade (SoA);
- Plano de Tratamento de Riscos;
- Registro de Riscos;
- procedimentos e registros de controles de segurança;
- processo de monitoramento, auditoria e melhoria contínua.

A existência desses documentos no repositório representa uma estrutura documental de referência. Sua inclusão não comprova que tenham sido aprovados, implantados ou utilizados por uma organização.

## 18. Referências

- ISO/IEC 27001:2022 — Information security, cybersecurity and privacy protection — Information security management systems — Requirements.
- ISO/IEC 27001:2022/Amd 1:2024 — Information security, cybersecurity and privacy protection — Information security management systems — Requirements — Amendment 1: Climate action changes.
- ISO/IEC 27005:2022 — Guidance on managing information security risks.
- ISO/IEC 27002:2022 — Information security, cybersecurity and privacy protection — Information security controls.
- ISO 31000:2018 — Risk management — Guidelines.

Consultar as publicações oficiais para confirmar os requisitos, as definições, as edições e as orientações aplicáveis.

