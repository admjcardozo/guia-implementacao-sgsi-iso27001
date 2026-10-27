# Modelo de Registro de Cópias de Segurança e Testes de Restauração

## 1. Objetivo

Este documento apresenta um modelo para registrar e acompanhar a gestão de cópias de segurança (*backups*) e os testes de restauração de dados, sistemas e serviços de TI.

O modelo permite documentar os recursos protegidos, a periodicidade das cópias, os critérios de retenção, os responsáveis, os resultados das execuções e as evidências de testes de restauração.

Seu propósito é apoiar a gestão de riscos, a continuidade de negócios, a recuperação de serviços e a avaliação dos controles de segurança da informação.

**Importante:** este arquivo é um modelo de referência. Seu preenchimento não comprova, por si só, que as cópias de segurança estejam sendo executadas corretamente ou que os dados possam ser recuperados.

## 2. Referências relacionadas

Considerar, conforme aplicabilidade:

- ISO/IEC 27001:2022, requisitos relacionados à operação, à avaliação de desempenho e à melhoria do SGSI.
- ISO/IEC 27001:2022, Anexo A, controle 8.13 — cópias de segurança da informação.
- ISO/IEC 27001:2022, Anexo A, controle 8.14 — redundância de recursos de processamento de informação, quando aplicável.
- Política de Segurança da Informação.
- Política ou procedimento de cópias de segurança.
- Plano de Continuidade de Negócios.
- Plano de Recuperação de Desastres de TI.
- Metodologia de Gestão de Riscos de Segurança da Informação.
- Procedimentos de classificação, retenção e descarte de informações.

A seleção e a aplicação dos controles devem considerar os riscos, o escopo do SGSI e a Declaração de Aplicabilidade (SoA).

## 3. Identificação e controle do documento

| Campo | Preenchimento |
|---|---|
| Identificador do registro | [BACKUP-AAAA-NNN] |
| Organização | [Nome da organização] |
| Área responsável | [Área ou equipe] |
| Responsável técnico | [Função ou nome] |
| Aprovador | [Função ou autoridade competente] |
| Data de criação | [AAAA-MM-DD] |
| Última atualização | [AAAA-MM-DD] |
| Versão | [Número] |
| Classificação da informação | [Classificação aplicável] |
| Local oficial do registro | [Referência controlada] |

## 4. Inventário de recursos protegidos

| Identificador | Sistema, serviço ou conjunto de dados | Responsável pelo ativo | Criticidade | Classificação da informação |
|---|---|---|---|---|
| [ATV-001] | [Descrição] | [Responsável] | [Classificação interna] | [Classificação] |
| [ATV-002] | [Descrição] | [Responsável] | [Classificação interna] | [Classificação] |

O inventário deve permitir identificar os recursos abrangidos pelas cópias de segurança e relacioná-los aos responsáveis e aos requisitos de recuperação.

Devem ser avaliados, conforme aplicabilidade, bancos de dados, arquivos, configurações, aplicações, máquinas virtuais, serviços em nuvem e outros recursos necessários à recuperação das atividades.

## 5. Requisitos de cópia de segurança

| Recurso | Frequência definida | Tipo de cópia | Retenção | Local de armazenamento | Responsável |
|---|---|---|---|---|---|
| [Recurso] | [Periodicidade] | [Completa / Incremental / Diferencial / Outra] | [Prazo] | [Referência controlada] | [Responsável] |
| [Recurso] | [Periodicidade] | [Tipo] | [Prazo] | [Referência controlada] | [Responsável] |

A frequência, o tipo de cópia e a retenção devem ser definidos com base na criticidade, nos requisitos de recuperação, na capacidade técnica, nos custos e nas obrigações aplicáveis.

Os prazos e as configurações devem ser aprovados pela organização. Os campos deste modelo não estabelecem valores universais.

## 6. Objetivos de recuperação

