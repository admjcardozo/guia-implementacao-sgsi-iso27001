# Metodologia de Gestão de Riscos de Segurança da Informação

## 1. Objetivo

Este documento estabelece uma metodologia de referência para identificar, analisar, avaliar, tratar e monitorar riscos de segurança da informação no contexto de um Sistema de Gestão de Segurança da Informação (SGSI).

A metodologia tem como objetivos:

- estabelecer critérios consistentes para a gestão de riscos;
- identificar riscos relacionados à confidencialidade, integridade e disponibilidade da informação;
- apoiar decisões sobre aceitação, tratamento e priorização dos riscos;
- manter rastreabilidade entre riscos identificados, avaliações, decisões tomadas e controles selecionados;
- fornecer subsídios para a Declaração de Aplicabilidade (SoA) e o Plano de Tratamento de Riscos;
- estabelecer uma base para a avaliação dos riscos residuais após o tratamento;
- apoiar o monitoramento e a melhoria contínua do SGSI.

Este documento apresenta uma metodologia de referência que deve ser adaptada ao contexto, aos objetivos, às obrigações e aos critérios de risco de cada organização.

## 2. Referências normativas e metodológicas

A metodologia considera como referências principais:

- **ISO/IEC 27001:2022**, incluindo a Emenda 1:2024 — requisitos para sistemas de gestão de segurança da informação, especialmente as cláusulas 6.1.2, relativa à avaliação de riscos de segurança da informação, e 6.1.3, relativa ao tratamento desses riscos.
- **ISO/IEC 27005:2022** — orientação específica para a gestão de riscos de segurança da informação.
- **ISO/IEC 27002:2022** — orientações de referência para controles de segurança da informação.
- **ISO 31000:2018** — princípios e orientações gerais para gestão de riscos, quando adotada como referência complementar.

A Emenda 1:2024 da ISO/IEC 27001 introduz considerações relacionadas às mudanças climáticas no contexto dos sistemas de gestão. A organização deve determinar se as mudanças climáticas constituem uma questão relevante para seu contexto e considerar os requisitos pertinentes das partes interessadas relacionados a esse tema.

Essa análise deve ser fundamentada nas circunstâncias da organização. Não se deve presumir que as mudanças climáticas constituam automaticamente um risco de segurança da informação em todos os contextos. Quando a análise de contexto identificar fatores climáticos relevantes para os objetivos, processos, ativos ou dependências do SGSI, esses fatores devem ser considerados na identificação e na avaliação dos riscos pertinentes.

A organização deve verificar as edições e emendas aplicáveis das normas e assegurar que os requisitos utilizados na implementação correspondam às versões oficialmente adotadas.

Este documento não reproduz o texto integral das normas. A consulta às publicações oficiais é necessária para confirmar os requisitos normativos.

## 3. Princípios da metodologia

A gestão de riscos deve observar os seguintes princípios.

### 3.1. Adequação ao contexto

Os critérios e processos de avaliação devem refletir o contexto organizacional, o escopo do SGSI, os objetivos de negócio, as obrigações aplicáveis e as características dos ativos e processos envolvidos.

### 3.2. Consistência e repetibilidade

A metodologia deve permitir que avaliações realizadas por pessoas diferentes produzam resultados comparáveis, considerando os mesmos critérios, premissas e condições de avaliação.

Quando houver mudanças nos critérios ou nas premissas, essas alterações devem ser documentadas para permitir a interpretação adequada dos resultados.

### 3.3. Rastreabilidade

Cada risco deve possuir identificação única e informações suficientes para relacionar o cenário de risco, os critérios utilizados, a base da avaliação, os resultados obtidos, as decisões tomadas e as ações de tratamento.

A rastreabilidade deve permitir identificar a relação entre:

- contexto e escopo do SGSI;
- riscos identificados e resultados das avaliações;
- opções de tratamento selecionadas;
- controles determinados como necessários;
- Declaração de Aplicabilidade (SoA);
- Plano de Tratamento de Riscos;
- implementação e avaliação dos controles;
- avaliação dos riscos residuais;
- aprovação do plano e aceitação formal dos riscos residuais.

