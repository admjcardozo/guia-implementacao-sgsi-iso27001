# Plano de Tratamento de Riscos de Segurança da Informação

## 1. Objetivo

Este documento estabelece uma metodologia de referência para elaborar, aprovar, executar, monitorar e revisar o Plano de Tratamento de Riscos de Segurança da Informação no contexto de um Sistema de Gestão de Segurança da Informação (SGSI).

O plano tem como objetivos:

- documentar as opções de tratamento selecionadas para os riscos identificados;
- definir ações, responsáveis, prazos e recursos necessários;
- estabelecer critérios para acompanhar a execução das ações;
- manter rastreabilidade entre riscos, controles e decisões de tratamento;
- distinguir a estimativa de risco residual esperado da avaliação do risco residual após o tratamento;
- apoiar a aprovação do plano pelos proprietários dos riscos e a aceitação formal dos riscos residuais;
- fornecer informações para o monitoramento e a melhoria contínua do SGSI.

Este documento é um guia metodológico. Não representa um plano de tratamento aprovado ou executado por uma organização real.

## 2. Referências normativas

A referência principal é a **ISO/IEC 27001:2022**, incluindo a **Emenda 1:2024**, que introduziu considerações relacionadas às mudanças climáticas nos requisitos relativos ao contexto da organização.

Para o tratamento de riscos, são especialmente relevantes:

- **Cláusula 6.1.2:** avaliação de riscos de segurança da informação.
- **Cláusula 6.1.3:** tratamento de riscos de segurança da informação.
- **Cláusula 8.2:** avaliação de riscos de segurança da informação em intervalos planejados e quando mudanças significativas forem propostas ou ocorrerem.
- **Cláusula 8.3:** implementação do tratamento de riscos conforme os planos estabelecidos.

A cláusula 6.1.3 contempla a seleção de opções de tratamento, a determinação dos controles necessários, a comparação desses controles com o Anexo A, a elaboração da Declaração de Aplicabilidade (SoA), a formulação do plano de tratamento e as aprovações requeridas, incluindo a aprovação do plano pelos proprietários dos riscos e a aceitação dos riscos residuais por esses proprietários.

A **ISO/IEC 27005:2022** fornece orientação complementar para a gestão de riscos de segurança da informação. A ISO/IEC 27002:2022 pode ser utilizada como referência para orientação sobre controles de segurança da informação. A ISO 31000:2018 pode complementar a abordagem de gestão de riscos quando adotada pela organização.

A Emenda 1:2024 da ISO/IEC 27001 exige que a organização determine se as mudanças climáticas são uma questão relevante para seu contexto e considere requisitos pertinentes das partes interessadas. Quando fatores climáticos forem relevantes para os objetivos, processos, ativos ou dependências do SGSI, seus efeitos devem ser considerados na avaliação e no tratamento dos riscos pertinentes. Não se deve presumir que mudanças climáticas constituam automaticamente um risco de segurança da informação em todos os contextos.

Este documento não reproduz integralmente o texto das normas. A consulta às publicações oficiais é necessária para confirmar os requisitos aplicáveis e sua interpretação no contexto do SGSI.

## 3. Conceitos fundamentais

Para aplicação desta metodologia, são utilizados os seguintes conceitos:

- **Risco identificado:** cenário de risco registrado e submetido ao processo de avaliação.
- **Risco inerente:** estimativa do risco antes de considerar os controles existentes, conforme a convenção metodológica adotada pela organização.
- **Risco atual:** estimativa do risco nas condições existentes no momento da avaliação, considerando os controles efetivamente implementados e as evidências disponíveis sobre sua operação e eficácia.
- **Opção de tratamento:** abordagem selecionada para modificar, evitar, compartilhar ou aceitar um risco, conforme aplicável.
- **Ação de tratamento:** atividade definida para implementar a opção de tratamento escolhida.
- **Controle:** medida que mantém e/ou modifica o risco.
- **Responsável pela ação:** pessoa ou função encarregada de executar ou coordenar uma atividade do plano.
- **Proprietário do risco:** pessoa ou função designada para responder pela gestão do risco e pelas decisões que lhe competem, incluindo a aprovação do plano de tratamento e a aceitação do risco residual.
- **Risco residual esperado:** estimativa do risco que deverá permanecer após a implementação das medidas de tratamento planejadas. Trata-se de uma previsão, não de uma comprovação de resultado.
- **Risco residual reavaliado:** estimativa do risco remanescente após a implementação das medidas de tratamento e a avaliação das condições e dos controles resultantes.
- **Aceitação do risco residual:** decisão formal do proprietário do risco de aceitar o risco remanescente, conforme os critérios e os requisitos aplicáveis.
- **Evidência de implementação:** informação que sustenta a afirmação de que uma ação ou controle foi implementado.
- **Eficácia do tratamento:** grau em que as medidas adotadas produzem os resultados esperados na modificação do risco.

Os termos risco inerente, risco atual e risco residual devem ser utilizados de maneira consistente com a metodologia de gestão de riscos do SGSI.

Nesta documentação, o risco atual é a referência operacional para a decisão de tratamento. O risco residual esperado é uma estimativa anterior à confirmação dos resultados. O risco residual reavaliado corresponde ao resultado da avaliação após a implementação das medidas de tratamento.

A organização deve documentar as definições, os momentos de avaliação e os critérios utilizados, evitando comparações inconsistentes entre resultados.

A implementação de um controle deve ser distinguida de sua eficácia. A existência de uma política, ferramenta ou procedimento, por si só, não demonstra necessariamente que o risco foi reduzido ao nível esperado.

O proprietário do risco e o responsável pela ação de tratamento exercem funções distintas. Uma mesma pessoa pode assumir ambas, desde que isso esteja definido e seja compatível com as responsabilidades e autoridades estabelecidas.

## 4. Princípios do plano de tratamento

O planejamento do tratamento deve observar os seguintes princípios.

### 4.1. Fundamentação em riscos

As ações devem estar vinculadas a riscos avaliados e a decisões de tratamento documentadas. A inclusão de uma atividade no plano deve possuir justificativa compreensível.

### 4.2. Responsabilidade definida

Cada ação deve possuir um responsável designado, com atribuições e autoridade compatíveis com sua execução.

O responsável pela ação não é necessariamente o proprietário do risco. As duas responsabilidades devem ser distinguidas quando atribuídas a pessoas ou funções diferentes.

### 4.3. Prazo e recursos

As ações devem possuir prazos aprovados e recursos compatíveis com sua complexidade e prioridade.

Quando houver dependências, restrições orçamentárias ou necessidade de contratação, essas condições devem ser registradas.

### 4.4. Rastreabilidade

O plano deve manter referências aos riscos, às decisões de tratamento, aos controles selecionados, à SoA e às evidências de execução.

A rastreabilidade deve permitir compreender por que uma ação foi selecionada, qual risco pretende tratar, qual resultado se espera alcançar e como sua execução e seus efeitos serão avaliados.

### 4.5. Aprovação formal

O plano de tratamento deve ser aprovado pelos proprietários dos riscos, conforme a ISO/IEC 27001:2022 e os requisitos aplicáveis.

A aceitação dos riscos residuais também deve ser formalizada pelos respectivos proprietários dos riscos. A aprovação inicial do plano e a aceitação posterior dos riscos residuais são decisões distintas.

A aprovação do plano não deve ser interpretada como aceitação automática de todos os riscos que permanecerem após a implementação.

### 4.6. Monitoramento

A execução das ações deve ser acompanhada para identificar atrasos, impedimentos, alterações de escopo e riscos que permaneçam acima dos critérios de aceitação.

### 4.7. Atualização conforme o contexto

O plano deve ser revisto quando alterações relevantes nos processos, nas tecnologias, nos fornecedores, nas obrigações aplicáveis ou no contexto organizacional modificarem os riscos ou a adequação das medidas selecionadas.

