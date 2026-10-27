# Modelo de Registro de Gestão de Acessos e Revisão de Permissões

## 1. Objetivo

Este documento apresenta um modelo para registrar solicitações, aprovações, concessões, alterações, revisões e revogações de acessos a sistemas, aplicações, infraestrutura e informações.

O objetivo é apoiar a governança de identidades e acessos, a aplicação do princípio do menor privilégio, a segregação de funções e a rastreabilidade das decisões relacionadas às permissões.

O modelo pode ser utilizado como referência para estruturar controles de acesso no contexto de um Sistema de Gestão de Segurança da Informação (SGSI).

**Importante:** este arquivo é um modelo de referência. Seu conteúdo não comprova que uma organização tenha implementado um processo de gestão de acessos nem que as permissões estejam adequadamente configuradas.

## 2. Referências relacionadas

Considerar, conforme aplicabilidade:

- ISO/IEC 27001:2022, requisitos relacionados à operação, à avaliação de desempenho e à melhoria do SGSI.
- ISO/IEC 27001:2022, Anexo A, controles relativos a gestão de identidades, informações de autenticação, direitos de acesso e acessos privilegiados.
- Política de Segurança da Informação.
- Política ou procedimento de controle de acesso.
- Procedimento de admissão, movimentação e desligamento de pessoas.
- Processo de gestão de mudanças.
- Metodologia de gestão de riscos.
- Inventário de ativos e serviços de informação.
- Requisitos legais, regulatórios e contratuais aplicáveis.

A seleção dos controles deve considerar o contexto, os riscos e a Declaração de Aplicabilidade (SoA) da organização.

## 3. Identificação do registro

| Campo | Preenchimento |
|---|---|
| Identificador do registro | [ACESSO-AAAA-NNN] |
| Organização | [Nome da organização] |
| Área responsável pelo processo | [Área] |
| Responsável pelo registro | [Função ou nome] |
| Aprovador do processo | [Função ou autoridade competente] |
| Data de criação | [AAAA-MM-DD] |
| Última atualização | [AAAA-MM-DD] |
| Versão | [Número] |
| Classificação da informação | [Classificação aplicável] |
| Local oficial do registro | [Referência controlada] |

## 4. Inventário de sistemas e recursos abrangidos

| Identificador | Sistema, aplicação ou recurso | Responsável pelo recurso | Criticidade | Método de autenticação |
|---|---|---|---|---|
| [REC-001] | [Descrição] | [Responsável] | [Classificação interna] | [Método] |
| [REC-002] | [Descrição] | [Responsável] | [Classificação interna] | [Método] |

O inventário deve identificar os recursos cujo acesso é gerenciado pelo processo e os responsáveis pelas decisões de autorização.

Quando aplicável, considerar aplicações corporativas, diretórios de identidade, plataformas em nuvem, ferramentas administrativas, bancos de dados, infraestrutura, dispositivos e serviços de terceiros.

## 5. Registro de solicitação de acesso

| Campo | Preenchimento |
|---|---|
| Identificador da solicitação | [SOL-AAAA-NNN] |
| Data da solicitação | [AAAA-MM-DD] |
| Solicitante | [Pessoa ou função] |
| Identidade ou conta de destino | [Identificador corporativo] |
| Área ou equipe | [Área] |
| Tipo de solicitação | [Novo acesso / Alteração / Elevação de privilégio / Revogação] |
| Sistema ou recurso | [Recurso] |
| Perfil ou permissão solicitada | [Descrição] |
| Justificativa de negócio | [Descrição] |
| Data de início necessária | [AAAA-MM-DD] |
| Data de término, quando aplicável | [AAAA-MM-DD] |
| Responsável pela aprovação | [Função ou nome] |
| Situação | [Pendente / Aprovada / Rejeitada / Executada / Cancelada] |

A solicitação deve conter informações suficientes para avaliar a necessidade do acesso, a compatibilidade com as responsabilidades da pessoa e os riscos envolvidos.

## 6. Avaliação e aprovação

Antes da concessão ou alteração de permissões, avaliar:

- Necessidade de negócio.
- Compatibilidade com a função exercida.
- Princípio do menor privilégio.
- Segregação de funções.
- Sensibilidade das informações acessadas.
- Criticidade do sistema.
- Duração necessária do acesso.
- Existência de acesso privilegiado.
- Possíveis conflitos de interesse.
- Requisitos legais, contratuais ou regulatórios.

**Decisão:** [Aprovada / Rejeitada / Aprovada com restrições]

**Justificativa:** [Descrição]

**Responsável pela decisão:** [Função ou nome]

**Data da decisão:** [AAAA-MM-DD]

**Restrições ou condições:** [Descrição]

A aprovação deve ser realizada por pessoa autorizada, de acordo com a matriz de responsabilidades definida pela organização. O solicitante não deve aprovar automaticamente o próprio acesso quando isso contrariar as regras de governança aplicáveis.

## 7. Registro da concessão ou alteração

