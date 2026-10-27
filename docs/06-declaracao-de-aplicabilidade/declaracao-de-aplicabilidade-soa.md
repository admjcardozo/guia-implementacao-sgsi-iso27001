# Declaração de Aplicabilidade (SoA)

## 1. Objetivo

Este documento apresenta uma metodologia de referência para elaboração, manutenção e controle da Declaração de Aplicabilidade (*Statement of Applicability* — SoA) no contexto de um Sistema de Gestão de Segurança da Informação (SGSI) baseado na ISO/IEC 27001:2022.

A Declaração de Aplicabilidade registra os controles de segurança da informação considerados necessários pela organização, a justificativa para sua inclusão, a situação de implementação e a justificativa para a exclusão de controles do Anexo A, conforme aplicável.

Seus objetivos são:

- estabelecer rastreabilidade entre riscos, decisões de tratamento e controles;
- documentar a seleção dos controles necessários;
- registrar justificativas de inclusão e exclusão;
- apresentar a situação de implementação dos controles;
- apoiar o planejamento, o monitoramento e a auditoria do SGSI;
- manter uma visão controlada e atualizada dos controles considerados no sistema de gestão;
- apoiar a demonstração da coerência entre avaliação de riscos, tratamento, controles e decisões de governança.

Este documento é um guia metodológico. Não representa uma SoA preenchida e aprovada para uma organização real.

## 2. Referências normativas

A referência principal é a **ISO/IEC 27001:2022**, incluindo a Emenda 1:2024, especialmente a cláusula 6.1.3, relativa ao tratamento de riscos de segurança da informação.

A cláusula 6.1.3 estabelece requisitos para o processo de tratamento de riscos, incluindo a seleção das opções de tratamento, a determinação dos controles necessários, a comparação com os controles do Anexo A, a elaboração da Declaração de Aplicabilidade, a formulação do plano de tratamento e a obtenção das aprovações pertinentes.

A ISO/IEC 27002:2022 pode ser utilizada como referência complementar para orientação sobre os controles de segurança da informação.

A Emenda 1:2024 da ISO/IEC 27001 introduz considerações relacionadas às mudanças climáticas no contexto organizacional. Quando esse tema for relevante para o contexto, os requisitos e as necessidades pertinentes devem ser considerados no processo de gestão do SGSI e, quando aplicável, na determinação dos controles necessários.

A consulta às publicações oficiais é necessária para confirmar a redação integral e a aplicação dos requisitos normativos.

## 3. O que é a Declaração de Aplicabilidade

A Declaração de Aplicabilidade é uma informação documentada do SGSI que consolida os controles necessários e registra as justificativas e informações de implementação exigidas pela norma.

Conforme a cláusula 6.1.3(d) da ISO/IEC 27001:2022, a SoA deve incluir:

- os controles necessários;
- a justificativa para a inclusão de cada controle necessário;
- a indicação de que os controles necessários estão implementados ou não;
- a justificativa para excluir controles do Anexo A.

A SoA não deve ser tratada apenas como uma cópia do Anexo A da norma. A organização deve determinar os controles necessários a partir do processo de tratamento de riscos e de outras obrigações e necessidades aplicáveis.

A comparação com o Anexo A serve para verificar se algum controle necessário foi inadvertidamente omitido. O Anexo A apresenta uma referência de controles possíveis, não uma lista que substitui a avaliação de riscos da organização.

A organização pode determinar controles adicionais que não estejam listados no Anexo A. Quando esses controles forem necessários, também devem ser considerados na SoA, com suas justificativas e informações pertinentes.

## 4. Relação entre riscos, controles e SoA

A elaboração da SoA deve manter rastreabilidade entre os principais elementos do SGSI:

1. contexto, escopo e requisitos aplicáveis;
2. avaliação de riscos de segurança da informação;
3. decisões e opções de tratamento;
4. determinação dos controles necessários;
5. comparação com os controles do Anexo A;
6. justificativas de inclusão e exclusão;
7. situação de implementação dos controles necessários;
8. plano de tratamento e evidências relacionadas;
9. aprovações e decisões relativas aos riscos residuais.

A relação entre riscos e controles deve ser documentada de forma que seja possível compreender por que determinado controle foi selecionado e quais riscos, obrigações ou necessidades ele ajuda a tratar.