## 5. Relação entre avaliação de riscos, SoA e plano de tratamento

O Plano de Tratamento de Riscos integra o processo de gestão de riscos do SGSI e deve permanecer coerente com a metodologia de avaliação de riscos e com a Declaração de Aplicabilidade.

A sequência metodológica de referência é:

1. estabelecer e manter os critérios de avaliação e aceitação de riscos;
2. identificar e avaliar os riscos de segurança da informação;
3. comparar os resultados com os critérios estabelecidos;
4. selecionar as opções de tratamento;
5. determinar os controles necessários para implementar as opções selecionadas;
6. comparar os controles necessários com os controles do Anexo A da ISO/IEC 27001:2022, verificando se algum controle necessário foi omitido;
7. elaborar ou atualizar a Declaração de Aplicabilidade;
8. formular o Plano de Tratamento de Riscos;
9. obter a aprovação do plano pelos proprietários dos riscos;
10. implementar e acompanhar as ações;
11. reavaliar os riscos após o tratamento;
12. obter e registrar a aceitação formal dos riscos residuais pelos respectivos proprietários.

Essa sequência é uma representação metodológica. As atividades podem exigir iterações, especialmente quando a análise de riscos, a seleção de controles ou a viabilidade das ações indicar a necessidade de rever decisões anteriores.

A comparação com o Anexo A não significa que todos os controles ali apresentados sejam automaticamente aplicáveis, nem limita a organização a utilizar somente esses controles. A organização deve determinar os controles necessários, considerar o Anexo A e justificar as inclusões e exclusões na SoA conforme os requisitos normativos.

O plano não substitui o registro de riscos nem a SoA. Cada documento possui uma finalidade específica:

- **Registro de riscos:** documenta os riscos identificados, as avaliações e as decisões relacionadas.
- **Declaração de Aplicabilidade:** documenta os controles necessários, as justificativas de inclusão, o estado de implementação e as justificativas para exclusões.
- **Plano de Tratamento de Riscos:** documenta as ações planejadas para implementar as decisões de tratamento.

As informações desses documentos devem permanecer coerentes e atualizadas. Uma mudança relevante no risco, no controle selecionado ou na estratégia de tratamento pode exigir a revisão dos documentos relacionados.

## 6. Seleção das opções de tratamento

A organização deve selecionar opções de tratamento adequadas aos riscos identificados, considerando os critérios aprovados, os objetivos do SGSI, os recursos disponíveis e as obrigações aplicáveis.

Entre as opções que podem ser consideradas estão:

### 6.1. Modificar o risco

Consiste em adotar controles ou outras medidas para alterar a probabilidade de ocorrência, as consequências ou outros fatores relevantes do risco.

Exemplos metodológicos:

- implementar autenticação multifator;
- revisar privilégios de acesso;
- estabelecer cópias de segurança e testar sua recuperação;
- melhorar o monitoramento de eventos de segurança;
- corrigir vulnerabilidades identificadas;
- estabelecer procedimentos de resposta a incidentes;
- aprimorar a gestão de mudanças;
- estabelecer processos de revisão de acessos e de segregação de funções.

A escolha de uma medida deve ser fundamentada no cenário avaliado. Os exemplos não constituem recomendações universais para todos os riscos.

### 6.2. Evitar o risco

Consiste em interromper, não iniciar ou modificar uma atividade ou condição que origina o risco, quando essa decisão for viável e apropriada.

A decisão deve considerar os impactos operacionais, estratégicos, contratuais e legais associados.

### 6.3. Compartilhar ou transferir parte do risco

Consiste em estabelecer mecanismos que distribuam ou transfiram determinadas responsabilidades ou consequências, como contratos, seguros ou serviços especializados, quando apropriado.

O compartilhamento ou a transferência não elimina automaticamente as responsabilidades da organização, suas obrigações legais ou todos os efeitos do risco. Os riscos relacionados a fornecedores e serviços terceirizados devem continuar sendo avaliados e acompanhados.