| Recurso | RPO aprovado | RTO aprovado | Responsável pela aprovação | Referência da decisão |
|---|---|---|---|---|
| [Recurso] | [Valor e unidade] | [Valor e unidade] | [Responsável] | [Referência] |

O RPO representa o ponto no tempo até o qual os dados devem ser recuperados, conforme o objetivo definido pela organização.

O RTO representa o período-alvo para restabelecer o recurso ou serviço, conforme os critérios de recuperação estabelecidos.

Os objetivos devem ser coerentes com a análise de impacto nos negócios e com os planos de continuidade e recuperação. A capacidade real de atendê-los precisa ser verificada por testes e evidências.

## 7. Proteção das cópias de segurança

A organização deve avaliar e documentar as medidas de proteção aplicáveis aos repositórios e aos processos de backup.

| Medida de proteção | Aplicabilidade | Implementação ou referência | Evidência |
|---|---|---|---|
| Controle de acesso | [Sim / Não / A avaliar] | [Descrição] | [Referência] |
| Autenticação e gestão de privilégios | [Sim / Não / A avaliar] | [Descrição] | [Referência] |
| Criptografia, quando necessária | [Sim / Não / A avaliar] | [Descrição] | [Referência] |
| Proteção contra alteração ou exclusão indevida | [Sim / Não / A avaliar] | [Descrição] | [Referência] |
| Separação entre ambientes ou repositórios | [Sim / Não / A avaliar] | [Descrição] | [Referência] |
| Monitoramento e registro de atividades | [Sim / Não / A avaliar] | [Descrição] | [Referência] |
| Proteção contra ameaças que afetem os backups | [Sim / Não / A avaliar] | [Descrição] | [Referência] |

A aplicação dessas medidas deve considerar o contexto, as ameaças, os riscos e a arquitetura utilizada. Não marcar uma medida como implementada sem evidência suficiente.

## 8. Registro das execuções de backup

| Identificador da execução | Recurso protegido | Início | Conclusão | Resultado | Referência da evidência |
|---|---|---|---|---|---|
| [BKP-001] | [Recurso] | [Data/hora] | [Data/hora] | [Sucesso / Falha / Parcial] | [Referência] |
| [BKP-002] | [Recurso] | [Data/hora] | [Data/hora] | [Resultado] | [Referência] |

Para cada execução, registrar os resultados fornecidos pela ferramenta ou pelo procedimento utilizado.

Quando houver falha ou execução parcial, documentar o impacto potencial, a ação corretiva ou de recuperação e a confirmação da execução posterior, quando aplicável.

A indicação de sucesso pela ferramenta não substitui as verificações de integridade e os testes de restauração necessários.

## 9. Tratamento de falhas de backup

| Campo | Preenchimento |
|---|---|
| Identificador da falha | [FALHA-AAAA-NNN] |
| Execução relacionada | [Identificador] |
| Data e hora da identificação | [Data/hora] |
| Recurso afetado | [Recurso] |
| Descrição da falha | [Descrição] |
| Impacto potencial | [Descrição] |
| Responsável pelo tratamento | [Responsável] |
| Ação imediata | [Descrição] |
| Causa identificada ou hipótese | [Descrição] |
| Prazo para resolução | [Data] |
| Resultado da correção | [Descrição] |
| Evidência de conclusão | [Referência] |

Se a falha comprometer requisitos de recuperação ou elevar significativamente o risco, avaliar o escalonamento aos responsáveis pelos serviços, pela continuidade e pelo SGSI.

Quando a ocorrência configurar uma não conformidade, registrar e tratar o caso também pelo processo de não conformidades e ações corretivas.

## 10. Planejamento do teste de restauração