### 3.4. Fundamentação em evidências

As avaliações devem ser apoiadas, sempre que possível, por informações verificáveis, como inventários, registros de incidentes, resultados de auditoria, avaliações técnicas, requisitos contratuais e análises de processos.

Quando forem utilizadas estimativas, hipóteses ou julgamentos especializados, as premissas, as fontes consultadas e as limitações relevantes devem ser documentadas.

A existência de um documento, procedimento ou ferramenta não comprova, isoladamente, que determinado controle esteja implementado ou seja eficaz.

### 3.5. Participação das partes relevantes

A identificação e a avaliação dos riscos devem envolver as pessoas que conhecem os processos, ativos, tecnologias, obrigações e objetivos relacionados ao cenário avaliado.

O proprietário do risco deve participar das decisões de gestão que estejam sob sua responsabilidade, inclusive da aprovação do plano de tratamento e da aceitação do risco residual, conforme os requisitos aplicáveis.

### 3.6. Revisão contínua

Os riscos devem ser reavaliados quando ocorrerem mudanças relevantes no contexto, nos ativos, nas ameaças, nas vulnerabilidades, nos controles ou nos requisitos aplicáveis.

A organização deve estabelecer critérios para revisão periódica e para reavaliação motivada por eventos, evitando que o registro de riscos permaneça desatualizado diante de mudanças relevantes.

## 4. Conceitos fundamentais

Para aplicação desta metodologia, são utilizados os seguintes conceitos:

- **Ativo:** informação, recurso, serviço, processo ou componente relevante para a organização e que necessita de proteção.
- **Ameaça:** circunstância, evento ou agente capaz de provocar um impacto adverso.
- **Vulnerabilidade:** fragilidade que pode ser explorada ou contribuir para a materialização de um cenário de risco.
- **Evento de risco:** ocorrência potencial que pode afetar os objetivos ou a segurança da informação.
- **Impacto:** consequência de um evento sobre a organização, seus processos, informações, pessoas, obrigações ou objetivos.
- **Probabilidade:** estimativa da possibilidade de ocorrência de um evento ou cenário, conforme os critérios adotados.
- **Risco:** efeito da incerteza sobre os objetivos, avaliado no contexto da segurança da informação.
- **Risco inerente:** estimativa do risco antes de considerar os controles existentes, conforme a convenção metodológica adotada pela organização.
- **Risco atual:** estimativa do risco nas condições existentes no momento da avaliação, considerando os controles efetivamente implementados e as evidências disponíveis sobre sua operação e eficácia.
- **Risco residual esperado:** estimativa do risco que deverá permanecer após a implementação das medidas de tratamento planejadas. Trata-se de uma previsão, não de uma comprovação de resultado.
- **Risco residual reavaliado:** estimativa do risco remanescente após a implementação das medidas de tratamento e a avaliação das condições e dos controles resultantes.
- **Proprietário do risco:** pessoa ou função designada para responder pela gestão do risco e pelas decisões que lhe competem, incluindo a aprovação do plano de tratamento e a aceitação do risco residual.
- **Responsável pela ação de tratamento:** pessoa ou função designada para executar uma ação específica prevista no plano de tratamento.
- **Tratamento do risco:** processo de selecionar e implementar opções para modificar o risco.
- **Critério de aceitação:** condição ou limite previamente estabelecido para determinar se um risco pode ser aceito.
- **Controle:** medida que mantém e/ou modifica o risco.

A terminologia deve ser aplicada de forma consistente em toda a documentação do SGSI.

Nesta metodologia, o termo **risco atual** designa a condição de referência para a decisão de tratamento. O termo **risco inerente** pode ser utilizado como análise complementar, desde que a organização defina sua finalidade e os critérios utilizados. A expressão **resultado da avaliação de riscos** pode ser empregada genericamente, mas não deve ser tratada como uma categoria adicional de risco.

