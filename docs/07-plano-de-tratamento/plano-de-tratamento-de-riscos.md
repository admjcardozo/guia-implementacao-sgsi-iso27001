# Plano de Tratamento de Riscos de Segurança da Informação

## 1. Objetivo

Este documento estabelece uma metodologia de referência para elaborar, aprovar, executar, monitorar e revisar o Plano de Tratamento de Riscos de Segurança da Informação no contexto de um Sistema de Gestão de Segurança da Informação (SGSI).

O plano tem como objetivos:

- documentar as opções de tratamento selecionadas para os riscos identificados;
- definir ações, responsáveis, prazos e recursos necessários;
- estabelecer critérios para acompanhar a execução das ações;
- manter rastreabilidade entre riscos, controles e decisões de tratamento;
- apoiar a avaliação dos riscos residuais;
- subsidiar a aprovação dos planos pelos proprietários dos riscos e pelas autoridades competentes;
- fornecer informações para o monitoramento e a melhoria contínua do SGSI.

Este documento é um guia metodológico. Não representa um plano de tratamento aprovado ou executado por uma organização real.

## 2. Referências normativas

A referência principal é a **ISO/IEC 27001:2022**, especialmente a cláusula 6.1.3, relativa ao tratamento de riscos de segurança da informação.

A cláusula 6.1.3 estabelece requisitos relacionados à seleção de opções de tratamento, à determinação dos controles necessários, à comparação com o Anexo A, à elaboração da Declaração de Aplicabilidade (SoA), à formulação do plano de tratamento e à obtenção da aprovação do plano e da aceitação dos riscos residuais pelos proprietários dos riscos.

A cláusula 8.3 também é relevante para a implementação do processo de tratamento de riscos conforme os planos estabelecidos.

A ISO/IEC 27002:2022 pode ser utilizada como referência complementar para orientação sobre controles de segurança da informação.

Este documento não reproduz integralmente o texto das normas. A consulta às publicações oficiais é necessária para confirmar os requisitos aplicáveis.

## 3. Conceitos fundamentais

Para aplicação desta metodologia, são utilizados os seguintes conceitos:

- **Risco identificado:** cenário de risco registrado e submetido ao processo de avaliação.
- **Opção de tratamento:** abordagem selecionada para modificar, evitar, compartilhar ou aceitar um risco, conforme aplicável.
- **Ação de tratamento:** atividade definida para implementar a opção de tratamento escolhida.
- **Controle:** medida destinada a modificar ou manter o risco, conforme o contexto.
- **Responsável pela ação:** pessoa ou função encarregada de executar ou coordenar uma atividade do plano.
- **Proprietário do risco:** pessoa ou função designada para responder pela gestão do risco dentro dos limites de autoridade estabelecidos.
- **Risco residual:** risco remanescente após a implementação das medidas consideradas no tratamento.
- **Aceitação do risco residual:** decisão formal de aceitar o risco remanescente, conforme os critérios e as autoridades definidos pela organização.
- **Evidência de implementação:** informação que sustenta a afirmação de que uma ação ou controle foi implementado.
- **Eficácia do tratamento:** grau em que as medidas adotadas produzem os resultados esperados na modificação do risco.

A organização deve definir os termos e as regras de aplicação de maneira consistente com sua metodologia de gestão de riscos.

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

O plano deve manter referências aos riscos, aos controles selecionados, à SoA e às evidências de execução.

### 4.5. Aprovação formal

As opções de tratamento, o plano e a aceitação dos riscos residuais devem ser submetidos às aprovações exigidas pela ISO/IEC 27001:2022 e pela governança definida pela organização.

### 4.6. Monitoramento

A execução das ações deve ser acompanhada para identificar atrasos, impedimentos, alterações de escopo e riscos que permaneçam acima dos critérios de aceitação.

## 5. Relação entre avaliação de riscos, SoA e plano de tratamento

O Plano de Tratamento de Riscos integra o processo de gestão de riscos do SGSI.

A sequência metodológica de referência é:

1. identificar e avaliar os riscos;
2. comparar os resultados com os critérios de risco estabelecidos;
3. selecionar as opções de tratamento;
4. determinar os controles necessários;
5. comparar os controles necessários com o Anexo A da ISO/IEC 27001:2022;
6. documentar a Declaração de Aplicabilidade;
7. elaborar o plano de tratamento;
8. obter as aprovações necessárias;
9. implementar e acompanhar as ações;
10. reavaliar os riscos e tratar a aceitação dos riscos residuais.

A sequência deve preservar a rastreabilidade entre os resultados da avaliação, as decisões tomadas e as medidas selecionadas.

O plano não substitui o registro de riscos nem a SoA. Cada documento possui uma finalidade específica, e suas informações devem permanecer coerentes.

## 6. Seleção das opções de tratamento

A organização deve selecionar opções de tratamento adequadas aos riscos identificados, considerando os critérios aprovados, os objetivos do SGSI e as obrigações aplicáveis.

Entre as opções que podem ser consideradas estão:

### 6.1. Modificar o risco

Consiste em adotar controles ou outras medidas para alterar a probabilidade de ocorrência, as consequências ou outros fatores relevantes do risco.

Exemplos metodológicos:

- implementar autenticação multifator;
- revisar privilégios de acesso;
- estabelecer cópias de segurança e testar sua recuperação;
- melhorar o monitoramento de eventos de segurança;
- corrigir vulnerabilidades identificadas;
- estabelecer procedimentos de resposta a incidentes.

A escolha de uma medida deve ser fundamentada no cenário avaliado. Os exemplos não constituem recomendações universais para todos os riscos.

### 6.2. Evitar o risco

Consiste em interromper, não iniciar ou modificar uma atividade ou condição que origina o risco, quando essa decisão for viável e apropriada.

A decisão deve considerar os impactos operacionais, estratégicos, contratuais e legais associados.

### 6.3. Compartilhar ou transferir parte do risco

Consiste em estabelecer mecanismos que distribuam ou transfiram determinadas responsabilidades ou consequências, como contratos, seguros ou serviços especializados, quando apropriado.

O compartilhamento ou a transferência não elimina automaticamente as responsabilidades da organização, suas obrigações legais ou todos os efeitos do risco.

### 6.4. Aceitar o risco

Consiste em decidir formalmente manter o risco dentro dos critérios e limites de autoridade estabelecidos.

A aceitação deve possuir justificativa documentada e aprovação por autoridade apropriada.

A aceitação não deve ser utilizada como substituto para o cumprimento de requisitos legais, regulatórios ou contratuais aplicáveis.

## 7. Estrutura recomendada do plano

A organização pode utilizar uma planilha, sistema de gestão de riscos ou ferramenta equivalente para registrar as ações.

A estrutura de referência deve contemplar, conforme aplicável:

| Campo | Finalidade |
|---|---|
| ID da ação | Identificador único da ação de tratamento. |
| ID do risco | Referência ao risco que motivou a ação. |
| Descrição do risco | Síntese do cenário de risco associado. |
| Opção de tratamento | Registrar a opção selecionada. |
| Controle relacionado | Referenciar o controle ou conjunto de controles envolvidos. |
| Descrição da ação | Especificar a atividade que será executada. |
| Resultado esperado | Definir o resultado pretendido. |
| Responsável | Identificar a pessoa ou função responsável pela execução. |
| Proprietário do risco | Identificar quem responde pela gestão do risco. |
| Prioridade | Registrar a prioridade conforme os critérios aprovados. |
| Prazo | Indicar a data-alvo aprovada. |
| Recursos necessários | Registrar recursos humanos, financeiros, técnicos ou externos. |
| Dependências | Identificar atividades, aprovações ou entregas necessárias. |
| Critério de conclusão | Definir como será verificado que a ação foi concluída. |
| Evidência esperada | Indicar os registros que sustentarão a conclusão. |
| Situação | Registrar o estado atual da ação. |
| Risco residual | Registrar o resultado da reavaliação, quando aplicável. |
| Aprovação | Registrar as aprovações necessárias. |
| Histórico | Preservar alterações, decisões e justificativas relevantes. |

