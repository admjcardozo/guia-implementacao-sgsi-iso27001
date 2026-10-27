# Modelo de Registro de Gestão de Mudanças de TI e Segurança da Informação

## 1. Objetivo

Este documento apresenta um modelo para registrar, avaliar, aprovar, implementar e validar mudanças em sistemas, aplicações, infraestrutura, serviços, configurações e controles de segurança da informação.

O registro busca assegurar que as mudanças sejam planejadas, avaliadas quanto aos riscos, autorizadas pelas pessoas competentes, executadas de forma controlada e verificadas após a implementação.

O modelo pode apoiar a gestão operacional e a manutenção do Sistema de Gestão de Segurança da Informação (SGSI), promovendo rastreabilidade das decisões e tratamento adequado dos impactos associados às mudanças.

**Importante:** este documento é um modelo de referência. Seu preenchimento não comprova que uma mudança tenha sido aprovada, executada ou validada em uma organização real.

## 2. Referências relacionadas

Considerar, conforme aplicabilidade:

- ISO/IEC 27001:2022, requisitos relacionados ao planejamento e controle operacional do SGSI.
- ISO/IEC 27001:2022, requisitos relativos à avaliação de riscos e ao tratamento de mudanças que possam afetar o SGSI.
- ISO/IEC 27001:2022, Anexo A, controles relacionados à gestão de mudanças, à configuração e à segurança dos serviços e sistemas.
- Política de Segurança da Informação.
- Procedimento de gestão de mudanças.
- Metodologia de gestão de riscos.
- Inventário de ativos e serviços de informação.
- Plano de continuidade de negócios.
- Procedimentos de resposta a incidentes.
- Procedimentos de desenvolvimento, testes e implantação de sistemas.

A seleção e a aplicação dos controles devem considerar o contexto organizacional, os riscos, o escopo do SGSI e a Declaração de Aplicabilidade (SoA).

## 3. Identificação da mudança

| Campo | Preenchimento |
|---|---|
| Identificador da mudança | [MUD-AAAA-NNN] |
| Título | [Descrição resumida] |
| Tipo de mudança | [Planejada / Emergencial / Padrão, se definida] |
| Data da solicitação | [AAAA-MM-DD] |
| Solicitante | [Pessoa ou função] |
| Área solicitante | [Área] |
| Responsável técnico | [Pessoa ou equipe] |
| Serviço ou ativo afetado | [Identificação] |
| Ambiente | [Desenvolvimento / Homologação / Produção / Outro] |
| Prioridade | [Conforme critérios internos] |
| Situação | [Solicitada / Em avaliação / Aprovada / Agendada / Em execução / Concluída / Rejeitada / Cancelada] |
| Classificação da informação | [Quando aplicável] |

O identificador deve permitir relacionar a mudança aos registros de risco, incidentes, testes, aprovações e evidências correspondentes.

## 4. Descrição e justificativa

**Descrição da mudança:**

[Descrever o que será alterado, incluindo sistemas, configurações, componentes, processos ou controles afetados.]

**Justificativa de negócio ou técnica:**

[Explicar a necessidade, o problema a resolver ou o benefício esperado.]

**Objetivo esperado:**

[Definir o resultado pretendido.]

**Escopo incluído:**

[Relacionar os componentes e atividades abrangidos.]

**Escopo excluído:**

[Relacionar o que não faz parte da mudança e justificar, quando necessário.]

**Referências relacionadas:**

[Identificadores de incidentes, problemas, projetos, requisitos ou solicitações vinculadas.]

## 5. Classificação e criticidade

A classificação deve seguir os critérios aprovados pela organização.

| Dimensão | Avaliação | Justificativa |
|---|---|---|
| Impacto no negócio | [Classificação interna] | [Descrição] |
| Impacto na disponibilidade | [Classificação interna] | [Descrição] |
| Impacto na confidencialidade | [Classificação interna] | [Descrição] |
| Impacto na integridade | [Classificação interna] | [Descrição] |
| Complexidade técnica | [Classificação interna] | [Descrição] |
| Abrangência | [Local / Múltiplos serviços / Organizacional / Outra] | [Descrição] |
| Necessidade de janela de manutenção | [Sim / Não] | [Justificativa] |
| Necessidade de comunicação prévia | [Sim / Não] | [Justificativa] |

**Classificação final:** [Conforme critérios internos]

**Responsável pela classificação:** [Função ou nome]