O risco residual esperado e o risco residual reavaliado também não devem ser confundidos: o primeiro é uma estimativa anterior à confirmação dos resultados; o segundo decorre da reavaliação após a implementação das medidas de tratamento.

A organização deve documentar as escalas, as regras de cálculo, as premissas e os critérios utilizados. Não se deve presumir que exista uma fórmula universal obrigatória para o cálculo de risco inerente, atual ou residual.

O proprietário do risco e o responsável pela ação de tratamento exercem funções distintas. Uma mesma pessoa pode assumir ambas, desde que isso esteja definido e seja compatível com as responsabilidades e autoridades estabelecidas.

## 5. Governança da gestão de riscos

A organização deve estabelecer responsabilidades para a gestão de riscos de segurança da informação.

Como referência metodológica, podem ser consideradas as seguintes atribuições:

| Papel | Atribuição de referência |
|---|---|
| Alta direção | Assegurar o direcionamento e os recursos necessários ao SGSI e tomar decisões de risco que estejam sob sua autoridade. |
| Responsável pelo SGSI | Coordenar a aplicação da metodologia, consolidar informações e acompanhar o processo de avaliação e tratamento. |
| Proprietário do risco | Validar o cenário, participar da avaliação, aprovar o plano de tratamento e aceitar formalmente o risco residual, conforme os requisitos aplicáveis e os limites de autoridade definidos. |
| Responsável pelo processo | Fornecer informações sobre processos, impactos, dependências e requisitos operacionais. |
| Responsável técnico | Contribuir com análises de ameaças, vulnerabilidades, arquitetura, exposição e eficácia dos controles. |
| Responsável pela ação de tratamento | Executar as ações que lhe forem atribuídas, fornecer evidências de execução e comunicar desvios ou impedimentos. |
| Jurídico, privacidade ou conformidade | Apoiar a identificação e a interpretação de obrigações legais, regulatórias e contratuais pertinentes. |
| Auditoria interna | Avaliar, com independência apropriada, a conformidade e a eficácia dos processos e controles auditados. |

Os papéis acima são referências metodológicas, não uma estrutura organizacional obrigatória estabelecida pela ISO/IEC 27001:2022.

A organização deve documentar as responsabilidades e autoridades pertinentes, incluindo quem pode aprovar planos de tratamento, aceitar riscos e autorizar exceções, considerando a relevância do risco e os limites de autoridade definidos.

A responsabilidade pela avaliação técnica de um risco não significa, por si só, autoridade para aceitá-lo. Da mesma forma, a execução de uma ação não transfere automaticamente ao executor a responsabilidade pela decisão de aceitar o risco remanescente.

A organização deve assegurar que a aprovação do plano de tratamento e a aceitação dos riscos residuais sejam atribuídas aos respectivos proprietários dos riscos, conforme a ISO/IEC 27001:2022, cláusula 6.1.3, e os requisitos de governança aplicáveis.

## 6. Etapas do processo de gestão de riscos

O processo de referência compreende as seguintes etapas:

1. estabelecer o contexto e os critérios de risco;
2. identificar os riscos relacionados ao escopo do SGSI;
3. analisar os riscos conforme os critérios estabelecidos;
4. avaliar e priorizar os riscos;
5. decidir as opções de tratamento necessárias;
6. determinar os controles necessários e compará-los com os controles do Anexo A da ISO/IEC 27001:2022, conforme os requisitos aplicáveis;
7. registrar as justificativas de inclusão e exclusão de controles na Declaração de Aplicabilidade (SoA);
8. elaborar e documentar o Plano de Tratamento de Riscos;
9. obter a aprovação do plano pelos proprietários dos riscos;
10. implementar e acompanhar as ações aprovadas;
11. verificar a implementação e avaliar a operação e a eficácia dos controles pertinentes;
12. reavaliar os riscos após o tratamento;
13. obter e registrar a aceitação formal dos riscos residuais pelos respectivos proprietários dos riscos;
14. monitorar, comunicar e revisar os riscos e as decisões tomadas.

