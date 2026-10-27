# Modelo de Registro de Testes de Recuperação e Continuidade

## 1. Objetivo

Este documento apresenta um modelo para planejar, registrar, avaliar e acompanhar testes de recuperação de serviços de TI e exercícios de continuidade de negócios.

O registro permite verificar se os procedimentos documentados são executáveis, se os recursos necessários estão disponíveis e se os resultados observados atendem aos critérios definidos previamente.

Também fornece evidências para a identificação de lacunas, o tratamento de riscos e a melhoria dos planos de continuidade, recuperação de desastres e resposta a incidentes.

**Importante:** este documento é um modelo de referência. Seu conteúdo não comprova que um teste tenha sido realizado nem que os objetivos de recuperação tenham sido atingidos.

## 2. Referências relacionadas

Considerar, conforme aplicabilidade:

- Plano de Continuidade de Negócios.
- Plano de Recuperação de Desastres de TI.
- Plano de Resposta a Incidentes de Segurança da Informação.
- Metodologia de Gestão de Riscos de Segurança da Informação.
- Procedimentos de cópia de segurança e restauração.
- Procedimentos de operação e recuperação dos serviços.
- ISO/IEC 27001:2022, especialmente os requisitos relacionados à operação, avaliação de desempenho e melhoria.
- ISO/IEC 27001:2022, Anexo A, controles aplicáveis à preparação de TIC para continuidade de negócios.

A escolha dos testes deve considerar os riscos, os objetivos de recuperação e os requisitos aplicáveis ao escopo do SGSI.

## 3. Identificação do teste

| Campo | Preenchimento |
|---|---|
| Identificador do teste | [TESTE-AAAA-NNN] |
| Título | [Nome do teste ou exercício] |
| Tipo | [Teste técnico / Exercício de mesa / Simulação / Outro] |
| Plano relacionado | [Identificador ou referência] |
| Serviço ou processo abrangido | [Descrição] |
| Responsável pelo teste | [Função ou nome] |
| Aprovador | [Função ou autoridade competente] |
| Data planejada | [AAAA-MM-DD] |
| Data de execução | [AAAA-MM-DD ou pendente] |
| Ambiente | [Desenvolvimento / Homologação / Produção / Outro] |
| Situação | [Planejado / Em execução / Concluído / Cancelado] |
| Classificação do registro | [Classificação de informação] |

## 4. Objetivo e escopo

**Objetivo do teste:**

[Descrever a capacidade ou o procedimento que será validado.]

**Escopo incluído:**

[Relacionar os serviços, sistemas, processos, equipes e recursos abrangidos.]

**Escopo excluído:**

[Relacionar exclusões e justificar sua aplicação.]

**Hipótese ou cenário testado:**

[Descrever a interrupção simulada ou a condição de recuperação avaliada.]

**Premissas:**

[Registrar as condições consideradas verdadeiras para a execução.]

**Restrições:**

[Registrar limitações técnicas, operacionais, contratuais ou de segurança.]

## 5. Critérios de sucesso

Os critérios devem ser definidos antes da execução para reduzir avaliações subjetivas dos resultados.

| Critério | Resultado esperado | Método de verificação | Responsável pela validação |
|---|---|---|---|
| Disponibilidade do serviço | [Condição esperada] | [Teste ou evidência] | [Responsável] |
| Integridade dos dados | [Condição esperada] | [Verificação] | [Responsável] |
| RTO | [Tempo máximo aprovado] | [Medição] | [Responsável] |
| RPO | [Limite aprovado de perda de dados temporal] | [Verificação] | [Responsável] |
| Controles de segurança | [Condição esperada] | [Verificação] | [Responsável] |
| Aprovação operacional | [Critério] | [Validação] | [Responsável] |

Os valores de RTO e RPO devem ser obtidos dos objetivos aprovados pela organização. Não devem ser presumidos ou definidos apenas para facilitar a aprovação do teste.

Quando um critério não for aplicável, registrar a justificativa.

## 6. Preparação e autorização

Antes da execução, confirmar:

- [ ] O objetivo e o escopo foram aprovados.
- [ ] Os participantes foram informados.
- [ ] O ambiente e os recursos estão disponíveis.
- [ ] Os riscos do teste foram avaliados.
- [ ] O impacto potencial sobre serviços produtivos foi considerado.
- [ ] Os critérios de interrupção do teste foram definidos.
- [ ] As cópias de segurança necessárias foram verificadas.
- [ ] As evidências que serão coletadas foram definidas.
- [ ] Os contatos e responsáveis estão disponíveis.
- [ ] Existe procedimento para retorno ao estado anterior, quando aplicável.
- [ ] Os fornecedores necessários foram acionados, quando aplicável.

**Responsável pela autorização:** [Função]

**Data da autorização:** [AAAA-MM-DD]

**Referência da aprovação:** [Identificador ou localização controlada]