Um controle pode ser necessário para tratar mais de um risco. Da mesma forma, um risco pode exigir vários controles complementares.

A rastreabilidade não deve ser limitada a uma correspondência simplificada de um risco para um único controle quando o cenário exigir um conjunto de medidas.

A SoA, o registro de riscos e o Plano de Tratamento de Riscos possuem finalidades diferentes. A organização deve manter referências coerentes entre esses documentos, sem presumir que a existência de um deles comprova a execução das atividades descritas nos demais.

## 5. Processo de elaboração da SoA

### 5.1. Confirmar o contexto e o escopo

Antes de elaborar a SoA, a organização deve confirmar o escopo do SGSI, os processos abrangidos, os ativos relevantes, as interfaces e as obrigações aplicáveis.

A análise de contexto deve considerar as questões internas e externas pertinentes, incluindo as mudanças climáticas quando forem relevantes para a organização, bem como as necessidades e expectativas das partes interessadas pertinentes.

Uma alteração no contexto, no escopo ou nos requisitos aplicáveis pode modificar a seleção de controles e deve ser avaliada quanto aos seus impactos na SoA.

### 5.2. Analisar os resultados da avaliação de riscos

Os resultados da avaliação de riscos devem ser examinados para identificar os controles e as medidas necessários ao tratamento dos cenários identificados.

A decisão deve considerar os critérios de risco aprovados, os níveis de risco, os requisitos aplicáveis e as opções de tratamento selecionadas.

A SoA não deve ser preenchida apenas com base em uma lista genérica de controles. A seleção deve refletir a análise realizada e as necessidades da organização.

### 5.3. Determinar os controles necessários

A organização deve determinar os controles necessários para implementar as opções de tratamento escolhidas.

A seleção deve considerar, conforme aplicável:

- riscos identificados;
- requisitos legais, regulatórios e contratuais;
- necessidades operacionais;
- compromissos com partes interessadas;
- dependências tecnológicas;
- requisitos de clientes;
- controles já existentes;
- objetivos de segurança da informação;
- necessidades de proteção da informação e continuidade operacional.

A seleção não deve ser feita apenas com base na disponibilidade de ferramentas tecnológicas ou em uma lista genérica de controles.

Os controles necessários podem ser selecionados de fontes diversas ou desenvolvidos conforme a necessidade, desde que a decisão seja fundamentada e mantenha coerência com os requisitos aplicáveis.

### 5.4. Comparar com o Anexo A

Após determinar os controles necessários, a organização deve compará-los com os controles do Anexo A da ISO/IEC 27001:2022 para verificar se algum controle necessário foi omitido.

Essa comparação não significa que todos os controles do Anexo A sejam automaticamente necessários em qualquer contexto. A decisão deve ser fundamentada nos requisitos normativos, nos riscos, nas obrigações e nas necessidades da organização.

A organização também pode determinar controles necessários que não estejam descritos no Anexo A, quando isso for apropriado ao seu contexto e aos riscos identificados.

A comparação com o Anexo A não substitui a determinação dos controles necessários. Sua finalidade é verificar se algum controle relevante deixou de ser considerado.

### 5.5. Registrar justificativas de inclusão

Para cada controle necessário, deve ser registrada a justificativa de inclusão.

A justificativa deve explicar por que o controle é necessário, considerando a origem da necessidade, o risco relacionado, a obrigação aplicável ou outro fundamento pertinente.

Quando possível, a justificativa deve indicar referências ao registro de riscos, aos requisitos aplicáveis ou a outros documentos que sustentem a decisão.

Expressões genéricas, como “boa prática” ou “segurança”, sem explicação adicional, podem dificultar a análise crítica e a auditoria.

### 5.6. Registrar justificativas de exclusão

Para cada controle do Anexo A excluído, deve ser registrada uma justificativa específica.

A justificativa deve refletir a análise realizada e ser coerente com o contexto, o escopo, os riscos e os requisitos aplicáveis.

A decisão não deve decorrer apenas da ausência de ferramenta, orçamento, responsável designado ou implementação. Essas condições podem indicar necessidades de planejamento ou tratamento, mas não constituem, isoladamente, justificativas suficientes para excluir um controle necessário.