### 6.4. Aceitar o risco

Consiste em decidir formalmente manter o risco dentro dos critérios e limites de autoridade estabelecidos.

A aceitação deve possuir justificativa documentada e aprovação por autoridade apropriada, observando os requisitos aplicáveis e a governança da organização.

A aceitação de um risco não deve ser utilizada como substituto para o cumprimento de requisitos legais, regulatórios ou contratuais aplicáveis.

Quando a organização decidir aceitar um risco, deve registrar a justificativa, o responsável pela decisão, a data, o nível de risco considerado e eventuais condições, limitações ou datas para reavaliação.

Quando houver tratamento planejado, a aceitação do risco residual deve ocorrer com base na avaliação pertinente após o tratamento, não apenas na estimativa registrada antes da implementação.

## 7. Estrutura recomendada do plano

A organização pode utilizar uma planilha, sistema de gestão de riscos ou ferramenta equivalente para registrar as ações.

A estrutura de referência deve contemplar:

| Campo | Finalidade |
|---|---|
| ID da ação | Identificador único da ação de tratamento. |
| ID do risco | Referência ao risco que motivou a ação. |
| Descrição do risco | Síntese do cenário de risco associado. |
| Avaliação de referência | Registro do risco atual ou da última avaliação válida, conforme a metodologia. |
| Opção de tratamento | Registrar a opção selecionada. |
| Controle relacionado | Referenciar o controle ou conjunto de controles envolvidos, incluindo a correspondência com a SoA quando aplicável. |
| Descrição da ação | Especificar a atividade que será executada. |
| Resultado esperado | Definir o resultado pretendido. |
| Responsável pela ação | Identificar a pessoa ou função responsável pela execução. |
| Proprietário do risco | Identificar quem responde pela gestão do risco. |
| Prioridade | Registrar a prioridade conforme os critérios aprovados. |
| Prazo | Indicar a data-alvo aprovada. |
| Recursos necessários | Registrar recursos humanos, financeiros, técnicos ou externos. |
| Dependências | Identificar atividades, aprovações ou entregas necessárias. |
| Critério de conclusão | Definir como será verificado que a ação foi concluída. |
| Evidência esperada | Indicar os registros que sustentarão a conclusão. |
| Situação | Registrar o estado atual da ação. |
| Resultado da validação | Registrar a verificação da execução e, quando aplicável, da eficácia da medida. |
| Risco residual esperado | Registrar a estimativa após o tratamento planejado, quando utilizada. |
| Risco residual reavaliado | Registrar o resultado da avaliação após a implementação das medidas. |
| Aprovação do plano | Registrar a aprovação pelo proprietário do risco. |
| Aceitação do risco residual | Registrar a decisão formal do proprietário do risco. |
| Histórico | Preservar alterações, decisões e justificativas relevantes. |

Os campos adicionais são recomendações metodológicas. A organização deve manter as informações documentadas necessárias para cumprir os requisitos normativos e demonstrar a execução controlada do tratamento.

Quando uma ação tratar mais de um risco ou envolver vários controles, a ferramenta utilizada deve permitir a rastreabilidade entre as relações, evitando que a consolidação dos registros impeça a compreensão das decisões.

## 8. Priorização das ações

A priorização deve considerar os critérios de risco aprovados e as necessidades da organização.

Podem ser considerados:

- nível e natureza do risco;
- impacto potencial sobre os objetivos;
- obrigações legais, regulatórias e contratuais;
- criticidade dos processos e das informações;
- exposição a ameaças;
- eficácia dos controles existentes;
- dependências entre ações;
- tempo necessário para implementar as medidas;
- disponibilidade de recursos;
- consequências do adiamento;
- riscos introduzidos pela própria implementação;
- mudanças relevantes no contexto interno e externo.

Uma classificação como crítica, alta, média ou baixa pode ser utilizada como mecanismo gerencial, desde que seus critérios estejam documentados.

