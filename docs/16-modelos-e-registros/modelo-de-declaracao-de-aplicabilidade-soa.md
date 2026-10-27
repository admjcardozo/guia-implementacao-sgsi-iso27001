# Modelo de Declaração de Aplicabilidade (SoA)

## 1. Objetivo

Este documento apresenta um modelo de referência para estruturar e manter a Declaração de Aplicabilidade (*Statement of Applicability* — SoA) de um Sistema de Gestão de Segurança da Informação (SGSI).

A Declaração de Aplicabilidade documenta os controles necessários para o SGSI, as justificativas de inclusão, as justificativas para exclusões dos controles do Anexo A da ISO/IEC 27001:2022 e a situação de implementação dos controles necessários.

Este arquivo é um modelo para adaptação. Não representa uma Declaração de Aplicabilidade aprovada ou preenchida para uma organização real.

## 2. Referências normativas

A principal referência é a ISO/IEC 27001:2022, especialmente:

- **Cláusula 6.1.3 — Tratamento de riscos de segurança da informação:** estabelece requisitos relacionados à determinação dos controles necessários e à elaboração da Declaração de Aplicabilidade.
- **Cláusula 8.3 — Tratamento de riscos de segurança da informação:** relaciona-se à implementação do plano de tratamento e à retenção da informação documentada pertinente.
- **Cláusula 7.5 — Informação documentada:** relaciona-se ao controle e à manutenção da documentação do SGSI.

O Anexo A da ISO/IEC 27001:2022 contém um conjunto de controles de referência para comparação durante a determinação dos controles necessários.

A organização não deve presumir que todos os controles necessários estarão limitados ao Anexo A. Controles adicionais podem ser determinados conforme os riscos, os requisitos e o contexto organizacional.

## 3. Finalidade da Declaração de Aplicabilidade

A SoA estabelece uma visão rastreável dos controles considerados no tratamento dos riscos de segurança da informação.

Sua elaboração deve manter coerência com:

- Escopo do SGSI;
- Metodologia de avaliação de riscos;
- Resultados da avaliação de riscos;
- Decisões de tratamento;
- Plano de tratamento de riscos;
- Requisitos legais, regulatórios e contratuais aplicáveis;
- Necessidades e expectativas pertinentes das partes interessadas;
- Controles efetivamente implementados;
- Evidências disponíveis.

A SoA não deve ser tratada como uma simples lista de controles copiada do Anexo A. As justificativas e as informações de implementação devem refletir as decisões e as condições reais do SGSI.

## 4. Informações de identificação

Recomenda-se manter os seguintes dados de identificação:

| Campo | Preenchimento |
|---|---|
| Organização | A preencher |
| Identificador do documento | A definir |
| Escopo do SGSI | Referência ao documento de escopo aprovado |
| Responsável pela manutenção | A designar |
| Autoridade aprovadora | A definir conforme a governança |
| Versão | A definir |
| Data de elaboração | A preencher quando elaborado |
| Data de aprovação | A preencher após aprovação |
| Próxima revisão | A definir conforme os critérios organizacionais |
| Classificação da informação | A definir conforme as regras internas |

Os campos devem ser preenchidos somente quando houver informações e decisões reais. A presença desses campos não comprova aprovação ou implementação.

## 5. Determinação dos controles necessários

A organização deve determinar os controles necessários ao tratamento dos riscos de segurança da informação, considerando a metodologia aprovada e os requisitos aplicáveis.

O processo deve considerar, conforme pertinente:

1. Identificar os riscos avaliados;
2. Selecionar as opções de tratamento;
3. Determinar os controles necessários;
4. Comparar os controles necessários com o Anexo A;
5. Verificar se algum controle necessário não está representado adequadamente no conjunto de referência;
6. Documentar as justificativas de inclusão;
7. Documentar as justificativas para exclusões dos controles do Anexo A;
8. Registrar a situação de implementação dos controles necessários;
9. Manter a coerência com o plano de tratamento;
10. Submeter a documentação às aprovações definidas pela organização.

A determinação dos controles deve refletir os riscos e requisitos aplicáveis, e não somente a disponibilidade de recursos ou a facilidade de implementação.

## 6. Estrutura da Declaração de Aplicabilidade

A tabela abaixo apresenta os campos recomendados para cada controle.