Quando um controle não for considerado necessário, a justificativa deve demonstrar a lógica da decisão no contexto avaliado.

### 5.7. Registrar a situação de implementação

A SoA deve indicar se os controles necessários estão implementados ou não.

Como complemento gerencial, a organização pode utilizar estados mais detalhados, como:

- não iniciado;
- planejado;
- em implementação;
- implementado;
- implementado parcialmente;
- pendente de validação;
- não implementado.

Esses estados adicionais são uma convenção metodológica. A organização deve definir seus significados e evitar que sejam confundidos com a indicação normativa de implementação.

A classificação de um controle como implementado deve ser sustentada por evidências apropriadas. A existência de uma política, contrato, ferramenta ou plano, isoladamente, não comprova necessariamente que o controle esteja implementado e opere eficazmente.

Quando a organização utilizar estados adicionais, deve estabelecer como eles serão consolidados para apresentar de forma inequívoca se o controle necessário está implementado ou não.

## 6. Estrutura recomendada da SoA

A estrutura abaixo é uma proposta metodológica de registro. Os campos podem ser adaptados às necessidades de governança, auditoria e gestão, preservando as informações requeridas pela ISO/IEC 27001:2022.

| Campo | Finalidade |
|---|---|
| ID do controle | Identificar o controle de maneira única. |
| Referência normativa | Registrar a referência ao controle do Anexo A, quando aplicável. |
| Nome do controle | Apresentar uma descrição controlada do controle. |
| Origem da necessidade | Identificar o risco, a obrigação ou outra necessidade que motivou a seleção. |
| Justificativa de inclusão | Explicar por que o controle foi considerado necessário. |
| Aplicabilidade | Registrar a decisão documentada relativa ao controle do Anexo A, quando pertinente. |
| Justificativa de exclusão | Explicar por que um controle do Anexo A foi excluído. |
| Situação de implementação | Indicar se o controle necessário está implementado ou não. |
| Responsável | Identificar o responsável pela gestão ou implementação. |
| Evidências | Referenciar registros, documentos ou outros elementos de comprovação. |
| Riscos relacionados | Identificar os riscos tratados ou influenciados pelo controle. |
| Plano de tratamento | Referenciar as ações pendentes, quando aplicável. |
| Data da revisão | Registrar quando a informação foi revisada. |
| Aprovação | Registrar a aprovação conforme a governança definida. |

Nem todos os campos adicionais são requisitos explícitos da norma. São elementos de gestão recomendados para melhorar a rastreabilidade e a manutenção da SoA.

A organização deve assegurar que o registro identifique todos os controles necessários, inclusive aqueles que não constem do Anexo A, quando houver.

## 7. Exemplo hipotético de registro

O exemplo a seguir é ilustrativo e não representa uma avaliação ou implementação real.

| Campo | Exemplo |
|---|---|
| ID do controle | EX-ACESSO-01 |
| Controle de referência | Controle relacionado à gestão de direitos de acesso, conforme catálogo oficial adotado |
| Origem da necessidade | Risco hipotético de manutenção de privilégios incompatíveis com a função do usuário |
| Justificativa de inclusão | A organização hipotética necessita estabelecer e revisar direitos de acesso de acordo com as responsabilidades e os riscos identificados. |
| Aplicabilidade | Incluído no exemplo didático |
| Situação de implementação | Não avaliada |
| Responsável | A definir pela organização hipotética |
| Evidências | Não apresentadas |
| Riscos relacionados | Risco hipotético de acesso indevido a informações restritas |
| Plano de tratamento | A definir após avaliação e aprovação |
| Data da revisão | Não aplicável ao exemplo |
| Aprovação | Não realizada |

Este exemplo não deve ser utilizado como declaração de conformidade, evidência de implementação ou afirmação sobre uma organização real.

Para uma SoA efetiva, a identificação, a denominação e a referência de cada controle devem ser verificadas na edição oficial da ISO/IEC 27001:2022 adotada pela organização.

## 8. Exclusão de controles do Anexo A

Quando um controle do Anexo A não for considerado necessário, a organização deve registrar a justificativa de exclusão na SoA.