A prioridade não deve ser determinada exclusivamente pela pontuação de uma matriz de risco. Obrigações aplicáveis e outros fatores relevantes podem exigir ação ou escalonamento independentemente do resultado numérico.

Quando uma ação prioritária não puder ser executada no prazo inicialmente previsto, a justificativa, os impactos e a decisão sobre medidas compensatórias devem ser documentados e submetidos à autoridade apropriada.

A organização deve evitar que restrições de orçamento, capacidade ou prazo sejam tratadas automaticamente como justificativa para aceitar riscos acima dos limites aprovados.

## 9. Definição das ações e critérios de conclusão

Cada ação deve ser descrita de maneira objetiva, permitindo compreender o que será feito, por quem, em qual prazo e como sua conclusão será verificada.

Descrições genéricas, como “melhorar a segurança” ou “corrigir acessos”, não são suficientes para orientar a execução e comprovar a conclusão.

Como estrutura metodológica, uma ação pode conter:

- situação ou problema a ser tratado;
- atividade a executar;
- resultado esperado;
- responsável;
- prazo;
- dependências;
- recursos;
- critério de conclusão;
- evidência esperada;
- forma de validação do resultado, quando aplicável.

O critério de conclusão deve permitir verificar se a entrega foi realizada.

Quando a ação envolver um controle de segurança, a conclusão da atividade não significa automaticamente que o controle esteja eficaz ou que o risco tenha sido reduzido ao nível pretendido. Essa conclusão depende da avaliação e das evidências apropriadas.

Quando a implementação depender de fornecedor, contratação, aprovação externa ou mudança de arquitetura, essas dependências devem ser consideradas no planejamento e no acompanhamento.

## 10. Exemplo hipotético de plano de tratamento

A tabela a seguir apresenta um exemplo exclusivamente didático.

| Campo | Exemplo |
|---|---|
| ID da ação | AT-ACESSO-001 |
| ID do risco | R-ACESSO-001 |
| Descrição do risco | Manutenção de privilégios incompatíveis com a função atual de um usuário. |
| Avaliação de referência | A determinar segundo a metodologia hipotética. |
| Opção de tratamento | Modificar o risco. |
| Controle relacionado | Gestão e revisão dos direitos de acesso, conforme os controles determinados pela organização. |
| Descrição da ação | Definir e executar um processo periódico de revisão de privilégios, incluindo registro das decisões e correção das incompatibilidades identificadas. |
| Resultado esperado | Reduzir a possibilidade de manutenção de acessos incompatíveis com as responsabilidades atribuídas. |
| Responsável | A definir pela organização hipotética. |
| Proprietário do risco | A designar conforme a governança hipotética. |
| Prioridade | A determinar segundo os critérios de risco aprovados. |
| Prazo | A definir. |
| Recursos necessários | A estimar após avaliação do ambiente e do escopo. |
| Critério de conclusão | Processo definido, revisão executada e decisões registradas conforme os critérios aprovados. |
| Evidência esperada | Procedimento aprovado, registros da revisão, decisões e comprovação das correções realizadas. |
| Situação | Não iniciado no exemplo. |
| Resultado da validação | Não realizado. |
| Risco residual esperado | Não estimado. |
| Risco residual reavaliado | Não avaliado. |
| Aprovação do plano | Não realizada. |
| Aceitação do risco residual | Não realizada. |

Este exemplo não representa uma ação executada, um controle implementado ou uma constatação sobre uma organização real.

Os responsáveis, prazos, prioridades, recursos e critérios definitivos devem ser estabelecidos a partir da avaliação de riscos e da governança da organização que utilizar o modelo.

## 11. Aprovação do plano e aceitação de riscos residuais

A organização deve estabelecer um processo formal para aprovar o plano de tratamento e obter a aceitação dos riscos residuais pelos proprietários dos riscos, conforme os requisitos aplicáveis.

O processo deve distinguir:

- aprovação das opções de tratamento;
- aprovação do plano e dos recursos;
- autorização para execução;
- validação da conclusão das ações;
- avaliação dos riscos após o tratamento;
- aceitação formal dos riscos residuais.