As etapas formam um fluxo metodológico integrado. A organização pode integrá-las aos processos de gestão existentes, desde que preserve os requisitos aplicáveis e a rastreabilidade das decisões.

A sequência não significa que todas as atividades precisem ocorrer de maneira estritamente linear. Informações novas, mudanças de contexto, falhas de controle ou resultados de avaliações podem exigir o retorno a etapas anteriores.

A metodologia deve distinguir as decisões de tratamento, a aprovação do plano, a execução das ações, a avaliação dos resultados e a aceitação do risco residual. Essas atividades estão relacionadas, mas não são equivalentes.

## 7. Estabelecimento dos critérios de risco

Antes de iniciar as avaliações, devem ser definidos os critérios que serão utilizados, de forma compatível com o contexto e com os objetivos da organização.

Os critérios devem contemplar, no mínimo:

- critérios para avaliação de riscos de segurança da informação;
- critérios para aceitação de riscos;
- critérios para classificar impacto e probabilidade;
- regras de priorização;
- limites de autoridade para aprovação e aceitação;
- condições que exigem escalonamento;
- critérios para revisão e reavaliação;
- regras para comparar resultados de avaliações realizadas em etapas diferentes;
- critérios para avaliar os riscos residuais após o tratamento.

A metodologia deve ser suficientemente clara para que as avaliações sejam consistentes e comparáveis.

Quando a organização utilizar escalas diferentes ou alterar critérios ao longo do tempo, deverá documentar as mudanças e avaliar seus efeitos sobre a comparabilidade dos resultados.

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

Os limites e exemplos devem ser adaptados aos objetivos, às obrigações e às características da organização. A escala apresentada é ilustrativa e não constitui uma classificação universal obrigatória.

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

A probabilidade deve ser estimada considerando as condições correspondentes à base da avaliação. Por exemplo, uma estimativa de risco atual deve considerar os controles existentes e as evidências disponíveis sobre sua operação e eficácia.

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

Os resultados só devem ser comparados diretamente quando as escalas, as premissas e a base da avaliação forem compatíveis.

## 8. Identificação dos riscos

A identificação deve considerar o escopo do SGSI, os processos, as informações, os ativos, as interfaces, os fornecedores, as dependências e os requisitos aplicáveis.

Para cada risco identificado, devem ser registrados:

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

Outras informações podem ser incluídas conforme a complexidade do cenário e as necessidades de rastreabilidade.

A descrição deve ser suficientemente específica para permitir compreender como o cenário pode ocorrer e quais consequências pode produzir.

### 8.1. Estrutura sugerida para descrever um risco

Uma estrutura útil para documentação é:

**Devido a [causa, ameaça ou condição], pode ocorrer [evento], resultando em [consequências para os objetivos ou a segurança da informação].**

Exemplo hipotético:

“Devido à ausência de revisão periódica dos privilégios de acesso, uma conta pode manter permissões incompatíveis com a função atual de seu titular, resultando em acesso indevido a informações restritas.”

O exemplo é ilustrativo e não representa constatação sobre uma organização real.

A formulação deve evitar tratar uma vulnerabilidade isolada como se ela descrevesse integralmente o risco. É importante registrar o evento potencial e suas consequências.

## 9. Análise dos riscos

A análise deve estimar o nível de risco segundo os critérios estabelecidos e identificar as condições consideradas na avaliação.

Devem ser considerados, conforme pertinente:

- características do cenário;
- exposição dos ativos e processos;
- ameaças relevantes;
- vulnerabilidades conhecidas;
- controles existentes;
- evidências sobre a implementação, a operação e a eficácia dos controles;
- probabilidade de ocorrência;
- magnitude das consequências;
- incertezas e limitações da avaliação.

A metodologia deve adotar o **risco atual** como referência operacional para a decisão de tratamento, considerando as condições existentes no momento da avaliação.

O risco inerente pode ser calculado como análise complementar, desde que a organização defina sua finalidade, as premissas e a forma de comparação com o risco atual.

Se forem utilizados resultados de risco residual esperado, a documentação deve identificar que se trata de uma estimativa anterior à confirmação dos resultados do tratamento.

