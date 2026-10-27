# Modelo de Registro de Vulnerabilidades e Gestão de Correções

## 1. Objetivo

Este documento apresenta um modelo para registrar, avaliar, priorizar, tratar e acompanhar vulnerabilidades de segurança da informação identificadas em ativos, sistemas, aplicações, infraestrutura e serviços tecnológicos.

O registro permite organizar as informações sobre a vulnerabilidade, avaliar sua criticidade no contexto da organização, definir medidas de tratamento, atribuir responsabilidades e documentar as evidências de correção ou mitigação.

O modelo também apoia a integração entre gestão de vulnerabilidades, gestão de riscos, gestão de mudanças e tratamento de incidentes no contexto do Sistema de Gestão de Segurança da Informação (SGSI).

**Importante:** este arquivo é um modelo de referência. Seu preenchimento não comprova que uma organização tenha identificado, corrigido ou eliminado vulnerabilidades reais.

## 2. Referências relacionadas

Considerar, conforme aplicabilidade:

- ISO/IEC 27001:2022, requisitos relacionados à avaliação de riscos, ao tratamento de riscos, à operação e à melhoria do SGSI.
- ISO/IEC 27001:2022, Anexo A, controles relacionados à gestão de vulnerabilidades técnicas, gestão de mudanças e segurança dos sistemas.
- Política de Segurança da Informação.
- Metodologia de Gestão de Riscos de Segurança da Informação.
- Procedimento de gestão de mudanças.
- Procedimento de resposta a incidentes.
- Inventário de ativos e serviços de informação.
- Procedimentos de atualização e correção de sistemas.
- Requisitos contratuais, legais e regulatórios aplicáveis.

A seleção e a aplicação dos controles devem considerar o contexto organizacional, os riscos identificados e a Declaração de Aplicabilidade (SoA).

## 3. Identificação do registro

| Campo | Preenchimento |
|---|---|
| Identificador do registro | [VULN-AAAA-NNN] |
| Título da vulnerabilidade | [Descrição resumida] |
| Data de identificação | [AAAA-MM-DD] |
| Origem da identificação | [Ferramenta / Auditoria / Fornecedor / Análise técnica / Outra] |
| Responsável pelo registro | [Função ou nome] |
| Área responsável pelo tratamento | [Área ou equipe] |
| Situação | [Identificada / Em avaliação / Planejada / Em tratamento / Mitigada / Corrigida / Aceita formalmente / Encerrada] |
| Classificação da informação | [Classificação aplicável] |
| Referência técnica externa | [Identificador público, quando aplicável] |

O identificador deve permitir relacionar a vulnerabilidade aos ativos afetados, aos riscos correspondentes, às mudanças executadas e às evidências de tratamento.

## 4. Descrição da vulnerabilidade

**Descrição objetiva:**

[Descrever a vulnerabilidade identificada, a condição observada e os recursos potencialmente afetados.]

**Origem da informação:**

[Indicar a ferramenta, o relatório, o fornecedor, a auditoria ou a análise que identificou a vulnerabilidade.]

**Evidências disponíveis:**

[Relacionar os relatórios, registros ou referências que sustentam a identificação.]

**Condição de exploração conhecida:**

[Registrar informações confirmadas sobre a possibilidade de exploração. Distinguir fatos de hipóteses.]

**Limitações da avaliação:**

[Descrever eventuais limitações de escopo, acesso, ferramenta ou evidência.]

A descrição deve conter informações suficientes para permitir a avaliação e o tratamento, evitando divulgar detalhes operacionais sensíveis em registros públicos.

## 5. Ativos e componentes afetados

| Identificador do ativo | Ativo ou componente | Ambiente | Responsável pelo ativo | Exposição conhecida |
|---|---|---|---|---|
| [ATV-001] | [Sistema ou componente] | [Produção / Homologação / Desenvolvimento / Outro] | [Responsável] | [Descrição] |
| [ATV-002] | [Sistema ou componente] | [Ambiente] | [Responsável] | [Descrição] |