| Campo | Orientação de preenchimento |
|---|---|
| Identificador do controle | Código de referência conforme a fonte normativa utilizada |
| Nome do controle | Denominação do controle |
| Fonte | Referência normativa ou fonte utilizada |
| Aplicabilidade | Indicação de inclusão ou exclusão no contexto avaliado |
| Justificativa de inclusão | Razão pela qual o controle foi considerado necessário |
| Justificativa de exclusão | Razão documentada para excluir um controle do Anexo A, quando aplicável |
| Riscos relacionados | Referências aos riscos que o controle ajuda a tratar |
| Requisitos relacionados | Requisitos legais, regulatórios, contratuais ou internos pertinentes |
| Situação de implementação | Estado real do controle |
| Evidência de implementação | Referência aos registros que sustentam a situação declarada |
| Responsável pelo controle | Pessoa ou função responsável |
| Ação relacionada | Referência ao plano de tratamento, quando aplicável |
| Data da avaliação | Data da última avaliação do controle |
| Próxima revisão | Data ou condição prevista para revisão |
| Observações | Informações complementares relevantes |

A organização pode adaptar a estrutura, desde que mantenha a informação documentada exigida e a rastreabilidade necessária.

## 7. Situação de implementação dos controles

A organização deve definir uma classificação de implementação clara, documentada e aplicada de forma consistente.

Uma escala possível é:

| Situação | Definição orientativa |
|---|---|
| Não iniciado | A implementação ainda não começou |
| Em planejamento | A abordagem de implementação está sendo definida |
| Em implementação | Existem atividades de implementação em andamento |
| Implementado | O controle foi implementado, conforme os critérios definidos |
| Implementado com pendências | O controle foi implementado parcialmente ou apresenta pendências relevantes, conforme a classificação adotada |
| Não avaliado | A situação ainda não foi avaliada |

Essa escala é uma proposta metodológica, não uma classificação obrigatória estabelecida pela ISO/IEC 27001:2022.

A organização deve definir o que significa cada situação e quais evidências são necessárias para utilizá-la.

A classificação **“implementado”** deve ser sustentada por evidências apropriadas. Quando necessário, a organização deve avaliar também a operação e a eficácia do controle, sem presumir que a mera existência de uma configuração ou documento demonstre o resultado esperado.

## 8. Justificativas de inclusão e exclusão

### 8.1 Justificativa de inclusão

A justificativa deve explicar por que o controle foi considerado necessário.

A fundamentação pode estar relacionada a:

- Tratamento de riscos;
- Requisitos legais ou regulatórios;
- Obrigações contratuais;
- Necessidades das partes interessadas;
- Requisitos internos;
- Necessidades operacionais;
- Proteção de ativos e informações.

A justificativa deve ser específica o suficiente para permitir compreender a decisão.

### 8.2 Justificativa de exclusão

Quando um controle do Anexo A for excluído, a justificativa deve ser documentada de acordo com a cláusula 6.1.3 da ISO/IEC 27001:2022.

A exclusão deve ser coerente com os riscos avaliados, os requisitos aplicáveis e as decisões de tratamento.

Não se deve excluir um controle apenas porque ele não foi implementado, porque sua implementação é difícil ou porque exige recursos. A ausência de implementação não constitui, isoladamente, justificativa adequada para excluir um controle necessário.

A aplicabilidade e a necessidade de cada controle devem ser avaliadas no contexto do SGSI.

## 9. Modelo de tabela para preenchimento

A tabela a seguir é um modelo vazio. Os códigos exemplificativos servem apenas para demonstrar a estrutura do registro.

| ID do controle | Nome do controle | Aplicabilidade | Justificativa | Situação de implementação | Evidência | Responsável |
|---|---|---|---|---|---|---|
| A definir | A preencher | A avaliar | A documentar | Não avaliado | A identificar | A designar |
| A definir | A preencher | A avaliar | A documentar | Não avaliado | A identificar | A designar |

A tabela não constitui uma SoA completa. A organização deve identificar e avaliar os controles pertinentes, inclusive os controles do Anexo A, sem limitar a análise às linhas ilustrativas deste modelo.

## 10. Exemplo hipotético de registro

O exemplo abaixo é fictício e demonstra apenas como uma justificativa pode ser redigida.

| Campo | Exemplo ilustrativo |
|---|---|
| Identificador | A definir conforme a fonte normativa utilizada |
| Controle | Revisão de acessos |
| Aplicabilidade | A avaliar no contexto organizacional |
| Justificativa de inclusão | Avaliar a necessidade de revisar direitos de acesso para reduzir o risco de manutenção de permissões incompatíveis com as responsabilidades atuais |
| Risco relacionado | A identificar no registro de riscos |
| Situação de implementação | Não avaliado |
| Evidência | A identificar |
| Responsável | A designar |