Após a implementação das medidas de tratamento, a organização deve reavaliar o risco residual com base nos controles e nas condições efetivamente existentes, utilizando evidências disponíveis sobre a implementação e a eficácia das medidas.

A mera existência de uma política, procedimento ou ferramenta não comprova, por si só, que o controle está implementado ou que opera eficazmente.

Para manter consistência, a documentação deve identificar a base de cada resultado:

- **Risco inerente:** estimativa antes de considerar os controles existentes, conforme a convenção adotada.
- **Risco atual:** estimativa considerando as condições e os controles existentes no momento da avaliação.
- **Risco residual esperado:** estimativa do risco remanescente após a implementação planejada das medidas de tratamento.
- **Risco residual reavaliado:** estimativa do risco remanescente após a implementação das medidas e a avaliação das condições resultantes.

A organização deve evitar comparar diretamente resultados calculados com premissas diferentes. Caso os critérios sejam alterados, as mudanças e seus efeitos devem ser documentados.

## 10. Avaliação e priorização

A avaliação compara os resultados da análise com os critérios de risco aprovados.

O processo deve permitir:

- determinar quais riscos necessitam de tratamento;
- identificar riscos que atendam aos critérios de aceitação;
- priorizar ações conforme a relevância do cenário;
- identificar riscos que exigem decisão da alta direção;
- documentar justificativas e exceções;
- estabelecer prazos e responsáveis para as decisões necessárias;
- identificar quando uma reavaliação ou medida adicional é necessária.

A priorização não deve considerar apenas a pontuação calculada. Obrigações legais, regulatórias ou contratuais, impactos sobre pessoas, compromissos com clientes e outras condições relevantes podem exigir tratamento ou escalonamento independentemente do resultado numérico.

A decisão de aceitar um risco deve respeitar os critérios e as autoridades estabelecidos e não pode ser utilizada para afastar obrigações legais, regulatórias ou contratuais aplicáveis.

A organização deve distinguir a aceitação de um risco segundo seus critérios internos da aceitação formal do risco residual após o tratamento. Quando houver tratamento planejado, a aceitação do risco residual deve ser registrada com base na avaliação pertinente e aprovada pelo respectivo proprietário do risco.

Quando o risco estiver fora dos critérios de aceitação, a organização deve avaliar opções de tratamento ou escalonar a decisão conforme a governança estabelecida. Eventuais exceções devem ser fundamentadas e não podem eliminar obrigações aplicáveis.

## 11. Registro de riscos

O registro de riscos é o instrumento de rastreabilidade das avaliações e das decisões tomadas.

Como estrutura de referência, recomenda-se manter os seguintes campos:

| Campo | Finalidade |
|---|---|
| ID do risco | Identificador único e persistente. |
| Data de identificação | Registrar quando o cenário foi identificado. |
| Processo ou ativo | Indicar o contexto afetado. |
| Proprietário do risco | Identificar quem responde pela gestão e pelas decisões pertinentes. |
| Cenário de risco | Descrever causa, evento e consequências. |
| Controles existentes | Registrar os controles considerados na avaliação. |
| Evidências dos controles | Referenciar informações disponíveis sobre implementação, operação e eficácia. |
| Impacto | Documentar a classificação e sua justificativa. |
| Probabilidade | Documentar a classificação e sua justificativa. |
| Resultado da avaliação | Registrar o nível de risco segundo os critérios adotados. |
| Base da avaliação | Indicar se o resultado representa risco inerente, risco atual, risco residual esperado ou risco residual reavaliado. |
| Critério de aceitação | Identificar o critério utilizado para a decisão. |
| Decisão de tratamento | Registrar a opção selecionada e sua justificativa. |
| Plano de tratamento | Referenciar as ações necessárias. |
| Responsável pela ação | Identificar quem executará cada ação. |
| Prazo | Registrar a data-alvo aprovada. |
| Aprovação do plano | Registrar a aprovação do plano de tratamento pelo proprietário do risco. |
| Evidências de execução | Referenciar registros que demonstrem a execução das ações. |
| Resultado da reavaliação | Registrar o risco residual após a implementação e a avaliação das medidas de tratamento. |
| Aceitação do risco residual | Registrar a decisão formal do proprietário do risco. |
| Situação | Indicar o estado atual do risco e das ações. |
| Histórico de revisão | Preservar alterações e decisões relevantes. |