Avaliar, conforme aplicabilidade:

- Sistemas operacionais.
- Aplicações e componentes de software.
- Bibliotecas e dependências.
- Equipamentos de rede e segurança.
- Servidores e máquinas virtuais.
- Dispositivos de usuário.
- Serviços em nuvem.
- Contêineres e plataformas de execução.
- Serviços de terceiros e componentes gerenciados por fornecedores.

A identificação do ativo deve ser consistente com o inventário de ativos da organização.

## 6. Avaliação da criticidade

A criticidade deve considerar informações técnicas disponíveis e o contexto real do ativo.

| Critério | Avaliação | Justificativa ou evidência |
|---|---|---|
| Severidade técnica informada pela fonte | [Classificação ou valor] | [Referência] |
| Facilidade de exploração | [Avaliação] | [Justificativa] |
| Exposição do ativo | [Interno / Externo / Restrito / Outra] | [Descrição] |
| Existência de exploração conhecida | [Sim / Não / Desconhecido] | [Referência] |
| Criticidade do ativo | [Classificação interna] | [Justificativa] |
| Impacto potencial no negócio | [Classificação interna] | [Justificativa] |
| Existência de controles compensatórios | [Sim / Não / Parcial] | [Descrição] |

**Prioridade de tratamento:** [Conforme critérios internos]

**Responsável pela avaliação:** [Função ou nome]

**Data da avaliação:** [AAAA-MM-DD]

A severidade técnica divulgada por uma fonte externa não deve ser utilizada isoladamente para definir a prioridade. A avaliação precisa considerar a exposição, a criticidade do ativo, os impactos possíveis e os controles existentes.

Quando aplicável, utilizar referências técnicas reconhecidas, como identificadores CVE e métricas CVSS, registrando a versão e a fonte consultada.

## 7. Decisão de tratamento

**Decisão:**

- [ ] Corrigir por atualização ou substituição do componente.
- [ ] Aplicar configuração corretiva.
- [ ] Implementar medida de mitigação temporária.
- [ ] Restringir a exposição ou o acesso.
- [ ] Desabilitar temporariamente o recurso afetado.
- [ ] Transferir o tratamento para fornecedor responsável.
- [ ] Aceitar formalmente o risco residual, conforme a governança definida.
- [ ] Realizar investigação complementar.
- [ ] Outra medida: [Descrever].

**Justificativa da decisão:**

[Explicar por que a medida escolhida é adequada ao risco identificado.]

**Responsável pela decisão:** [Função ou autoridade competente]

**Data da decisão:** [AAAA-MM-DD]

**Referência do risco relacionado:** [Identificador, quando aplicável]

A aceitação formal do risco deve seguir os critérios e os níveis de autoridade estabelecidos pela organização. Ela não equivale à correção da vulnerabilidade.

## 8. Plano de tratamento

| Ação | Tipo | Responsável | Prazo | Critério de conclusão | Evidência esperada |
|---|---|---|---|---|---|
| [Descrição] | [Correção / Mitigação / Investigação / Outra] | [Responsável] | [Data] | [Critério] | [Referência] |
| [Descrição] | [Tipo] | [Responsável] | [Data] | [Critério] | [Referência] |

O plano deve definir as atividades necessárias, os responsáveis, os prazos e as evidências que permitirão verificar a conclusão.

Quando a correção depender de fornecedor, registrar a dependência, a previsão de atendimento, as alternativas disponíveis e o responsável interno pelo acompanhamento.

## 9. Gestão de correções e mudanças

As correções que alterem sistemas, configurações ou serviços devem seguir o processo de gestão de mudanças aplicável.

Registrar, quando necessário:

| Campo | Preenchimento |
|---|---|
| Identificador da mudança | [Identificador] |
| Procedimento ou pacote de correção | [Referência] |
| Ambiente de validação | [Ambiente] |
| Testes prévios | [Referência e resultado] |
| Aprovação necessária | [Responsável e referência] |
| Janela de implementação | [Data e horário] |
| Plano de reversão | [Referência] |
| Responsável pela execução | [Responsável] |
| Resultado da implementação | [Resultado] |

A correção não deve ser considerada concluída apenas porque foi instalada ou aplicada. A organização deve verificar se a vulnerabilidade deixou de estar presente e se a mudança não introduziu problemas inaceitáveis.

## 10. Medidas de mitigação temporária

Quando a correção imediata não for viável, documentar as medidas temporárias adotadas para reduzir a exposição ou o impacto potencial.

| Medida de mitigação | Risco tratado | Responsável | Data de implementação | Validação | Condição de encerramento |
|---|---|---|---|---|---|
| [Descrição] | [Risco] | [Responsável] | [Data] | [Evidência] | [Condição] |

Exemplos possíveis incluem restrição de acesso, segmentação de rede, desativação de funcionalidades vulneráveis ou aplicação de regras adicionais de monitoramento.

A eficácia das medidas deve ser avaliada conforme o risco. Mitigações temporárias precisam ter responsáveis, prazo de revisão e condição definida para encerramento ou substituição.

## 11. Verificação da correção

| Campo | Preenchimento |
|---|---|
| Data da verificação | [AAAA-MM-DD] |
| Responsável pela verificação | [Função ou nome] |
| Método utilizado | [Ferramenta / Teste / Inspeção / Outro] |
| Ativos verificados | [Lista ou referência] |
| Resultado | [Corrigida / Parcialmente corrigida / Não corrigida / Inconclusivo] |
| Evidência da verificação | [Referência controlada] |
| Limitações | [Descrição] |

**Conclusão técnica:**

[Descrever o resultado com base nas evidências disponíveis.]

A verificação deve confirmar que o tratamento alcançou o resultado esperado, considerando os limites do método utilizado.

Se o método não permitir comprovar a eliminação da vulnerabilidade, registrar essa limitação e definir a necessidade de investigação adicional.

## 12. Avaliação de risco residual

Após a correção ou mitigação, avaliar se permanece algum risco relevante.

| Campo | Preenchimento |
|---|---|
| Risco residual identificado | [Descrição] |
| Classificação atualizada | [Conforme metodologia interna] |
| Controles remanescentes | [Descrição] |
| Tratamento adicional necessário | [Sim / Não / A avaliar] |
| Responsável pela avaliação | [Responsável] |
| Aprovação, quando necessária | [Autoridade competente] |
| Referência do registro de risco | [Identificador] |

O encerramento da vulnerabilidade deve ser coerente com o resultado técnico e com a decisão sobre o risco residual. Quando o risco permanecer, registrar o tratamento aprovado e as condições de acompanhamento.

## 13. Vulnerabilidades relacionadas a incidentes

Quando houver indícios de exploração ou comprometimento, avaliar a necessidade de acionar o processo de resposta a incidentes.

**Há evidências de exploração?** [Sim / Não / A investigar]

**Incidente relacionado:** [Identificador, quando aplicável]

**Ações de investigação:** [Descrição]

**Medidas de contenção:** [Descrição]

**Responsável pelo acompanhamento:** [Responsável]

**Referências de evidências:** [Localização controlada]

A identificação de uma vulnerabilidade não comprova que ela tenha sido explorada. Da mesma forma, a ausência de evidência de exploração não demonstra necessariamente que ela não ocorreu.

## 14. Exceções e aceitação formal de risco

Quando a organização decidir não corrigir uma vulnerabilidade dentro do prazo inicialmente previsto, a decisão deve ser documentada conforme a governança de riscos.