| Campo | Preenchimento |
|---|---|
| Identificador do teste | [REST-AAAA-NNN] |
| Recurso ou conjunto de dados | [Descrição] |
| Objetivo do teste | [Objetivo] |
| Escopo | [Escopo incluído e excluído] |
| Cópia selecionada | [Identificador ou referência] |
| Ambiente de restauração | [Ambiente] |
| Data planejada | [AAAA-MM-DD] |
| Responsável pela execução | [Responsável] |
| Responsável pela validação | [Responsável] |
| Autorização necessária | [Responsável e referência] |
| Critérios de sucesso | [Critérios] |

O teste deve ser planejado de forma a reduzir riscos para os ambientes produtivos e evitar a exposição indevida de informações.

Quando houver dados pessoais, informações confidenciais ou dados de clientes, o ambiente de teste deve dispor de controles adequados ao tipo de informação utilizada.

## 11. Procedimento e execução da restauração

| Etapa | Atividade | Responsável | Horário de início | Horário de conclusão | Resultado ou evidência |
|---|---|---|---|---|---|
| 1 | Seleção e verificação da cópia | [Responsável] | [Data/hora] | [Data/hora] | [Referência] |
| 2 | Preparação do ambiente | [Responsável] | [Data/hora] | [Data/hora] | [Referência] |
| 3 | Execução da restauração | [Responsável] | [Data/hora] | [Data/hora] | [Referência] |
| 4 | Validação técnica | [Responsável] | [Data/hora] | [Data/hora] | [Referência] |
| 5 | Validação operacional | [Responsável] | [Data/hora] | [Data/hora] | [Referência] |
| 6 | Encerramento e limpeza controlada | [Responsável] | [Data/hora] | [Data/hora] | [Referência] |

Os procedimentos técnicos detalhados devem ser mantidos em documentação controlada apropriada. Este registro deve apontar para as instruções utilizadas, sem expor credenciais, segredos ou configurações sensíveis desnecessariamente.

## 12. Validação dos dados e do serviço recuperado

| Verificação | Critério esperado | Resultado observado | Atendido? | Evidência |
|---|---|---|---|---|
| Integridade dos dados | [Critério] | [Resultado] | [Sim / Não / Inconclusivo] | [Referência] |
| Consistência das informações | [Critério] | [Resultado] | [Sim / Não / Inconclusivo] | [Referência] |
| Disponibilidade do recurso | [Critério] | [Resultado] | [Sim / Não / Inconclusivo] | [Referência] |
| Funcionamento da aplicação | [Critério] | [Resultado] | [Sim / Não / Inconclusivo] | [Referência] |
| Controles de acesso | [Critério] | [Resultado] | [Sim / Não / Inconclusivo] | [Referência] |
| Registros e monitoramento | [Critério] | [Resultado] | [Sim / Não / Inconclusivo] | [Referência] |

Os critérios de validação devem ser adequados ao tipo de recurso restaurado. Uma restauração tecnicamente concluída não comprova necessariamente que os dados estejam íntegros ou que o serviço esteja operacional.

## 13. Resultado do teste de restauração

**Resultado geral:** [Aprovado / Aprovado com ressalvas / Reprovado / Inconclusivo]

**Tempo observado de restauração:** [Valor e unidade]

**RPO avaliado:** [Resultado ou não aplicável]

**RTO avaliado:** [Resultado ou não aplicável]

**Desvios identificados:** [Descrição]

**Limitações do teste:** [Descrição]

**Conclusão técnica:** [Conclusão baseada nas evidências]

**Responsável pela validação:** [Responsável]

**Data da validação:** [AAAA-MM-DD]

A conclusão deve indicar quais capacidades foram efetivamente verificadas e quais permanecem sem comprovação.

## 14. Desvios e ações de melhoria

| Identificador | Desvio ou lacuna | Risco associado | Ação necessária | Responsável | Prazo |
|---|---|---|---|---|---|
| [DESV-001] | [Descrição] | [Risco] | [Ação] | [Responsável] | [Data] |

As ações devem possuir critérios verificáveis de conclusão e evidências de implementação.