A organização deve adaptar os campos à sua realidade, preservando as informações necessárias para demonstrar a aplicação consistente do processo.

Os campos devem permitir distinguir o proprietário do risco do responsável pela execução de cada ação. Também devem permitir verificar se o plano foi aprovado, se as medidas foram executadas, se o resultado foi reavaliado e se o risco residual foi formalmente aceito.

O registro pode ser mantido em planilha, sistema de gestão de riscos ou outra ferramenta controlada. A ferramenta escolhida não substitui a necessidade de critérios claros, governança e evidências.

## 12. Relação com o tratamento de riscos

A avaliação de riscos deve fornecer entradas para a seleção das opções de tratamento.

Entre as opções metodológicas possíveis estão:

- modificar o risco por meio de controles ou outras medidas;
- evitar a atividade ou condição que origina o risco;
- compartilhar ou transferir parte do risco, quando apropriado;
- aceitar o risco, desde que a decisão seja compatível com os critérios, as obrigações e a autoridade estabelecidos.

Essas opções devem ser avaliadas considerando sua adequação ao cenário, seus custos, seus efeitos esperados, as obrigações aplicáveis e os riscos remanescentes.

A seleção de controles deve considerar os requisitos da ISO/IEC 27001:2022, incluindo a emenda aplicável, os resultados da avaliação de riscos e as necessidades da organização. A comparação com o Anexo A deve contribuir para assegurar que controles necessários não sejam omitidos e que a SoA contenha as justificativas pertinentes para inclusão e exclusão.

A aplicação desta metodologia deve ser integrada ao documento específico de tratamento de riscos e à elaboração da Declaração de Aplicabilidade (SoA). Esses documentos devem manter rastreabilidade entre os riscos, as decisões de tratamento, os controles necessários e as ações planejadas.

A aprovação do plano de tratamento, a execução das ações, a verificação dos controles, a reavaliação do risco residual e a aceitação desse risco são atividades distintas.

Conforme a ISO/IEC 27001:2022, cláusula 6.1.3, o plano de tratamento deve ser aprovado pelos proprietários dos riscos, e os riscos residuais devem ser aceitos pelos respectivos proprietários dos riscos. Essas decisões devem ser registradas de forma que seja possível identificar quem aprovou o plano e quem aceitou cada risco residual.

A aprovação do plano não comprova que as ações foram executadas ou que os controles são eficazes. Da mesma forma, a conclusão de uma ação não equivale à aceitação do risco residual.

Quando a implementação das medidas produzir um resultado diferente do esperado, a organização deve reavaliar o risco e determinar se são necessárias ações adicionais antes da decisão de aceitação.

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
- alterações no contexto climático, quando identificadas como relevantes para o contexto organizacional ou para os riscos de segurança da informação;
- alterações nas premissas utilizadas para avaliar impacto, probabilidade ou eficácia dos controles.

A organização deve definir periodicidade, responsáveis e gatilhos de revisão compatíveis com a criticidade dos riscos.

O encerramento de uma ação de tratamento não deve ser confundido com o encerramento automático do risco. A conclusão da ação deve ser acompanhada da verificação pertinente e, quando necessária, da reavaliação do risco residual.

Quando a reavaliação indicar que o risco residual permanece acima dos critérios de aceitação, devem ser avaliadas medidas adicionais ou o escalonamento da decisão.

A aceitação do risco residual não elimina a necessidade de monitoramento quando o cenário continuar relevante para o SGSI. Mudanças posteriores podem exigir nova avaliação e decisões adicionais.

## 14. Evidências e registros do processo

A organização deve determinar quais informações documentadas são necessárias para demonstrar a aplicação do processo de avaliação e tratamento de riscos.