**Data da avaliação:** [AAAA-MM-DD]

A classificação deve considerar os efeitos diretos e indiretos da mudança, inclusive as dependências tecnológicas e operacionais.

## 6. Avaliação de riscos

A mudança deve ser avaliada quanto aos riscos que pode introduzir, modificar ou reduzir.

| Risco identificado | Probabilidade ou classificação | Impacto potencial | Medida de tratamento | Responsável |
|---|---|---|---|---|
| [Descrição] | [Conforme metodologia interna] | [Descrição] | [Ação] | [Responsável] |
| [Descrição] | [Classificação] | [Descrição] | [Ação] | [Responsável] |

Avaliar, conforme aplicabilidade:

- Interrupção ou degradação de serviços.
- Exposição ou alteração indevida de informações.
- Perda ou corrupção de dados.
- Introdução de vulnerabilidades.
- Falha de compatibilidade ou integração.
- Indisponibilidade de recursos de recuperação.
- Alteração de permissões ou privilégios.
- Impactos em fornecedores e serviços terceirizados.
- Efeitos sobre requisitos legais, regulatórios ou contratuais.
- Impactos sobre outros controles do SGSI.

**Conclusão da avaliação:** [Aceita / Requer medidas adicionais / Não recomendada / Pendente]

**Responsável pela avaliação:** [Função ou nome]

**Referência do registro de risco:** [Identificador, quando aplicável]

Quando a mudança alterar significativamente o contexto ou os riscos do SGSI, avaliar a necessidade de atualizar os registros de risco e os documentos relacionados.

## 7. Impactos e dependências

| Serviço, ativo ou área | Impacto previsto | Dependência | Medida de mitigação | Responsável |
|---|---|---|---|---|
| [Identificação] | [Descrição] | [Dependência] | [Medida] | [Responsável] |

Considerar, conforme aplicabilidade:

- Aplicações e bancos de dados.
- Infraestrutura, redes e conectividade.
- Identidades e controle de acesso.
- Integrações e interfaces.
- Fornecedores e serviços em nuvem.
- Usuários e áreas de negócio.
- Monitoramento e ferramentas de segurança.
- Cópias de segurança e procedimentos de recuperação.
- Processos operacionais e atividades críticas.

## 8. Plano de implementação

| Etapa | Atividade | Responsável | Início previsto | Conclusão prevista | Critério de conclusão |
|---|---|---|---|---|---|
| 1 | [Preparação] | [Responsável] | [Data/hora] | [Data/hora] | [Critério] |
| 2 | [Execução] | [Responsável] | [Data/hora] | [Data/hora] | [Critério] |
| 3 | [Validação] | [Responsável] | [Data/hora] | [Data/hora] | [Critério] |
| 4 | [Encerramento] | [Responsável] | [Data/hora] | [Data/hora] | [Critério] |

O plano deve identificar a sequência de execução, os responsáveis, os recursos necessários, as dependências e os critérios que demonstram a conclusão de cada etapa.

Quando houver necessidade de janela de manutenção, registrar o período aprovado e os critérios para início, suspensão ou interrupção da execução.

## 9. Testes e validações prévias

| Teste ou validação | Ambiente | Critério de sucesso | Responsável | Resultado | Evidência |
|---|---|---|---|---|---|
| [Teste funcional] | [Ambiente] | [Critério] | [Responsável] | [Pendente / Aprovado / Reprovado] | [Referência] |
| [Teste de segurança] | [Ambiente] | [Critério] | [Responsável] | [Resultado] | [Referência] |
| [Teste de integração] | [Ambiente] | [Critério] | [Responsável] | [Resultado] | [Referência] |
| [Teste de recuperação] | [Ambiente] | [Critério] | [Responsável] | [Resultado] | [Referência] |

Os testes devem ser proporcionais ao risco e à complexidade da mudança.

Quando um teste não for aplicável, registrar a justificativa. Quando os resultados forem insuficientes ou inconclusivos, a aprovação deve considerar expressamente essa limitação.

## 10. Plano de retorno ou reversão

A mudança deve prever, quando tecnicamente viável e proporcional ao risco, como retornar a uma condição estável caso a implementação falhe ou produza impactos inaceitáveis.

**Critérios para iniciar a reversão:**

[Descrever as condições objetivas que exigem a interrupção ou o retorno.]

**Procedimento de reversão:**