Testes que possam afetar serviços produtivos devem ser planejados e autorizados previamente. A execução não deve introduzir riscos desproporcionais para a organização ou para seus clientes.

## 7. Recursos e dependências

| Recurso ou dependência | Finalidade | Disponibilidade confirmada? | Responsável | Observações |
|---|---|---|---|---|
| [Sistema ou infraestrutura] | [Finalidade] | [Sim / Não / Pendente] | [Responsável] | [Observação] |
| [Cópia de segurança] | [Finalidade] | [Sim / Não / Pendente] | [Responsável] | [Observação] |
| [Fornecedor ou equipe] | [Finalidade] | [Sim / Não / Pendente] | [Responsável] | [Observação] |

Registrar as dependências necessárias à execução e as limitações identificadas antes do início.

## 8. Procedimento de execução

| Etapa | Procedimento ou atividade | Responsável | Resultado esperado | Evidência |
|---|---|---|---|---|
| 1 | [Preparação do cenário] | [Responsável] | [Resultado] | [Referência] |
| 2 | [Execução do procedimento] | [Responsável] | [Resultado] | [Referência] |
| 3 | [Validação técnica] | [Responsável] | [Resultado] | [Referência] |
| 4 | [Validação operacional] | [Responsável] | [Resultado] | [Referência] |
| 5 | [Encerramento e retorno] | [Responsável] | [Resultado] | [Referência] |

Descrever o procedimento com detalhe suficiente para permitir a compreensão do que foi executado e a comparação entre o resultado esperado e o resultado observado.

Quando forem utilizadas instruções técnicas específicas, referenciar o procedimento controlado correspondente.

## 9. Registro cronológico da execução

| Data e hora | Atividade ou evento | Responsável | Resultado observado | Evidência |
|---|---|---|---|---|
| [Data/hora] | [Descrição] | [Responsável] | [Resultado] | [Referência] |
| [Data/hora] | [Descrição] | [Responsável] | [Resultado] | [Referência] |

Registrar os horários de início e conclusão das etapas relevantes, as decisões tomadas, os desvios observados e eventuais interrupções.

Utilizar uma referência temporal consistente, indicando o fuso horário quando necessário.

## 10. Resultados obtidos

| Critério | Resultado esperado | Resultado observado | Atendido? | Evidência |
|---|---|---|---|---|
| [Critério] | [Esperado] | [Observado] | [Sim / Não / Parcial] | [Referência] |
| [Critério] | [Esperado] | [Observado] | [Sim / Não / Parcial] | [Referência] |

**Resultado geral:** [Aprovado / Aprovado com ressalvas / Reprovado / Inconclusivo]

**Justificativa:**

[Explicar o resultado com base nos critérios estabelecidos antes da execução.]

Um resultado inconclusivo deve ser registrado quando não houver evidências suficientes para avaliar os critérios. A ausência de evidências não deve ser interpretada como comprovação de sucesso.

## 11. Avaliação de RTO e RPO

### 11.1 Tempo de recuperação

| Campo | Registro |
|---|---|
| RTO aprovado | [Valor e unidade] |
| Início da interrupção ou marco de referência | [Data e hora] |
| Marco de recuperação definido | [Descrição] |
| Horário do marco de recuperação | [Data e hora] |
| Tempo de recuperação observado | [Valor e unidade] |
| Objetivo atendido? | [Sim / Não / Inconclusivo] |

A medição deve utilizar os marcos de início e recuperação definidos pela organização, de modo que os resultados sejam comparáveis entre testes.

### 11.2 Ponto de recuperação

| Campo | Registro |
|---|---|
| RPO aprovado | [Valor e unidade] |
| Referência temporal dos dados esperados | [Data e hora] |
| Referência temporal dos dados recuperados | [Data e hora] |
| Perda de dados observada | [Valor e unidade, quando mensurável] |
| Objetivo atendido? | [Sim / Não / Inconclusivo] |
| Evidência da validação | [Referência] |

A avaliação do RPO deve considerar a definição adotada pela organização e a capacidade de verificar a consistência dos dados recuperados.

Se o teste não permitir medir o RPO de forma confiável, registrar a limitação e definir a necessidade de validação complementar.

## 12. Validação de segurança da informação

A recuperação deve ser avaliada também sob a perspectiva de segurança da informação.

| Verificação | Resultado | Evidência ou justificativa |
|---|---|---|
| Integridade dos dados recuperados | [Resultado] | [Referência] |
| Controles de acesso e privilégios | [Resultado] | [Referência] |
| Configurações de segurança relevantes | [Resultado] | [Referência] |
| Registro e monitoramento de eventos | [Resultado] | [Referência] |
| Proteção das cópias de segurança | [Resultado] | [Referência] |
| Eliminação ou restrição de acessos temporários | [Resultado] | [Referência] |
| Validação de riscos residuais | [Resultado] | [Referência] |

As verificações devem ser adaptadas ao tipo de teste, ao serviço recuperado e aos riscos envolvidos.

## 13. Desvios, falhas e limitações