Os campos adicionais são recomendações metodológicas. A organização deve manter, no mínimo, as informações necessárias para cumprir os requisitos normativos e demonstrar a execução controlada do tratamento.

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
- riscos introduzidos pela própria implementação.

Uma classificação como crítica, alta, média ou baixa pode ser utilizada como mecanismo gerencial, desde que seus critérios estejam documentados.

A prioridade não deve ser determinada exclusivamente pela pontuação de uma matriz de risco. Obrigações aplicáveis e outros fatores relevantes podem exigir ação ou escalonamento independentemente do resultado numérico.

Quando uma ação prioritária não puder ser executada no prazo inicialmente previsto, a justificativa, os impactos e a decisão sobre medidas compensatórias devem ser documentados e submetidos à autoridade apropriada.

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
- evidência esperada.

O critério de conclusão deve permitir verificar se a entrega foi realizada.

Quando a ação envolver um controle de segurança, a conclusão da atividade não significa automaticamente que o controle esteja eficaz ou que o risco tenha sido reduzido ao nível pretendido. Essa conclusão depende da avaliação e das evidências apropriadas.

## 10. Exemplo hipotético de plano de tratamento

A tabela a seguir apresenta um exemplo exclusivamente didático.

| Campo | Exemplo |
|---|---|
| ID da ação | AT-ACESSO-001 |
| ID do risco | R-ACESSO-001 |
| Descrição do risco | Manutenção de privilégios incompatíveis com a função atual de um usuário. |
| Opção de tratamento | Modificar o risco. |
| Controle relacionado | Gestão e revisão dos direitos de acesso, conforme os controles determinados pela organização. |
| Descrição da ação | Definir e executar um processo periódico de revisão de privilégios, incluindo registro das decisões e correção das incompatibilidades identificadas. |
| Resultado esperado | Reduzir a possibilidade de manutenção de acessos incompatíveis com as responsabilidades atribuídas. |
| Responsável | A definir pela organização hipotética. |
| Prioridade | A determinar segundo os critérios de risco aprovados. |
| Prazo | A definir. |
| Recursos necessários | A estimar após avaliação do ambiente e do escopo. |
| Critério de conclusão | Processo definido, revisão executada e decisões registradas conforme os critérios aprovados. |
| Evidência esperada | Procedimento aprovado, registros da revisão, decisões e comprovação das correções realizadas. |
| Situação | Não iniciado no exemplo. |
| Risco residual | Não avaliado. |
| Aprovação | Não realizada. |

Este exemplo não representa uma ação executada, um controle implementado ou uma constatação sobre uma organização real.

Os responsáveis, prazos, prioridades, recursos e critérios definitivos devem ser estabelecidos a partir da avaliação e da governança da organização que utilizar o modelo.

## 11. Aprovação do plano e aceitação de riscos residuais

A organização deve estabelecer um processo formal para aprovar o plano de tratamento e a aceitação dos riscos residuais pelos proprietários dos riscos, conforme os requisitos aplicáveis.

O processo deve distinguir:

- aprovação da opção de tratamento;
- aprovação do plano e dos recursos;
- autorização para execução;
- validação da conclusão das ações;
- avaliação do risco residual;
- aceitação formal do risco residual.

Essas decisões podem ocorrer em momentos diferentes e devem ser registradas de forma que sua sequência e seus responsáveis sejam compreensíveis.

A aprovação do plano não deve ser interpretada como aceitação automática de todos os riscos residuais futuros.

Quando o risco residual permanecer acima dos critérios de aceitação, a organização deve avaliar novas opções de tratamento ou escalar a decisão conforme sua governança.

A aceitação deve respeitar as obrigações aplicáveis e os limites de autoridade definidos. Não se deve presumir que qualquer pessoa possa aceitar qualquer nível de risco.

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
- riscos que permanecem sem tratamento suficiente.

Quando houver atraso, mudança ou impedimento relevante, a situação deve ser registrada e submetida à análise apropriada.

A alteração de prazos ou escopo deve possuir justificativa e aprovação conforme as regras estabelecidas.

O acompanhamento pode ser realizado por reuniões de governança, indicadores, relatórios, sistemas de gestão ou outros mecanismos adequados.

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
- critérios de aceitação aplicáveis.