Este exemplo não atribui um código normativo específico nem declara que o controle tenha sido implementado. O identificador, a aplicabilidade e a situação real devem ser confirmados com base na fonte normativa e nas evidências pertinentes.

## 11. Relação com o plano de tratamento de riscos

A SoA e o plano de tratamento devem permanecer coerentes.

Quando um controle necessário ainda não estiver implementado ou exigir aprimoramento, a organização deve avaliar como a situação será tratada e registrar as ações pertinentes.

A rastreabilidade pode ser estruturada da seguinte forma:

| Elemento | Finalidade |
|---|---|
| Registro de riscos | Identifica e avalia os riscos |
| Plano de tratamento | Registra as ações selecionadas para tratar os riscos |
| Declaração de Aplicabilidade | Documenta os controles necessários, as justificativas e a situação de implementação |
| Evidências | Sustentam as declarações sobre a execução e a situação dos controles |

Essa relação permite verificar se as decisões de tratamento estão refletidas na seleção dos controles e se as situações declaradas são sustentadas por evidências.

## 12. Revisão e atualização da SoA

A Declaração de Aplicabilidade deve ser revista quando mudanças relevantes afetarem a avaliação de riscos, as decisões de tratamento ou a situação dos controles.

Podem motivar uma revisão:

- Alterações no escopo do SGSI;
- Mudanças significativas nos processos;
- Novos riscos ou mudanças nos riscos existentes;
- Incidentes relevantes;
- Alterações legais, regulatórias ou contratuais;
- Mudanças nos controles implementados;
- Resultados de auditorias;
- Mudanças em fornecedores;
- Resultados de análises críticas pela direção;
- Mudanças na metodologia de gestão de riscos.

A organização deve definir responsáveis, critérios de revisão e mecanismos de aprovação.

A atualização documental deve refletir as alterações efetivamente avaliadas e aprovadas. Não se deve alterar a situação de um controle sem evidências adequadas.

## 13. Controle da informação documentada

A SoA deve ser mantida e controlada conforme os requisitos aplicáveis do SGSI.

Recomenda-se estabelecer:

- Identificação e versão;
- Responsável pela manutenção;
- Autoridade de aprovação;
- Histórico de alterações;
- Regras de acesso;
- Referências às evidências;
- Critérios de retenção;
- Proteção contra alterações não autorizadas.

A SoA pode conter informações sobre riscos, controles e fragilidades. A organização deve definir sua classificação e proteger o documento conforme a sensibilidade das informações registradas.

## 14. Critérios de qualidade da SoA

Antes de considerar a SoA adequadamente estruturada, recomenda-se verificar se:

- Os controles necessários foram determinados com base nos riscos e requisitos aplicáveis;
- A comparação com o Anexo A foi realizada;
- As justificativas de inclusão estão documentadas;
- As justificativas para exclusões dos controles do Anexo A estão documentadas;
- A situação de implementação reflete a realidade;
- As evidências são identificáveis e pertinentes;
- Os controles estão relacionados aos riscos e às ações de tratamento;
- Os responsáveis estão definidos quando aplicável;
- A documentação está atualizada;
- As aprovações necessárias foram registradas.

Esta lista é uma ferramenta metodológica e não constitui declaração de conformidade ou certificação.

## 15. Limitações de aplicação

Este modelo deve ser adaptado à metodologia de gestão de riscos, à governança e ao contexto da organização.

Ele não substitui a consulta à versão oficial e vigente da ISO/IEC 27001:2022 nem a avaliação dos controles pertinentes ao SGSI.

A presença de um controle na SoA não comprova, isoladamente, que ele foi implementado ou que funciona eficazmente. A situação declarada deve ser sustentada por evidências apropriadas.

Este documento é um modelo de referência e não representa uma Declaração de Aplicabilidade aprovada para uma organização real.

## 16. Histórico de alterações

| Versão | Descrição | Situação |
|---|---|---|
| 1.0 | Criação do modelo de referência para Declaração de Aplicabilidade | Modelo para adaptação |

A situação indicada descreve o estado documental deste arquivo no projeto e não comprova aprovação, implementação ou validação em uma organização real.