Essas decisões podem ocorrer em momentos diferentes e devem ser registradas de forma que sua sequência e seus responsáveis sejam compreensíveis.

A aprovação do plano de tratamento pelos proprietários dos riscos é distinta da aceitação dos riscos residuais. A primeira autoriza o planejamento do tratamento conforme a governança estabelecida; a segunda registra a decisão sobre o risco que permanece após a avaliação pertinente.

A aprovação do plano não deve ser interpretada como aceitação automática de todos os riscos residuais futuros. A avaliação após o tratamento pode revelar que as medidas foram insuficientes, que novos riscos surgiram ou que as condições originalmente consideradas se alteraram.

Quando o risco residual permanecer acima dos critérios de aceitação, a organização deve avaliar novas opções de tratamento ou escalar a decisão conforme sua governança.

A aceitação deve respeitar as obrigações aplicáveis e os limites de autoridade definidos. Não se deve presumir que qualquer pessoa possa aceitar qualquer nível de risco.

Os registros de aprovação e aceitação devem identificar:

- risco e avaliação considerados;
- justificativa da decisão;
- proprietário do risco e autoridade envolvida;
- data da decisão;
- condições ou restrições estabelecidas;
- necessidade de monitoramento ou reavaliação;
- medidas adicionais previstas, quando houver.

## 12. Implementação e acompanhamento das ações

A execução do plano deve ser acompanhada de acordo com a criticidade dos riscos, os prazos e as regras de governança estabelecidas.

O acompanhamento deve permitir identificar:

- ações concluídas;
- ações em andamento;
- ações atrasadas;
- impedimentos;
- dependências não atendidas;
- mudanças de escopo;
- necessidade de recursos adicionais;
- evidências pendentes;
- riscos que permanecem sem tratamento suficiente;
- controles cuja eficácia ainda não foi validada.

Quando houver atraso, mudança ou impedimento relevante, a situação deve ser registrada e submetida à análise apropriada.

A alteração de prazos ou escopo deve possuir justificativa e aprovação conforme as regras estabelecidas.

O acompanhamento pode ser realizado por reuniões de governança, indicadores, relatórios, sistemas de gestão ou outros mecanismos adequados.

A frequência de acompanhamento deve ser proporcional à prioridade das ações, à exposição ao risco e às necessidades de decisão da organização.

## 13. Reavaliação dos riscos residuais

Após a implementação das medidas previstas, o risco deve ser reavaliado conforme a metodologia de gestão de riscos adotada.

A reavaliação deve considerar:

- ações efetivamente concluídas;
- controles implementados;
- evidências de funcionamento;
- limitações remanescentes;
- mudanças nas ameaças e vulnerabilidades;
- efeitos não previstos das medidas;
- impacto e probabilidade após o tratamento;
- critérios de aceitação aplicáveis;
- alterações relevantes no contexto em que o risco foi avaliado.

A avaliação deve distinguir entre a conclusão de uma ação e a eficácia do tratamento.

Uma atividade pode ter sido concluída sem produzir a redução de risco esperada. Nesse caso, podem ser necessárias medidas adicionais, revisão da abordagem ou escalonamento da decisão.

A comparação entre avaliações deve utilizar critérios consistentes e registrar as premissas relevantes. Se a metodologia, a escala ou as condições de avaliação tiverem sido alteradas, essas mudanças devem ser consideradas na interpretação dos resultados.

O risco residual reavaliado e a respectiva aceitação devem ser documentados conforme a governança definida. A decisão de aceitação deve refletir o risco efetivamente avaliado e não apenas a previsão registrada no plano inicial.

A aceitação formal deve ser atribuída ao proprietário do risco. A execução da ação ou a validação técnica do controle não substitui essa decisão.

## 14. Gestão de mudanças no plano

O plano deve ser atualizado quando houver alterações relevantes nas condições que fundamentaram as ações.

Exemplos de situações que podem exigir revisão:

- alteração no cenário de risco;
- mudança de prioridade;
- indisponibilidade de recursos;
- alteração de prazo;
- mudança na solução técnica;
- alteração de fornecedor;
- mudança no escopo do SGSI;
- identificação de novas obrigações;
- alterações relevantes no contexto interno ou externo;
- alterações climáticas ou fatores relacionados ao clima, quando pertinentes ao contexto e aos objetivos da organização;
- evidências de que a medida selecionada é insuficiente;
- ocorrência de incidente relacionado ao risco.

As mudanças devem manter histórico, justificativa, responsável e aprovação quando exigida.

A revisão do plano deve preservar a rastreabilidade entre a avaliação de riscos, as decisões de tratamento, a SoA e os registros de implementação.

Quando uma mudança significativa afetar o cenário de risco, a organização deve avaliar se é necessário atualizar a avaliação de riscos, rever os controles determinados ou modificar a estratégia de tratamento.

## 15. Evidências e registros

A organização deve determinar e manter as informações documentadas necessárias para demonstrar o planejamento, a execução e a avaliação do tratamento de riscos.

Conforme aplicável, os registros podem incluir:

- plano de tratamento aprovado;
- avaliações de riscos;
- justificativas das opções selecionadas;
- aprovações e autorizações;
- registros de execução;
- evidências de implementação dos controles;
- registros de testes e validações;
- histórico de mudanças;
- justificativas para atrasos ou desvios;
- avaliações dos riscos residuais;
- decisões de aceitação;
- relatórios de acompanhamento;
- registros de reavaliação quando ocorrerem mudanças significativas.

Os registros devem ser protegidos contra alteração indevida, perda e acesso não autorizado, conforme os requisitos e as necessidades da organização.

A documentação deve refletir a situação real. Não se deve marcar uma ação como concluída ou um controle como implementado sem evidências apropriadas.

As evidências devem ser suficientes para sustentar as afirmações registradas, considerando a natureza da ação e do controle. A existência de um documento ou de uma configuração, isoladamente, pode não demonstrar que um processo esteja sendo executado de forma consistente ou que o controle produza o resultado esperado.

## 16. Indicadores de acompanhamento

A organização pode estabelecer indicadores para monitorar a execução do plano e apoiar decisões de governança.

Exemplos de indicadores metodológicos:

- percentual de ações concluídas no prazo;
- quantidade de ações atrasadas por nível de prioridade;
- quantidade de riscos sem proprietário designado;
- quantidade de ações sem evidências de conclusão;
- quantidade de riscos residuais pendentes de aceitação;
- tempo médio de conclusão das ações;
- quantidade de ações reabertas após validação;
- quantidade de riscos acima dos critérios de aceitação;
- distribuição das ações por área responsável;
- percentual de ações concluídas cuja eficácia foi avaliada;
- quantidade de ações com dependências ou impedimentos críticos.

Os indicadores devem possuir definição, fórmula, fonte de dados, periodicidade, responsável e critérios de interpretação.

Os indicadores são instrumentos de acompanhamento e não substituem a análise qualitativa dos riscos. Um percentual elevado de ações concluídas, por exemplo, não demonstra por si só que os riscos estejam adequadamente tratados.

A seleção dos indicadores deve considerar as necessidades de informação da gestão e das demais funções responsáveis pelo monitoramento do SGSI.

## 17. Critérios de qualidade

Antes de aprovar ou revisar o plano, recomenda-se verificar:

- [ ] Os riscos relacionados estão identificados e avaliados.
- [ ] Os critérios de avaliação e aceitação estão definidos e são aplicáveis.
- [ ] As opções de tratamento possuem justificativa.
- [ ] Os controles necessários estão relacionados à SoA.
- [ ] As ações estão vinculadas aos riscos e às decisões de tratamento.
- [ ] Cada ação possui descrição objetiva.
- [ ] Os responsáveis estão definidos.
- [ ] Os prazos e recursos foram avaliados.
- [ ] Os critérios de conclusão e as evidências esperadas estão documentados.
- [ ] As dependências e os impedimentos relevantes estão registrados.
- [ ] O plano possui aprovação dos proprietários dos riscos.
- [ ] O acompanhamento e o controle de mudanças estão definidos.
- [ ] A reavaliação dos riscos residuais está prevista.
- [ ] A aceitação dos riscos residuais está atribuída aos respectivos proprietários.
- [ ] A aprovação do plano e a aceitação dos riscos residuais são registradas como decisões distintas.
- [ ] Os registros permitem rastrear as decisões e os resultados.
- [ ] A documentação distingue execução da ação e eficácia do tratamento.
- [ ] Os documentos relacionados permanecem coerentes e atualizados.

A conclusão desta verificação indica que o plano foi analisado segundo os critérios estabelecidos. Não comprova, isoladamente, a implementação eficaz do tratamento nem a conformidade integral do SGSI.

## 18. Limitações e adaptação

Este documento apresenta uma metodologia de referência para fins educacionais e de estruturação profissional.

Não constitui um plano de tratamento de riscos real, não define ações obrigatórias para todas as organizações e não comprova que qualquer risco tenha sido tratado.

Antes de utilizar o modelo em um SGSI real, a organização deve:

1. validar a metodologia e os critérios de risco;
2. utilizar resultados efetivos da avaliação de riscos;
3. selecionar opções de tratamento adequadas;
4. determinar os controles necessários;
5. elaborar ou atualizar a SoA;
6. definir ações, responsáveis, prazos e recursos;
7. obter a aprovação do plano pelos proprietários dos riscos;
8. implementar as ações e manter evidências da execução;
9. reavaliar os riscos após o tratamento;
10. registrar a aceitação formal dos riscos residuais pelos respectivos proprietários;
11. revisar o plano quando mudanças significativas afetarem os riscos ou as medidas adotadas.

Os exemplos deste documento são hipotéticos e devem ser adaptados ao contexto, aos objetivos e às obrigações da organização.

A adoção deste material não garante certificação ou conformidade automática com a ISO/IEC 27001. A conformidade depende da aplicação dos requisitos pertinentes e das evidências correspondentes no contexto do SGSI.

## 19. Documentos relacionados

Este documento deve ser articulado com:

- Documento Mestre de Implementação do SGSI;
- Análise de Contexto e Partes Interessadas;
- Definição do Escopo do SGSI;
- Política de Segurança da Informação;
- Papéis, Responsabilidades e Autoridades do SGSI;
- Metodologia de Gestão de Riscos de Segurança da Informação;
- Registro de Riscos;
- Declaração de Aplicabilidade (SoA);
- modelos de registros e evidências de implementação dos controles;
- Planejamento e Controle Operacional do SGSI;
- Monitoramento, Medição, Análise e Avaliação do SGSI;
- Metodologia de Auditoria Interna do SGSI;
- Análise Crítica pela Direção e Melhoria Contínua do SGSI.

Este documento deve utilizar a mesma terminologia da metodologia de gestão de riscos, distinguindo risco atual, risco residual esperado e risco residual reavaliado.

A SoA deve manter rastreabilidade com os controles necessários, suas justificativas de inclusão ou exclusão e as informações de implementação pertinentes.

A existência desses documentos no repositório representa sua inclusão na estrutura de referência, não a comprovação de aprovação ou implementação organizacional.

## 20. Referências

- ISO/IEC 27001:2022 — *Information security, cybersecurity and privacy protection — Information security management systems — Requirements*.
- ISO/IEC 27001:2022/Amd 1:2024 — *Climate action changes*.
- ISO/IEC 27005:2022 — *Information security, cybersecurity and privacy protection — Guidance on managing information security risks*.
- ISO/IEC 27002:2022 — *Information security, cybersecurity and privacy protection — Information security controls*.
- ISO 31000:2018 — *Risk management — Guidelines*, como referência complementar, quando adotada pela organização.

Consultar as publicações oficiais para confirmar os requisitos e as orientações aplicáveis.