[Referenciar o procedimento controlado ou descrever as etapas necessárias.]

**Responsável pela decisão:** [Função ou autoridade]

**Responsável pela execução:** [Função ou equipe]

**Tempo estimado para reversão:** [Estimativa validada, quando disponível]

**Dependências e limitações:**

[Descrever restrições técnicas ou operacionais.]

**Critérios para validar a reversão:**

[Definir como será confirmada a estabilidade do ambiente.]

**Evidência do teste de reversão, quando aplicável:**

[Referência]

Uma reversão pode não ser viável em todas as mudanças. Nesses casos, registrar a justificativa e definir medidas alternativas de mitigação e recuperação.

## 11. Aprovação da mudança

| Papel ou área | Decisão | Responsável | Data | Referência da aprovação |
|---|---|---|---|---|
| Responsável técnico | [Aprovar / Rejeitar / Solicitar ajustes] | [Responsável] | [Data] | [Referência] |
| Responsável pelo serviço | [Decisão] | [Responsável] | [Data] | [Referência] |
| Segurança da informação | [Decisão / Não aplicável com justificativa] | [Responsável] | [Data] | [Referência] |
| Gestor ou autoridade competente | [Decisão] | [Responsável] | [Data] | [Referência] |

As aprovações devem seguir a matriz de autoridade da organização e considerar a criticidade e os riscos da mudança.

A execução não deve ser considerada autorizada apenas porque a solicitação foi registrada.

## 12. Comunicação e janela de execução

**Janela aprovada:** [Data e horário]

**Áreas a comunicar:** [Lista]

**Responsável pela comunicação:** [Função]

**Canal de comunicação:** [Canal aprovado]

**Plano de comunicação:**

[Descrever os avisos necessários antes, durante e após a mudança.]

**Plano de contingência de comunicação:**

[Descrever alternativas, quando necessárias.]

As comunicações devem indicar os impactos previstos, os períodos de indisponibilidade, as orientações aos usuários e os canais para reporte de problemas, conforme aplicável.

## 13. Execução e registro das atividades

| Data e hora | Atividade executada | Responsável | Resultado | Desvio ou observação | Evidência |
|---|---|---|---|---|---|
| [Data/hora] | [Descrição] | [Responsável] | [Resultado] | [Observação] | [Referência] |
| [Data/hora] | [Descrição] | [Responsável] | [Resultado] | [Observação] | [Referência] |

Registrar as atividades efetivamente realizadas, incluindo desvios do plano, decisões emergenciais, interrupções e alterações de escopo.

Se a mudança não puder ser executada conforme o planejado, documentar a decisão de continuar, interromper, ajustar ou reverter a implementação.

## 14. Validação após a implementação

| Verificação | Critério esperado | Resultado observado | Atendido? | Evidência |
|---|---|---|---|---|
| Funcionamento do serviço | [Critério] | [Resultado] | [Sim / Não / Parcial] | [Referência] |
| Integridade dos dados | [Critério] | [Resultado] | [Sim / Não / Não aplicável] | [Referência] |
| Controles de segurança | [Critério] | [Resultado] | [Sim / Não / Parcial] | [Referência] |
| Integrações e dependências | [Critério] | [Resultado] | [Sim / Não / Parcial] | [Referência] |
| Monitoramento e logs | [Critério] | [Resultado] | [Sim / Não / Parcial] | [Referência] |
| Aceitação do serviço | [Critério] | [Resultado] | [Sim / Não / Pendente] | [Referência] |

**Resultado geral:** [Aprovado / Aprovado com ressalvas / Revertido / Inconclusivo]

**Responsável pela validação:** [Função ou nome]

**Data da validação:** [AAAA-MM-DD]

A conclusão deve ser baseada em evidências. A ausência de problemas imediatamente após a implantação não comprova, por si só, que todos os riscos foram eliminados.

## 15. Tratamento de falhas e incidentes relacionados

Se a mudança provocar falha, degradação ou incidente de segurança, registrar a ocorrência conforme os processos aplicáveis.

| Campo | Preenchimento |
|---|---|
| Incidente relacionado | [Identificador, quando aplicável] |
| Descrição da ocorrência | [Descrição] |
| Impacto observado | [Descrição] |
| Ação imediata | [Descrição] |
| Decisão sobre a mudança | [Continuar / Suspender / Reverter / Outra] |
| Responsável pela decisão | [Função] |
| Evidências | [Referências] |