| Campo | Preenchimento |
|---|---|
| Identificador da execução | [EXEC-AAAA-NNN] |
| Solicitação relacionada | [Identificador] |
| Identidade ou conta | [Identificador corporativo] |
| Recurso de destino | [Sistema ou serviço] |
| Perfil ou permissão aplicada | [Descrição] |
| Responsável pela execução | [Função ou equipe] |
| Data e hora da execução | [Data/hora e fuso, se necessário] |
| Resultado | [Concluído / Parcial / Falha] |
| Evidência de execução | [Referência controlada] |
| Validação posterior | [Resultado e responsável] |

O registro deve diferenciar a aprovação da solicitação da execução técnica da mudança.

Quando a execução falhar ou ocorrer parcialmente, documentar a situação, o risco associado e as medidas adotadas para concluir ou reverter a alteração.

## 8. Gestão de acessos privilegiados

Acessos administrativos ou privilegiados podem aumentar o impacto de erros, abusos ou comprometimentos. A organização deve estabelecer critérios específicos para sua concessão, utilização, monitoramento e revisão.

| Campo | Preenchimento |
|---|---|
| Identificador do acesso privilegiado | [PRIV-AAAA-NNN] |
| Identidade ou conta | [Identificador] |
| Sistema ou recurso | [Recurso] |
| Justificativa | [Descrição] |
| Escopo do privilégio | [Permissões] |
| Aprovação específica | [Responsável e referência] |
| Prazo ou condição de expiração | [Data ou condição] |
| Medidas adicionais de proteção | [Descrição] |
| Monitoramento aplicável | [Referência] |
| Data da última revisão | [AAAA-MM-DD] |

Conforme os riscos, considerar contas administrativas separadas, autenticação reforçada, concessão temporária de privilégios, monitoramento de atividades e restrição de acesso a informações de autenticação.

Segredos, senhas, tokens e chaves não devem ser registrados neste documento.

## 9. Movimentação de pessoas e mudanças de função

Mudanças de função, equipe, responsabilidade ou vínculo podem exigir a revisão dos acessos existentes.

| Identificador | Pessoa ou identidade | Mudança ocorrida | Acessos a revisar | Responsável | Prazo |
|---|---|---|---|---|---|
| [MOV-001] | [Identificador corporativo] | [Descrição] | [Recursos] | [Responsável] | [Data] |

O processo deve avaliar se as permissões anteriores permanecem necessárias, se novos acessos precisam ser concedidos e se existem conflitos de segregação de funções.

A concessão de novos acessos não deve resultar automaticamente na manutenção de todas as permissões anteriores.

## 10. Desligamento e revogação de acessos

| Campo | Preenchimento |
|---|---|
| Identificador da revogação | [REV-AAAA-NNN] |
| Identidade ou conta | [Identificador corporativo] |
| Motivo da revogação | [Descrição] |
| Data e hora de referência | [Data/hora] |
| Recursos abrangidos | [Lista ou referência controlada] |
| Responsável pela execução | [Responsável] |
| Data e hora da execução | [Data/hora] |
| Resultado | [Concluído / Parcial / Falha] |
| Evidência de revogação | [Referência] |
| Pendências identificadas | [Descrição] |

O processo deve considerar, conforme aplicabilidade, contas corporativas, aplicações, acessos remotos, sessões, dispositivos, credenciais, privilégios administrativos e acessos concedidos por fornecedores.

Os prazos e os gatilhos de revogação devem ser definidos conforme o risco, a natureza do vínculo e os procedimentos da organização.

## 11. Revisão periódica de acessos

A revisão deve confirmar se os acessos permanecem necessários, adequados e autorizados.

**Identificador da revisão:** [REVISAO-AAAA-NNN]

**Período avaliado:** [Período]

**Sistemas abrangidos:** [Lista ou referência]

**Responsável pela revisão:** [Função]

**Data de início:** [AAAA-MM-DD]

**Data de conclusão:** [AAAA-MM-DD]

### 11.1 Registro individual da revisão

| Identidade ou conta | Sistema | Permissão atual | Necessidade confirmada? | Decisão | Ação necessária |
|---|---|---|---|---|---|
| [Identificador] | [Sistema] | [Permissão] | [Sim / Não / Pendente] | [Manter / Ajustar / Revogar / Investigar] | [Descrição] |
| [Identificador] | [Sistema] | [Permissão] | [Sim / Não / Pendente] | [Decisão] | [Descrição] |

A revisão deve utilizar informações atualizadas e considerar as responsabilidades atuais, a criticidade do recurso e os critérios internos de acesso.

A ausência de resposta de um responsável não deve ser interpretada automaticamente como confirmação da necessidade do acesso.

## 12. Tratamento de acessos inadequados

| Identificador | Acesso ou situação identificada | Risco associado | Ação definida | Responsável | Prazo | Evidência |
|---|---|---|---|---|---|---|
| [NC-ACESSO-001] | [Descrição] | [Risco] | [Ação] | [Responsável] | [Data] | [Referência] |

Exemplos de situações que podem exigir tratamento:

- Permissões incompatíveis com a função exercida.
- Contas sem responsável identificado.
- Contas inativas que permanecem habilitadas.
- Privilégios excessivos.
- Acessos não aprovados.
- Contas compartilhadas sem justificativa ou controles apropriados.
- Falta de evidência de revisão.
- Acessos de terceiros mantidos após o término da necessidade.

As ações devem ser priorizadas conforme a severidade e o risco. Quando a situação configurar não conformidade, utilizar também o processo de registro de não conformidades e ações corretivas.

## 13. Segregação de funções

A organização deve identificar atividades e permissões cuja combinação possa criar conflitos ou permitir ações indevidas sem controles compensatórios.

| Atividade ou combinação de permissões | Risco potencial | Regra definida | Controle compensatório, se aplicável | Responsável pela avaliação |
|---|---|---|---|---|
| [Descrição] | [Risco] | [Regra] | [Controle] | [Responsável] |

A avaliação deve considerar as funções reais, os riscos, os requisitos de negócio e os controles compensatórios aprovados.

Quando uma segregação completa não for viável, registrar a justificativa, a autorização e as medidas utilizadas para reduzir o risco.

## 14. Acessos de terceiros e fornecedores

| Campo | Preenchimento |
|---|---|
| Identificador do acesso | [TERC-AAAA-NNN] |
| Fornecedor | [Nome] |
| Pessoa ou identidade | [Identificador autorizado] |
| Serviço contratado | [Descrição] |
| Recursos acessados | [Lista ou referência] |
| Justificativa | [Descrição] |
| Responsável interno | [Responsável] |
| Aprovação | [Referência] |
| Período autorizado | [Início e término] |
| Restrições aplicáveis | [Descrição] |
| Data da última revisão | [AAAA-MM-DD] |
| Condição de encerramento | [Descrição] |

Os acessos de terceiros devem ter escopo, duração, responsabilidade e condições de encerramento definidos.

A organização deve avaliar os riscos relacionados a acessos remotos, privilégios, subcontratação e dependência de fornecedores.

## 15. Indicadores possíveis

A organização pode utilizar indicadores como:

- Percentual de acessos revisados no período.
- Percentual de revisões concluídas dentro do prazo.
- Quantidade de permissões inadequadas identificadas.
- Quantidade de acessos privilegiados sem justificativa atualizada.
- Tempo entre o desligamento e a revogação efetiva dos acessos.
- Percentual de solicitações com aprovação e evidência de execução.
- Quantidade de contas sem responsável identificado.
- Percentual de ações de revisão concluídas no prazo.
- Quantidade de exceções de segregação de funções ainda vigentes.

Cada indicador deve ter definição, método de cálculo, fonte de dados, responsável e periodicidade documentados.

Os resultados devem ser analisados considerando o escopo dos sistemas, a qualidade dos registros e os critérios de classificação adotados.

## 16. Proteção e retenção dos registros

Os registros de acesso podem conter informações pessoais, organizacionais e técnicas sensíveis.

A organização deve definir:

- Permissões de consulta, alteração e aprovação.
- Rastreabilidade das mudanças.
- Local de armazenamento das evidências.
- Prazo de retenção.
- Critérios para compartilhamento.
- Procedimentos de descarte seguro.
- Tratamento de informações pessoais conforme os requisitos aplicáveis.

Este modelo não deve ser preenchido com senhas, tokens, chaves privadas ou outros segredos de autenticação.

## 17. Checklist de qualidade

- [ ] Os sistemas e recursos abrangidos estão identificados.
- [ ] As solicitações possuem justificativa de negócio.
- [ ] As aprovações foram registradas por pessoas autorizadas.
- [ ] As concessões e alterações possuem evidências de execução.
- [ ] Os acessos privilegiados foram avaliados conforme os riscos.
- [ ] As movimentações de pessoas geram revisão das permissões.
- [ ] Os desligamentos contemplam a revogação dos acessos pertinentes.
- [ ] As revisões periódicas possuem responsáveis e prazos.
- [ ] As permissões inadequadas geram ações de tratamento.
- [ ] As exceções de segregação de funções estão justificadas.
- [ ] Os acessos de terceiros possuem prazo e responsável.
- [ ] Os registros estão protegidos e são rastreáveis.

## 18. Limitações e orientações de uso

Este modelo deve ser adaptado à arquitetura tecnológica, às ferramentas de identidade, às responsabilidades e aos requisitos da organização.

O preenchimento dos registros não comprova, isoladamente, que as permissões estejam corretas em todos os sistemas. A efetividade do processo depende da qualidade dos dados, da execução das mudanças, da revisão dos acessos e da existência de evidências verificáveis.

A conformidade com a ISO/IEC 27001:2022 deve ser avaliada considerando os requisitos e controles aplicáveis, sua implementação efetiva e a operação do SGSI.

## 19. Histórico de revisão

| Versão | Data | Descrição da alteração | Responsável |
|---|---|---|---|
| 1.0 | [AAAA-MM-DD] | Criação do modelo para adaptação | [Responsável] |
