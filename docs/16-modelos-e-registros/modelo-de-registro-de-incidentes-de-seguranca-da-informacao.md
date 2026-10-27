# Modelo de Registro de Incidentes de Segurança da Informação

## 1. Objetivo

Este documento apresenta um modelo para registrar, acompanhar, tratar e encerrar incidentes de segurança da informação no contexto de um Sistema de Gestão de Segurança da Informação (SGSI).

O registro permite organizar as informações sobre a ocorrência, seus impactos, as ações de contenção e recuperação, as evidências disponíveis, as responsabilidades e as oportunidades de melhoria.

O modelo deve ser adaptado ao contexto, ao escopo, aos riscos e aos procedimentos da organização.

**Importante:** este arquivo é um modelo de referência. Seu conteúdo não representa um incidente real nem comprova que uma organização tenha implementado um processo de gestão de incidentes.

## 2. Referências relacionadas

Este modelo pode apoiar a organização de informações relacionadas a:

- ISO/IEC 27001:2022, especialmente os requisitos relativos à operação do SGSI, ao monitoramento, à avaliação de desempenho e à melhoria.
- ISO/IEC 27001:2022, Anexo A, controles relacionados à preparação para incidentes, à avaliação de eventos de segurança e à resposta a incidentes.
- Políticas e procedimentos internos de segurança da informação.
- Processo de gestão de riscos de segurança da informação.
- Plano de continuidade de negócios e procedimentos de recuperação, quando aplicáveis.
- Obrigações contratuais, legais e regulatórias pertinentes ao incidente.

A seleção e a aplicação dos requisitos e controles devem considerar o contexto da organização, os riscos identificados e a Declaração de Aplicabilidade (SoA). Este modelo, isoladamente, não demonstra conformidade com a norma.

## 3. Conceitos utilizados

**Evento de segurança da informação:** ocorrência observada que pode indicar uma falha, uma violação ou uma condição relevante para a segurança da informação.

**Incidente de segurança da informação:** evento ou conjunto de eventos que compromete ou ameaça comprometer a segurança da informação e que exige resposta conforme os critérios definidos pela organização.

**Contenção:** ação destinada a limitar a propagação ou os efeitos do incidente.

**Erradicação:** ação destinada a eliminar a causa técnica ou a condição que permitiu a ocorrência, quando aplicável.

**Recuperação:** processo de restabelecimento seguro dos serviços, sistemas, informações ou atividades afetadas.

**Causa raiz:** causa fundamental identificada por meio de análise apropriada, quando possível. A causa não deve ser presumida sem evidências suficientes.

**Lição aprendida:** conhecimento obtido durante ou após o tratamento do incidente que pode contribuir para prevenir recorrências ou melhorar a capacidade de resposta.

## 4. Identificação do registro

| Campo | Preenchimento |
|---|---|
| Identificador do incidente | [INC-AAAA-NNN] |
| Título do incidente | [Título objetivo] |
| Data e hora da detecção | [AAAA-MM-DD HH:MM e fuso horário] |
| Data e hora estimada do início | [Data, hora e indicação de incerteza, se aplicável] |
| Data e hora do registro | [AAAA-MM-DD HH:MM e fuso horário] |
| Pessoa ou área responsável pelo registro | [Responsável] |
| Área responsável pela resposta | [Área ou equipe] |
| Situação atual | [Em triagem / Em tratamento / Em recuperação / Monitoramento / Encerrado] |
| Classificação de severidade | [Conforme critérios internos] |
| Confidencialidade do registro | [Classificação aplicável] |

A organização deve definir um padrão de identificação que permita rastrear o incidente sem expor informações sensíveis desnecessariamente.

## 5. Origem da detecção

Indicar como o evento foi identificado.

- [ ] Ferramenta de monitoramento ou alerta de segurança
- [ ] Central de serviços ou suporte técnico
- [ ] Comunicação de colaborador
- [ ] Comunicação de cliente, fornecedor ou parceiro
- [ ] Auditoria ou avaliação de controles
- [ ] Análise de logs ou investigação técnica
- [ ] Comunicação de autoridade ou entidade externa
- [ ] Outro: [Descrever]

**Descrição da detecção:**

[Registrar o que foi observado, por quem, quando e por qual meio. Diferenciar os fatos confirmados das suspeitas iniciais.]

## 6. Descrição do incidente

**Resumo executivo:**

[Descrever o incidente de forma objetiva, indicando o que ocorreu ou pode ter ocorrido, quais ativos ou serviços estão envolvidos e qual é a situação conhecida.]