A gestão da mudança e o tratamento do incidente são processos relacionados, mas distintos. Manter a rastreabilidade entre os registros sem substituir um processo pelo outro.

## 16. Encerramento da mudança

**Situação final:** [Concluída / Concluída com ressalvas / Revertida / Cancelada / Pendente]

**Resumo do resultado:**

[Descrever o que foi implementado, validado ou revertido.]

**Pendências remanescentes:**

[Relacionar ações, riscos ou verificações ainda necessários.]

**Responsável pelo encerramento:** [Função ou nome]

**Data do encerramento:** [AAAA-MM-DD]

**Aprovação final:** [Responsável e referência]

O encerramento administrativo deve refletir a situação real da mudança. Pendências relevantes precisam permanecer registradas e ser acompanhadas por responsáveis e prazos definidos.

## 17. Lições aprendidas e melhoria contínua

Após mudanças relevantes, avaliar:

- O planejamento foi adequado?
- A avaliação de riscos identificou os impactos principais?
- Os testes foram suficientes?
- As aprovações ocorreram antes da execução?
- A janela de implementação foi adequada?
- O plano de reversão era viável?
- A comunicação foi tempestiva?
- Os critérios de validação foram atendidos?
- Houve falhas ou incidentes associados?
- Existem oportunidades de simplificação ou melhoria do processo?

**Lições aprendidas:** [Descrição]

**Ações de melhoria:** [Referências]

**Responsáveis e prazos:** [Definir]

## 18. Indicadores possíveis

A organização pode acompanhar indicadores como:

- Percentual de mudanças executadas com aprovação prévia.
- Percentual de mudanças concluídas com sucesso.
- Taxa de mudanças revertidas.
- Quantidade de incidentes associados a mudanças.
- Percentual de mudanças com avaliação de riscos documentada.
- Percentual de mudanças com testes e evidências registrados.
- Percentual de mudanças emergenciais.
- Percentual de ações de melhoria concluídas no prazo.

Cada indicador deve possuir definição, método de cálculo, fonte de dados, responsável e periodicidade documentados.

Os resultados devem ser interpretados considerando a criticidade, a complexidade e o perfil das mudanças realizadas.

## 19. Controle de acesso e retenção dos registros

Os registros de mudanças podem conter informações técnicas, operacionais e organizacionais sensíveis.

A organização deve definir:

- Quem pode criar, consultar, alterar e aprovar registros.
- Como as alterações serão rastreadas.
- Onde as evidências serão armazenadas.
- Qual prazo de retenção será aplicado.
- Como serão protegidas as informações de infraestrutura.
- Como ocorrerá o descarte seguro dos registros.

Senhas, tokens, chaves privadas e outros segredos não devem ser inseridos neste documento nem publicados em repositórios públicos.

## 20. Checklist de qualidade

- [ ] A mudança possui identificador e justificativa.
- [ ] O escopo e os impactos foram documentados.
- [ ] Os riscos foram avaliados.
- [ ] As dependências foram identificadas.
- [ ] O plano de implementação possui responsáveis e critérios de conclusão.
- [ ] Os testes necessários foram definidos e registrados.
- [ ] A necessidade de reversão foi avaliada.
- [ ] As aprovações necessárias foram obtidas antes da execução.
- [ ] A comunicação foi planejada quando aplicável.
- [ ] A execução possui registro cronológico e evidências.
- [ ] A validação após a implementação foi documentada.
- [ ] Falhas e incidentes relacionados foram tratados.
- [ ] Pendências possuem responsáveis e prazos.
- [ ] O encerramento reflete o resultado real da mudança.

## 21. Limitações e orientações de uso

Este modelo deve ser adaptado à arquitetura, às ferramentas, aos níveis de criticidade e à governança de mudanças da organização.

O registro não substitui procedimentos técnicos, ferramentas de gestão de mudanças, controles automatizados ou mecanismos de aprovação.

O preenchimento do documento não comprova, isoladamente, a conformidade com a ISO/IEC 27001:2022. A conformidade depende da implementação efetiva dos requisitos e controles aplicáveis, da operação dos processos e da existência de evidências apropriadas.

## 22. Histórico de revisão

| Versão | Data | Descrição da alteração | Responsável |
|---|---|---|---|
| 1.0 | [AAAA-MM-DD] | Criação do modelo para adaptação | [Responsável] |