Como exemplos de registros que podem ser mantidos:

- metodologia e critérios de risco aprovados;
- registro de riscos;
- evidências e premissas utilizadas nas avaliações;
- atas ou registros de decisões;
- justificativas para as opções de tratamento selecionadas;
- Declaração de Aplicabilidade;
- planos de tratamento;
- registros de aprovação do plano pelos proprietários dos riscos;
- registros de acompanhamento e execução das ações;
- evidências de implementação e avaliação dos controles;
- resultados das reavaliações de risco residual;
- registros de aceitação dos riscos residuais pelos respectivos proprietários;
- histórico de alterações;
- comunicações sobre riscos relevantes;
- registros de revisão da metodologia.

A seleção e a extensão dos registros devem considerar os requisitos normativos aplicáveis, o contexto e as necessidades de demonstração de conformidade.

Os registros devem permitir reconstruir as principais decisões do processo, incluindo a base da avaliação, os critérios aplicados, as ações aprovadas, os resultados observados e as decisões de aceitação.

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
- [ ] A base da avaliação está identificada: risco inerente, risco atual, risco residual esperado ou risco residual reavaliado.
- [ ] As decisões de tratamento e aceitação possuem justificativas.
- [ ] As responsabilidades e autoridades estão definidas.
- [ ] O proprietário do risco está identificado para cada risco relevante.
- [ ] Os responsáveis pela execução das ações estão identificados.
- [ ] A aprovação do plano de tratamento pelos proprietários dos riscos está prevista e registrada.
- [ ] A reavaliação do risco residual após o tratamento está prevista.
- [ ] A aceitação formal dos riscos residuais pelos respectivos proprietários está prevista e registrada.
- [ ] A aprovação do plano, a execução das ações, a avaliação dos controles e a aceitação dos riscos residuais são tratadas como atividades distintas.
- [ ] Existe rastreabilidade entre avaliação, tratamento, SoA e controles selecionados.
- [ ] A metodologia prevê monitoramento e revisão.
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
4. designar proprietários dos riscos, responsáveis pelas ações e autoridades pertinentes;
5. documentar as evidências e premissas das avaliações;
6. integrar os resultados ao processo de tratamento de riscos e à SoA;
7. obter a aprovação do plano de tratamento pelos proprietários dos riscos;
8. implementar as ações e avaliar os resultados;
9. reavaliar os riscos residuais e obter sua aceitação formal pelos respectivos proprietários;
10. revisar a metodologia à luz dos requisitos normativos e das necessidades organizacionais.

Nenhuma escala, matriz ou exemplo deste documento deve ser interpretado como uma exigência universal da ISO/IEC 27001:2022.

A aplicação efetiva da metodologia depende de sua adaptação ao contexto real, da execução dos processos previstos e da manutenção das informações documentadas pertinentes.

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

O Plano de Tratamento de Riscos deve utilizar a mesma terminologia para risco atual, risco residual esperado e risco residual reavaliado, além de distinguir a aprovação do plano da aceitação formal dos riscos residuais.

A SoA deve manter rastreabilidade com os controles necessários, suas justificativas de inclusão ou exclusão e as informações de implementação pertinentes.

A existência desses documentos no repositório representa uma estrutura documental de referência. Sua inclusão não comprova que tenham sido aprovados, implantados ou utilizados por uma organização.

## 18. Referências

- ISO/IEC 27001:2022 — *Information security, cybersecurity and privacy protection — Information security management systems — Requirements*.
- ISO/IEC 27001:2022/Amd 1:2024 — *Information security, cybersecurity and privacy protection — Information security management systems — Requirements — Amendment 1: Climate action changes*.
- ISO/IEC 27005:2022 — *Guidance on managing information security risks*.
- ISO/IEC 27002:2022 — *Information security, cybersecurity and privacy protection — Information security controls*.
- ISO 31000:2018 — *Risk management — Guidelines*.

Consultar as publicações oficiais para confirmar os requisitos, as definições, as edições e as orientações aplicáveis.