A justificativa deve refletir a análise realizada e ser coerente com o contexto, o escopo, os riscos e os requisitos aplicáveis.

A exclusão não deve decorrer apenas de:

- ausência de ferramenta ou orçamento;
- inexistência de responsável designado;
- falta de implementação;
- preferência operacional;
- desconhecimento do controle;
- decisão sem análise documentada.

Essas situações podem representar necessidades de planejamento ou tratamento, mas não constituem, isoladamente, justificativas suficientes para excluir um controle necessário.

A decisão deve considerar se o controle é necessário para tratar riscos ou cumprir requisitos aplicáveis. Quando necessário, devem ser avaliadas alternativas adequadas, sem presumir que uma alternativa elimina automaticamente a necessidade original.

A justificativa deve ser suficientemente clara para permitir a revisão posterior da decisão e a compreensão de sua fundamentação por pessoas autorizadas, incluindo auditores.

## 9. Controles adicionais e requisitos externos

A organização pode determinar controles necessários que não estejam listados no Anexo A, desde que a seleção seja fundamentada.

Esses controles podem decorrer, por exemplo, de:

- riscos específicos do negócio;
- requisitos legais ou regulatórios;
- compromissos contratuais;
- necessidades tecnológicas;
- características do ambiente operacional;
- requisitos de clientes ou parceiros;
- objetivos específicos de segurança da informação.

A organização deve documentar a origem da necessidade e a forma pela qual o controle contribui para o tratamento do risco ou o atendimento da obrigação correspondente.

A inclusão de controles adicionais não elimina a necessidade de comparar os controles necessários com o Anexo A.

Quando um controle adicional for necessário, sua identificação, justificativa de inclusão e situação de implementação devem constar da SoA, conforme aplicável. A organização deve manter referências que permitam relacioná-lo aos riscos, requisitos ou decisões que fundamentaram sua seleção.

## 10. Relação com o Plano de Tratamento de Riscos

A SoA e o Plano de Tratamento de Riscos possuem finalidades relacionadas, mas distintas.

A SoA consolida os controles necessários, suas justificativas, a situação de implementação e as justificativas de exclusão dos controles do Anexo A.

O Plano de Tratamento de Riscos documenta as ações selecionadas para tratar os riscos, incluindo responsabilidades, prazos e outros elementos necessários ao acompanhamento.

Um controle necessário que ainda não esteja implementado pode exigir uma ação de tratamento. Nesse caso, a SoA e o plano devem manter referências consistentes entre si.

A cláusula 6.1.3 da ISO/IEC 27001:2022 também prevê a aprovação do plano de tratamento pelos proprietários dos riscos e a aceitação dos riscos residuais por esses proprietários.

Essas decisões devem ser documentadas de acordo com a governança da organização. A aprovação do plano não deve ser interpretada como aceitação automática de todos os riscos residuais.

A conclusão de uma ação deve ser acompanhada da avaliação apropriada para verificar a implementação do controle e, quando pertinente, a eficácia das medidas adotadas.

## 11. Aprovação, manutenção e controle de mudanças

A organização deve estabelecer responsabilidades para revisar, aprovar, atualizar e controlar a SoA.

A governança definida deve esclarecer:

- quem propõe alterações;
- quem valida as justificativas;
- quem aprova a SoA;
- como as mudanças são registradas;
- como são mantidas as versões anteriores;
- como a SoA é disponibilizada às pessoas autorizadas;
- quais eventos exigem revisão extraordinária.

A SoA deve ser revisada quando houver mudanças relevantes nos riscos, no escopo, nos requisitos aplicáveis, nos controles ou nas decisões de tratamento.

A periodicidade da revisão deve ser definida pela organização considerando o contexto e os critérios de governança estabelecidos.

As alterações devem preservar a rastreabilidade entre a versão anterior, a decisão de mudança, a justificativa e a aprovação pertinente.

## 12. Evidências e rastreabilidade

A organização deve manter informações documentadas suficientes para demonstrar a lógica da seleção dos controles e a situação registrada.

Como exemplos de evidências relacionadas, conforme aplicável:

- avaliações de riscos;
- decisões de tratamento;
- justificativas de inclusão e exclusão;
- aprovações;
- registros de implementação;
- procedimentos e políticas;
- resultados de testes;
- registros de monitoramento;
- relatórios de auditoria;
- histórico de alterações da SoA;
- registros de aprovação do plano de tratamento;
- registros de aceitação dos riscos residuais pelos proprietários dos riscos, conforme aplicável.

A evidência deve sustentar a afirmação realizada. Um controle registrado como implementado deve possuir comprovação compatível com sua natureza e com os critérios definidos.

A SoA não substitui os documentos operacionais, os registros de execução ou as evidências específicas dos controles.

A existência de uma referência documental não comprova automaticamente que o controle foi executado, que está operando eficazmente ou que o risco foi reduzido ao nível pretendido.

## 13. Critérios de qualidade

Antes de aprovar ou revisar a SoA, recomenda-se verificar:

- [ ] Os controles necessários foram determinados a partir do processo de tratamento de riscos e das necessidades aplicáveis.
- [ ] Foi realizada a comparação com os controles do Anexo A.
- [ ] Os controles necessários, inclusive os adicionais, estão identificados.
- [ ] Os controles necessários possuem justificativas de inclusão.
- [ ] Os controles do Anexo A excluídos possuem justificativas documentadas.
- [ ] A situação de implementação dos controles necessários está registrada.
- [ ] As referências aos riscos e às ações de tratamento são rastreáveis.
- [ ] As informações são coerentes com o escopo do SGSI.
- [ ] As justificativas são específicas e compreensíveis.
- [ ] As aprovações seguem as autoridades definidas.
- [ ] A versão e o histórico de alterações estão controlados.
- [ ] As informações registradas são sustentadas por evidências apropriadas.
- [ ] Os controles adicionais, quando existentes, estão identificados e justificados.
- [ ] A relação com o plano de tratamento e a aceitação dos riscos residuais está documentada.

A conclusão desta verificação indica que a SoA foi analisada segundo os critérios definidos. Não constitui, isoladamente, comprovação de conformidade integral com a ISO/IEC 27001:2022.

## 14. Limitações e adaptação

Este documento é um guia metodológico para fins educacionais e de estruturação profissional.

A estrutura apresentada não representa uma SoA efetiva de uma organização, não determina previamente quais controles devem ser selecionados e não comprova a implementação de qualquer controle.

Para uso em um SGSI real, a organização deve:

1. confirmar o escopo e os requisitos aplicáveis;
2. realizar e documentar a avaliação de riscos;
3. determinar os controles necessários;
4. comparar os controles necessários com o Anexo A;
5. justificar inclusões e exclusões;
6. registrar a situação de implementação;
7. manter rastreabilidade com o Plano de Tratamento de Riscos;
8. obter as aprovações previstas na governança;
9. registrar a aprovação do plano de tratamento e a aceitação dos riscos residuais pelos proprietários dos riscos, conforme aplicável;
10. manter a SoA atualizada e controlada.

A decisão sobre a aplicabilidade de controles deve ser baseada em análise documentada, não em pressupostos genéricos.

## 15. Documentos relacionados

Este documento deve ser articulado com:

- Documento Mestre de Implementação do SGSI;
- Análise de Contexto e Partes Interessadas;
- Definição do Escopo do SGSI;
- Política de Segurança da Informação;
- Papéis, Responsabilidades e Autoridades do SGSI;
- Metodologia de Gestão de Riscos de Segurança da Informação;
- Registro de Riscos;
- Plano de Tratamento de Riscos;
- procedimentos e registros dos controles de segurança;
- processos de monitoramento, auditoria e melhoria contínua.

A existência de um documento no repositório representa sua inclusão na estrutura de referência, não a comprovação de aprovação ou implementação organizacional.

## 16. Referências

- ISO/IEC 27001:2022 — Information security, cybersecurity and privacy protection — Information security management systems — Requirements.
- ISO/IEC 27001:2022/Amd 1:2024 — Information security, cybersecurity and privacy protection — Information security management systems — Requirements — Amendment 1: Climate action changes.
- ISO/IEC 27002:2022 — Information security, cybersecurity and privacy protection — Information security controls.

Consultar as publicações oficiais para confirmar os requisitos, as referências, as edições e as orientações aplicáveis.