| Identificador | Descrição do desvio | Impacto | Causa conhecida ou hipótese | Tratamento necessário |
|---|---|---|---|---|
| [DESV-001] | [Descrição] | [Impacto] | [Causa ou hipótese] | [Ação] |

Registrar os desvios em relação ao procedimento, aos critérios de sucesso ou aos objetivos de recuperação.

Distinguir fatos confirmados de hipóteses. Quando a causa não estiver determinada, indicar a necessidade de investigação complementar.

## 14. Ações de melhoria

| Ação | Tipo | Responsável | Prazo | Critério de conclusão | Evidência |
|---|---|---|---|---|---|
| [Descrição] | [Correção / Ação corretiva / Melhoria / Tratamento de risco] | [Responsável] | [Data] | [Critério] | [Referência] |

As ações devem ser priorizadas de acordo com o impacto, a urgência e o risco associado às lacunas identificadas.

Quando uma falha representar não conformidade, utilizar também o processo específico de registro de não conformidades e ações corretivas, mantendo a rastreabilidade entre os documentos.

## 15. Conclusão e aprovação

**Conclusão do teste:**

[Resumir os resultados, os critérios atendidos, as limitações e os principais desvios.]

**Capacidade de recuperação demonstrada:**

[Descrever somente as capacidades efetivamente verificadas pelas evidências.]

**Lacunas remanescentes:**

[Relacionar as lacunas ainda não resolvidas.]

**Necessidade de novo teste:**

[Sim / Não / A avaliar, com justificativa.]

**Responsável pela execução:** [Nome ou função]

**Responsável pela validação dos resultados:** [Nome ou função]

**Aprovador:** [Nome ou função]

**Data de aprovação:** [AAAA-MM-DD]

A aprovação do relatório confirma a análise dos resultados documentados. Ela não deve ser interpretada como garantia de sucesso em todos os cenários futuros de interrupção.

## 16. Acompanhamento posterior

| Ação pendente | Responsável | Prazo | Situação | Evidência de conclusão |
|---|---|---|---|---|
| [Descrição] | [Responsável] | [Data] | [Situação] | [Referência] |

As ações pendentes devem ser acompanhadas até sua conclusão ou até que uma decisão formal, fundamentada e autorizada estabeleça outro tratamento.

## 17. Indicadores possíveis

A organização pode utilizar os registros de testes para acompanhar:

- Percentual de testes concluídos em relação aos planejados.
- Percentual de critérios de sucesso atendidos.
- Percentual de testes que atingiram o RTO aprovado.
- Percentual de testes que atingiram o RPO aprovado.
- Quantidade de desvios relevantes identificados.
- Percentual de ações de melhoria concluídas dentro do prazo.
- Tempo médio de recuperação observado nos testes comparáveis.
- Recorrência de falhas identificadas em exercícios anteriores.

Cada indicador deve ter definição, método de cálculo, fonte de dados, responsável e periodicidade documentados.

## 18. Controle e proteção do registro

O registro e suas evidências devem ser protegidos de acordo com sua classificação e sensibilidade.

A organização deve definir:

- Quem pode consultar, criar, alterar e aprovar os registros.
- Como as alterações serão rastreadas.
- Onde as evidências serão armazenadas.
- Qual prazo de retenção será aplicado.
- Como será controlado o acesso a dados técnicos sensíveis.
- Como ocorrerá o descarte seguro, quando autorizado.

Credenciais, segredos técnicos, informações pessoais desnecessárias e detalhes que facilitem ataques não devem ser inseridos em repositórios públicos.

## 19. Checklist de qualidade

- [ ] O teste possui identificador e objetivo definidos.
- [ ] O escopo e o cenário estão documentados.
- [ ] Os critérios de sucesso foram estabelecidos antes da execução.
- [ ] A execução foi autorizada.
- [ ] Os resultados observados possuem evidências.
- [ ] RTO e RPO foram avaliados quando aplicáveis.
- [ ] Os aspectos de segurança da informação foram considerados.
- [ ] Desvios e limitações foram registrados.
- [ ] As ações de melhoria possuem responsáveis e prazos.
- [ ] A conclusão foi analisada e aprovada.
- [ ] As evidências e os registros estão protegidos.

## 20. Limitações e orientações de uso

Este modelo deve ser adaptado ao contexto da organização, aos procedimentos técnicos existentes e aos objetivos de recuperação aprovados.

O preenchimento do documento, sem execução real e evidências adequadas, não demonstra que a recuperação ou a continuidade tenham sido testadas.

Os resultados de um teste representam as condições observadas naquele exercício. Mudanças de ambiente, arquitetura, dados, fornecedores ou procedimentos podem alterar a capacidade de recuperação e exigir novas validações.

## 21. Histórico de revisão

| Versão | Data | Descrição da alteração | Responsável |
|---|---|---|---|
| 1.0 | [AAAA-MM-DD] | Criação do modelo para adaptação | [Responsável] |