| Campo | Preenchimento |
|---|---|
| Justificativa da exceção | [Descrição] |
| Risco residual | [Descrição] |
| Medidas compensatórias | [Descrição] |
| Autoridade responsável pela aceitação | [Função] |
| Data da aprovação | [AAAA-MM-DD] |
| Prazo de validade da exceção | [Data ou condição] |
| Data da próxima revisão | [AAAA-MM-DD] |
| Condição para reavaliação | [Descrição] |

A aceitação deve ser explícita, fundamentada, limitada e revisável. Não deve ser utilizada para substituir indefinidamente o tratamento necessário sem avaliação do risco e das alternativas disponíveis.

## 15. Indicadores possíveis

A organização pode acompanhar indicadores como:

- Quantidade de vulnerabilidades abertas por criticidade.
- Percentual de vulnerabilidades tratadas dentro do prazo definido.
- Tempo médio entre identificação e tratamento.
- Quantidade de vulnerabilidades críticas vencidas.
- Percentual de ativos críticos cobertos por avaliações de vulnerabilidade.
- Percentual de correções verificadas após implementação.
- Quantidade de exceções de risco vigentes.
- Percentual de ações de mitigação revisadas no prazo.
- Recorrência de vulnerabilidades relacionadas à mesma causa.

Cada indicador deve possuir definição, método de cálculo, fonte de dados, responsável e periodicidade documentados.

Os indicadores devem considerar o escopo das avaliações, a qualidade dos dados e os critérios de classificação utilizados.

## 16. Controle de acesso e proteção dos registros

Os registros de vulnerabilidades podem conter informações técnicas sensíveis, incluindo detalhes sobre ativos, versões de software, exposição e medidas de proteção.

A organização deve definir:

- Quem pode consultar, criar, alterar e aprovar os registros.
- Como as alterações serão rastreadas.
- Onde as evidências serão armazenadas.
- Qual prazo de retenção será aplicado.
- Como serão compartilhados relatórios com fornecedores.
- Como evitar a exposição de informações que facilitem ataques.

Detalhes operacionais sensíveis, credenciais, tokens, chaves e informações de exploração que não sejam necessárias à finalidade do registro não devem ser publicados em repositórios públicos.

## 17. Checklist de qualidade

- [ ] A vulnerabilidade possui identificador único.
- [ ] A descrição é sustentada por uma fonte ou evidência.
- [ ] Os ativos afetados foram identificados.
- [ ] A criticidade considera o contexto do ativo e o impacto potencial.
- [ ] A decisão de tratamento está documentada.
- [ ] As ações possuem responsáveis e prazos.
- [ ] As correções seguem o processo de mudanças aplicável.
- [ ] As medidas temporárias possuem critérios de revisão.
- [ ] A correção foi verificada com evidências apropriadas.
- [ ] O risco residual foi avaliado.
- [ ] A necessidade de resposta a incidentes foi considerada.
- [ ] As exceções possuem aprovação e prazo de revisão.
- [ ] Os registros estão protegidos e rastreáveis.

## 18. Limitações e orientações de uso

Este modelo deve ser adaptado às ferramentas, aos processos, à arquitetura tecnológica e aos critérios de risco da organização.

O registro de uma vulnerabilidade não comprova sua correção. A conclusão deve estar fundamentada em evidências adequadas ao método de verificação utilizado.

A priorização deve considerar a criticidade técnica e o contexto de negócio, sem presumir que todas as vulnerabilidades classificadas de forma semelhante apresentem o mesmo risco.

O preenchimento deste documento não comprova, isoladamente, a conformidade com a ISO/IEC 27001:2022. A conformidade depende da implementação efetiva dos requisitos e controles aplicáveis, da operação dos processos e da existência de evidências apropriadas.

## 19. Histórico de revisão

| Versão | Data | Descrição da alteração | Responsável |
|---|---|---|---|
| 1.0 | [AAAA-MM-DD] | Criação do modelo para adaptação | [Responsável] |