A avaliação deve distinguir entre a conclusão de uma ação e a eficácia do tratamento.

Uma atividade pode ter sido concluída sem produzir a redução de risco esperada. Nesse caso, podem ser necessárias medidas adicionais, revisão dos critérios ou escalonamento da decisão.

O risco residual e a respectiva aceitação devem ser documentados conforme a governança definida.

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
- evidências de que a medida selecionada é insuficiente;
- ocorrência de incidente relacionado ao risco.

As mudanças devem manter histórico, justificativa, responsável e aprovação quando exigida.

A revisão do plano deve preservar a rastreabilidade entre a avaliação de riscos, as decisões de tratamento, a SoA e os registros de implementação.

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
- relatórios de acompanhamento.

Os registros devem ser protegidos contra alteração indevida, perda e acesso não autorizado, conforme os requisitos e as necessidades da organização.

A documentação deve refletir a situação real. Não se deve marcar uma ação como concluída ou um controle como implementado sem evidências apropriadas.

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
- distribuição das ações por área responsável.

Os indicadores devem possuir definição, fórmula, fonte de dados, periodicidade, responsável e critérios de interpretação.

Os indicadores são instrumentos de acompanhamento e não substituem a análise qualitativa dos riscos. Um percentual elevado de ações concluídas, por exemplo, não demonstra por si só que os riscos estejam adequadamente tratados.

## 17. Critérios de qualidade

Antes de aprovar ou revisar o plano, recomenda-se verificar:

- [ ] Os riscos relacionados estão identificados e avaliados.
- [ ] As opções de tratamento possuem justificativa.
- [ ] Os controles necessários estão relacionados à SoA.
- [ ] Cada ação possui descrição objetiva.
- [ ] Os responsáveis estão definidos.
- [ ] Os prazos e recursos foram avaliados.
- [ ] Os critérios de conclusão e as evidências esperadas estão documentados.
- [ ] As dependências e os impedimentos relevantes estão registrados.
- [ ] O plano possui as aprovações necessárias.
- [ ] O acompanhamento e o controle de mudanças estão definidos.
- [ ] A reavaliação dos riscos residuais está prevista.
- [ ] A aceitação dos riscos residuais está sujeita à autoridade apropriada.
- [ ] Os registros permitem rastrear as decisões e os resultados.

A conclusão desta verificação indica que o plano foi analisado segundo os critérios estabelecidos. Não comprova, isoladamente, a implementação eficaz do tratamento nem a conformidade integral do SGSI.

## 18. Limitações e adaptação

Este documento apresenta uma metodologia de referência para fins educacionais e de estruturação profissional.

Não constitui um plano de tratamento de riscos real, não define ações obrigatórias para todas as organizações e não comprova que qualquer risco tenha sido tratado.

Antes de utilizar o modelo em um SGSI real, a organização deve:

1. validar a metodologia e os critérios de risco;
2. utilizar resultados efetivos da avaliação de riscos;
3. selecionar opções de tratamento adequadas;
4. determinar os controles necessários;
5. elaborar e aprovar a SoA;
6. definir ações, responsáveis, prazos e recursos;
7. aprovar o plano e implementar as ações;
8. manter evidências da execução;
9. reavaliar os riscos residuais;
10. registrar as decisões de aceitação e as necessidades de tratamento adicional.

Os exemplos deste documento são hipotéticos e devem ser adaptados ao contexto e às obrigações da organização.

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
- procedimentos e registros de implementação dos controles;
- processos de monitoramento, auditoria e melhoria contínua.

A existência desses documentos no repositório representa sua inclusão na estrutura de referência, não a comprovação de aprovação ou implementação organizacional.

## 20. Referências

- ISO/IEC 27001:2022 — Information security, cybersecurity and privacy protection — Information security management systems — Requirements.
- ISO/IEC 27002:2022 — Information security, cybersecurity and privacy protection — Information security controls.
- ISO 31000 — Risk management — Guidelines, como referência complementar, quando adotada pela organização.

Consultar as publicações oficiais para confirmar os requisitos e as orientações aplicáveis.