Quando necessário, atualizar a avaliação de riscos, os procedimentos de backup, os planos de continuidade e os critérios de recuperação.

## 15. Revisão de riscos e controles

| Questão | Avaliação | Justificativa ou referência |
|---|---|---|
| As cópias atendem às necessidades de recuperação? | [Sim / Não / Parcial] | [Referência] |
| A frequência precisa ser revisada? | [Sim / Não / A avaliar] | [Justificativa] |
| A retenção precisa ser revisada? | [Sim / Não / A avaliar] | [Justificativa] |
| Os controles de proteção são adequados? | [Sim / Não / Parcial] | [Referência] |
| A avaliação de riscos precisa ser atualizada? | [Sim / Não / A avaliar] | [Referência] |
| A SoA precisa ser revisada? | [Sim / Não / A avaliar] | [Justificativa] |

As decisões devem ser baseadas nas evidências, nos requisitos aplicáveis e na metodologia de gestão de riscos da organização.

## 16. Indicadores possíveis

A organização pode acompanhar:

- Percentual de execuções de backup concluídas com sucesso.
- Quantidade de falhas de backup por período.
- Percentual de recursos críticos abrangidos por cópias de segurança.
- Percentual de testes de restauração realizados conforme o planejamento.
- Percentual de testes de restauração aprovados.
- Percentual de testes que atenderam ao RTO e ao RPO definidos.
- Tempo médio observado de restauração em testes comparáveis.
- Percentual de ações de melhoria concluídas no prazo.

Cada indicador deve ter definição, método de cálculo, fonte de dados, responsável e periodicidade documentados.

Os resultados devem ser interpretados considerando a criticidade dos recursos, as diferenças entre ambientes e as limitações dos testes.

## 17. Controle de acesso, retenção e proteção dos registros

Os registros de backup e restauração podem conter informações técnicas sensíveis e devem ser protegidos conforme sua classificação.

A organização deve definir:

- Permissões de consulta, alteração e aprovação.
- Rastreabilidade das alterações.
- Local de armazenamento das evidências.
- Prazo de retenção.
- Proteção de logs e relatórios técnicos.
- Procedimentos de descarte seguro.
- Tratamento de informações pessoais ou confidenciais.

Credenciais, chaves, tokens e segredos técnicos não devem ser inseridos neste registro nem publicados em repositórios públicos.

## 18. Checklist de qualidade

- [ ] Os recursos protegidos estão identificados.
- [ ] A frequência e a retenção das cópias estão definidas.
- [ ] Os objetivos de recuperação foram documentados.
- [ ] As execuções possuem registros e evidências.
- [ ] As falhas possuem responsáveis e ações de tratamento.
- [ ] Os testes de restauração possuem critérios de sucesso.
- [ ] A execução foi autorizada quando necessário.
- [ ] Os resultados foram validados tecnicamente.
- [ ] Os desvios e riscos residuais foram documentados.
- [ ] As ações de melhoria possuem prazos e critérios de conclusão.
- [ ] Os registros estão protegidos e rastreáveis.

## 19. Limitações e orientações de uso

Este modelo deve ser adaptado aos recursos tecnológicos, às ferramentas, aos requisitos de recuperação e aos procedimentos da organização.

A existência de cópias de segurança ou de relatórios de execução não garante que os dados sejam recuperáveis. A capacidade de restauração precisa ser avaliada por meio de testes apropriados e evidências verificáveis.

O preenchimento deste documento não comprova, isoladamente, a conformidade com a ISO/IEC 27001:2022. A conformidade depende da implementação efetiva dos requisitos e controles aplicáveis, de sua operação e da existência de evidências adequadas.

## 20. Histórico de revisão

| Versão | Data | Descrição da alteração | Responsável |
|---|---|---|---|
| 1.0 | [AAAA-MM-DD] | Criação do modelo para adaptação | [Responsável] |