**Descrição detalhada:**

[Registrar os fatos conhecidos em ordem cronológica, incluindo alertas, comunicações, ações realizadas e resultados observados.]

**Informações ainda não confirmadas:**

[Relacionar hipóteses, lacunas de informação e pontos que dependem de investigação.]

**Origem ou vetor suspeito:**

[Registrar apenas quando houver informação suficiente. Identificar expressamente as hipóteses ainda não confirmadas.]

## 7. Ativos, serviços e informações afetados

| Ativo, serviço ou informação | Responsável pelo ativo | Impacto observado ou suspeito | Situação atual |
|---|---|---|---|
| [Identificação] | [Responsável] | [Descrição] | [Situação] |
| [Identificação] | [Responsável] | [Descrição] | [Situação] |

Considerar, quando aplicável:

- Sistemas, aplicações e infraestrutura.
- Contas, identidades e credenciais.
- Informações corporativas ou dados pessoais.
- Serviços prestados a clientes ou áreas internas.
- Fornecedores, parceiros e integrações.
- Ambientes físicos, equipamentos e recursos de comunicação.

Não incluir senhas, tokens, chaves privadas ou outros segredos no registro. Referenciar repositórios ou sistemas de evidências com controles de acesso adequados.

## 8. Classificação e avaliação de impacto

A classificação deve seguir os critérios aprovados pela organização. Os campos abaixo são sugestões e precisam ser ajustados à metodologia interna.

| Dimensão | Avaliação | Justificativa ou evidência |
|---|---|---|
| Confidencialidade | [Sem impacto / Baixo / Médio / Alto / A confirmar] | [Descrição] |
| Integridade | [Sem impacto / Baixo / Médio / Alto / A confirmar] | [Descrição] |
| Disponibilidade | [Sem impacto / Baixo / Médio / Alto / A confirmar] | [Descrição] |
| Impacto operacional | [Classificação interna] | [Descrição] |
| Impacto financeiro | [Classificação interna / A confirmar] | [Descrição] |
| Impacto legal ou regulatório | [Classificação interna / A confirmar] | [Descrição] |
| Impacto reputacional | [Classificação interna / A confirmar] | [Descrição] |
| Abrangência | [Local / Organizacional / Externa / A confirmar] | [Descrição] |

**Severidade final:** [Classificação conforme critérios internos]

**Justificativa da classificação:** [Registrar os critérios aplicados e as evidências que sustentam a decisão.]

**Necessidade de escalonamento:** [Sim / Não / Em avaliação]

**Responsável pela decisão:** [Nome ou função]

**Data e hora da decisão:** [Data, hora e fuso horário]

## 9. Linha do tempo do incidente

| Data e hora | Evento ou decisão | Responsável | Evidência ou referência |
|---|---|---|---|
| [Data e hora] | [Descrição] | [Responsável] | [Identificador da evidência] |
| [Data e hora] | [Descrição] | [Responsável] | [Identificador da evidência] |

A linha do tempo deve diferenciar o horário em que um evento ocorreu do horário em que foi identificado ou registrado, quando essas informações forem distintas.

## 10. Ações de resposta

### 10.1 Contenção

| Ação | Responsável | Início | Conclusão | Resultado ou evidência |
|---|---|---|---|---|
| [Descrição] | [Responsável] | [Data/hora] | [Data/hora ou pendente] | [Referência] |

### 10.2 Erradicação

| Ação | Responsável | Início | Conclusão | Resultado ou evidência |
|---|---|---|---|---|
| [Descrição] | [Responsável] | [Data/hora] | [Data/hora ou pendente] | [Referência] |

### 10.3 Recuperação

| Ação | Responsável | Início | Conclusão | Resultado ou evidência |
|---|---|---|---|---|
| [Descrição] | [Responsável] | [Data/hora] | [Data/hora ou pendente] | [Referência] |

Para cada ação, registrar a decisão tomada, o responsável, o prazo, o resultado e as evidências correspondentes. Quando uma etapa não for aplicável, justificar a decisão.

## 11. Comunicação e escalonamento

| Destinatário ou parte interessada | Motivo da comunicação | Responsável | Data e hora | Situação |
|---|---|---|---|---|
| [Área, função ou entidade] | [Motivo] | [Responsável] | [Data/hora] | [Situação] |

Registrar, conforme aplicável:

- Comunicação à gestão e às áreas responsáveis.
- Acionamento de equipes técnicas, jurídicas, de privacidade ou de continuidade.
- Comunicação a clientes, fornecedores ou parceiros.
- Avaliação da necessidade de notificação a autoridades ou órgãos competentes.
- Comunicação a pessoas afetadas, quando aplicável.
- Motivo e aprovação para decisões de comunicar ou não comunicar.

Prazos, destinatários e obrigações de notificação devem ser avaliados conforme a legislação, a regulamentação, os contratos e as circunstâncias efetivas do caso. Este modelo não substitui a avaliação jurídica ou regulatória.

## 12. Tratamento de dados pessoais

**Há indícios de envolvimento de dados pessoais?** [Sim / Não / A confirmar]

**Categorias de dados potencialmente envolvidas:** [Descrição sem reproduzir dados pessoais desnecessários]

**Avaliação realizada por:** [Responsável ou área]

**Decisão sobre comunicação ou notificação:** [Decisão, justificativa, aprovador e data]

**Referência do registro relacionado:** [Identificador ou localização controlada]

As informações pessoais devem ser tratadas de acordo com as regras de privacidade, proteção de dados, necessidade de acesso e retenção aplicáveis. Evitar inserir dados pessoais identificáveis no registro quando uma referência controlada for suficiente.

## 13. Evidências e preservação

| Identificador | Descrição da evidência | Origem | Data e hora da coleta | Responsável pela coleta | Localização controlada |
|---|---|---|---|---|---|
| [EVD-001] | [Descrição] | [Origem] | [Data/hora] | [Responsável] | [Referência] |

Registrar, quando aplicável:

- Logs, alertas e registros de sistemas.
- Capturas de tela e relatórios técnicos.
- Arquivos ou artefatos relevantes.
- Comunicações relacionadas ao incidente.
- Registros de decisões e aprovações.
- Informações sobre coleta, transferência, armazenamento e acesso às evidências.

Preservar a integridade e a rastreabilidade das evidências conforme os procedimentos aplicáveis. Quando houver necessidade de investigação formal ou preservação para fins legais, seguir as orientações das áreas competentes.

## 14. Análise de causa e recorrência

**Causa raiz identificada:** [Descrição ou “não determinada”]

**Método de análise utilizado:** [Método]

**Evidências que sustentam a conclusão:** [Referências]

**Fatores contribuintes:** [Descrição]

**Existem ocorrências semelhantes anteriores?** [Sim / Não / A verificar]

**Registros relacionados:** [Identificadores]

**Risco de recorrência:** [Avaliação conforme critérios internos]

Não atribuir uma causa definitiva sem evidências suficientes. Se a investigação não permitir determinar a causa, registrar essa limitação e indicar se haverá análise complementar.

## 15. Relação com a gestão de riscos

| Campo | Preenchimento |
|---|---|
| Risco relacionado | [Identificador do risco, se existente] |
| O risco estava registrado previamente? | [Sim / Não / A verificar] |
| Avaliação de risco precisa ser revisada? | [Sim / Não / Em avaliação] |
| Controles relacionados | [Identificadores ou referências] |
| Necessidade de atualizar a SoA | [Avaliar conforme aplicabilidade e mudanças] |
| Responsável pela revisão | [Responsável] |
| Prazo para revisão | [Data] |

A ocorrência de um incidente pode indicar a necessidade de revisar riscos, controles, procedimentos, critérios de aceitação e decisões anteriores. Essa revisão deve ser baseada nas evidências e na metodologia de gestão de riscos adotada pela organização.

## 16. Ações de melhoria decorrentes do incidente

| Ação | Tipo | Responsável | Prazo | Critério de conclusão | Evidência |
|---|---|---|---|---|---|
| [Descrição] | [Correção / Ação corretiva / Melhoria / Tratamento de risco] | [Responsável] | [Data] | [Critério verificável] | [Referência] |

As ações podem incluir mudanças técnicas, ajustes de processos, revisão de políticas, capacitação, melhorias de monitoramento ou atualização de planos de resposta.

Quando uma ação estiver relacionada a uma não conformidade, utilizar também o registro específico de não conformidades e ações corretivas, evitando duplicidade de informações e mantendo a rastreabilidade entre os registros.

## 17. Lições aprendidas

**O que funcionou adequadamente?**

[Registrar práticas e controles que contribuíram para a detecção, resposta ou recuperação.]

**O que precisa ser melhorado?**

[Registrar lacunas, atrasos, falhas de comunicação ou limitações observadas.]

**Quais melhorias foram priorizadas?**

[Relacionar ações aprovadas, responsáveis e prazos.]

**É necessária atualização de treinamento ou conscientização?**

[Sim / Não / A avaliar, com justificativa.]

## 18. Encerramento do incidente

O encerramento deve ocorrer conforme os critérios aprovados pela organização. A conclusão administrativa do registro não deve ser confundida com a comprovação de que todos os riscos foram eliminados.

| Critério | Situação | Evidência ou justificativa |
|---|---|---|
| Contenção concluída ou formalmente dispensada | [Sim / Não / Não aplicável] | [Referência] |
| Recuperação concluída ou plano aprovado | [Sim / Não / Não aplicável] | [Referência] |
| Impactos avaliados | [Sim / Não / Parcial] | [Referência] |
| Comunicações avaliadas e realizadas, quando necessárias | [Sim / Não / Não aplicável] | [Referência] |
| Evidências preservadas conforme aplicável | [Sim / Não / Não aplicável] | [Referência] |
| Ações pendentes registradas e atribuídas | [Sim / Não] | [Referência] |
| Revisão de riscos avaliada | [Sim / Não] | [Referência] |
| Lições aprendidas registradas | [Sim / Não] | [Referência] |

**Decisão de encerramento:** [Encerrado / Mantido em acompanhamento]

**Justificativa:** [Descrição]

**Responsável pela aprovação:** [Nome ou função]

**Data do encerramento:** [Data e hora]

**Acompanhamento posterior necessário:** [Sim / Não; descrever responsável, prazo e condição de acompanhamento.]

## 19. Indicadores possíveis

A organização pode utilizar informações consolidadas dos registros para acompanhar, por exemplo:

- Quantidade de incidentes por período e categoria.
- Distribuição por severidade.
- Tempo entre detecção e registro.
- Tempo até contenção e recuperação.
- Percentual de incidentes com causa identificada.
- Percentual de ações concluídas dentro do prazo.
- Ocorrência de incidentes recorrentes.
- Percentual de registros com evidências adequadas.
- Quantidade de ações de melhoria originadas por incidentes.

Os indicadores devem ter definições, fórmulas, fontes de dados, responsáveis e periodicidade documentados. Comparações devem considerar diferenças de escopo, classificação e qualidade dos dados.

## 20. Controle de acesso, retenção e proteção do registro

O registro deve ser protegido de acordo com a classificação da informação e com a sensibilidade do incidente.

A organização deve definir:

- Quem pode consultar, criar, alterar e aprovar registros.
- Como as alterações serão rastreadas.
- Onde as evidências serão armazenadas.
- Qual é o prazo de retenção aplicável.
- Como serão tratadas solicitações de acesso, preservação ou descarte.
- Como evitar a exposição de informações sensíveis durante a comunicação e o encerramento.

Os prazos de retenção devem ser definidos conforme necessidades operacionais, legais, regulatórias e contratuais.

## 21. Checklist de qualidade do registro

- [ ] O incidente possui identificador único.
- [ ] Os fatos confirmados estão separados das hipóteses.
- [ ] A severidade está fundamentada nos critérios internos.
- [ ] Os ativos e serviços afetados foram identificados.
- [ ] As ações de resposta possuem responsáveis e evidências.
- [ ] As decisões de comunicação foram avaliadas e registradas.
- [ ] As evidências possuem referências rastreáveis.
- [ ] A necessidade de revisar riscos e controles foi avaliada.
- [ ] As ações pendentes possuem responsáveis e prazos.
- [ ] A decisão de encerramento foi justificada e aprovada.
- [ ] O acesso e a retenção do registro foram considerados.

## 22. Limitações e orientações de uso

Este modelo deve ser adaptado aos procedimentos de resposta a incidentes, à estrutura de governança, aos critérios de classificação e às obrigações aplicáveis à organização.

Ele não substitui um plano de resposta a incidentes, procedimentos técnicos de investigação, planos de continuidade, análise jurídica ou avaliação de obrigações regulatórias.

O preenchimento de um registro não comprova, isoladamente, a conformidade com a ISO/IEC 27001:2022. A conformidade depende da implementação efetiva, da operação dos processos e da existência de evidências apropriadas.

## 23. Histórico de revisão

| Versão | Data | Descrição da alteração | Responsável |
|---|---|---|---|
| 1.0 | [AAAA-MM-DD] | Criação do modelo para adaptação | [Responsável] |
