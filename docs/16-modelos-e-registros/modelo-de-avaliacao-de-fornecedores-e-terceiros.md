# Modelo de Avaliação de Fornecedores e Terceiros

## 1. Objetivo

Este documento apresenta um modelo de referência para avaliar e acompanhar os riscos de Segurança da Informação relacionados a fornecedores, prestadores de serviços, parceiros e outros terceiros que possam afetar o Sistema de Gestão de Segurança da Informação (SGSI).

O modelo busca apoiar a identificação de terceiros relevantes, a análise dos serviços prestados, a avaliação de riscos, a definição de requisitos de segurança e o acompanhamento das medidas acordadas.

Sua aplicação deve considerar o contexto organizacional, o escopo do SGSI, a criticidade dos serviços, os dados tratados, os acessos concedidos e as obrigações legais, regulatórias e contratuais aplicáveis.

**Importante:** este documento é um modelo conceitual. Seu conteúdo não comprova que fornecedores tenham sido avaliados ou que requisitos contratuais tenham sido implementados em uma organização real.

## 2. Referências e alinhamento

A aplicação deste modelo deve considerar, conforme a pertinência:

- ISO/IEC 27001:2022 — requisitos relativos ao contexto, à gestão de riscos, ao controle operacional, à avaliação de desempenho e à informação documentada.
- ISO/IEC 27002:2022 — orientações relacionadas à segurança da informação nas relações com fornecedores, aos acordos com terceiros e à gestão da cadeia de fornecimento de tecnologia.
- ISO/IEC 27005 — orientações para gestão de riscos de Segurança da Informação.
- Lei nº 13.709/2018 (LGPD), quando houver tratamento de dados pessoais.
- Requisitos legais, regulatórios e contratuais aplicáveis ao serviço.
- Políticas internas de compras, contratação, gestão de terceiros, privacidade e Segurança da Informação.

A organização deve consultar as normas oficiais e determinar quais requisitos são aplicáveis ao seu contexto. Este modelo não substitui a consulta às normas.

## 3. Escopo da avaliação

A avaliação pode ser aplicada a:

- Fornecedores de sistemas, aplicações e serviços em nuvem.
- Empresas de suporte, manutenção e operação de tecnologia.
- Prestadores com acesso físico ou lógico a ambientes organizacionais.
- Terceiros que armazenem, processem, transmitam ou tenham acesso a informações da organização.
- Operadores ou outros agentes envolvidos no tratamento de dados pessoais, conforme os papéis efetivamente exercidos.
- Fornecedores de infraestrutura, conectividade, hospedagem, backup e recuperação.
- Empresas responsáveis por serviços críticos ou essenciais ao negócio.
- Parceiros e subcontratados cuja atuação possa afetar a segurança da informação.

A organização deve estabelecer critérios para determinar quais terceiros serão avaliados e o nível de profundidade necessário.

## 4. Identificação do fornecedor

| Campo | Descrição ou orientação |
|---|---|
| Identificador do registro | Código único para rastreabilidade. |
| Razão social ou nome | Identificação formal do fornecedor ou terceiro. |
| CNPJ ou identificador equivalente | Identificador legal, quando aplicável. |
| Serviço contratado | Descrição do produto ou serviço fornecido. |
| Área contratante | Área organizacional responsável pela contratação ou utilização. |
| Responsável interno | Papel ou pessoa responsável pelo relacionamento com o fornecedor. |
| Responsável do fornecedor | Contato autorizado para assuntos contratuais e de segurança, quando disponível. |
| Data de início do relacionamento | Data de início da contratação ou prestação do serviço. |
| Vigência contratual | Prazo de vigência, quando aplicável. |
| Situação | Em avaliação, aprovado, aprovado com condições, suspenso, encerrado ou outra situação definida. |
| Contrato ou referência | Identificador ou localização do contrato e dos documentos pertinentes. |
| Subcontratação | Indicação de subcontratados relevantes, quando conhecidos e aplicáveis. |

O registro deve conter apenas os dados necessários à finalidade da avaliação e ser protegido conforme as regras internas de acesso e retenção.

## 5. Caracterização do serviço

Antes da avaliação, devem ser identificadas as características do serviço e sua relação com a organização.

| Campo | Descrição ou orientação |
|---|---|
| Finalidade do serviço | Necessidade de negócio atendida. |
| Processos suportados | Processos que dependem do serviço. |
| Criticidade para o negócio | Impacto potencial da indisponibilidade ou comprometimento do serviço. |
| Informações tratadas | Categorias de informação acessadas, armazenadas, processadas ou transmitidas. |
| Dados pessoais | Indicação de tratamento de dados pessoais, quando aplicável. |
| Tipo de acesso | Sem acesso, acesso físico, acesso lógico, acesso administrativo ou outra categoria definida. |
| Ambientes envolvidos | Produção, homologação, desenvolvimento, ambiente corporativo ou outros ambientes pertinentes. |
| Local de processamento ou armazenamento | Localização ou região, quando conhecida e relevante. |
| Dependências relevantes | Sistemas, fornecedores ou serviços dos quais a solução depende. |
| Requisitos de disponibilidade | Requisitos definidos para a continuidade do serviço. |
| Requisitos de recuperação | Objetivos e condições de recuperação, quando aplicáveis. |
| Impacto de interrupção | Consequências previstas para a organização. |

As informações devem ser verificadas com a área contratante, a equipe técnica, Segurança da Informação, privacidade e outras funções pertinentes.

## 6. Classificação de criticidade do fornecedor

A organização deve estabelecer critérios próprios para classificar os terceiros. O exemplo abaixo é ilustrativo e deve ser adaptado.

| Nível ilustrativo | Caracterização | Abordagem sugerida |
|---|---|---|
| Crítico | A interrupção ou o comprometimento pode causar impacto grave sobre processos essenciais, informações sensíveis ou obrigações relevantes. | Avaliação aprofundada, requisitos formais de segurança, acompanhamento definido e análise de continuidade. |
| Alto | O fornecedor possui acesso relevante ou suporta processos importantes. | Avaliação de riscos, verificação dos requisitos pertinentes e revisões periódicas. |
| Moderado | O serviço apresenta impacto limitado, mas pode afetar informações ou operações organizacionais. | Avaliação proporcional ao risco e acompanhamento conforme critérios internos. |
| Baixo | A relação possui exposição limitada e não envolve dependências ou acessos significativos identificados. | Verificação básica documentada e reavaliação quando houver mudança de contexto. |

A criticidade não deve ser definida exclusivamente pelo valor financeiro do contrato. Devem ser considerados o impacto operacional, a sensibilidade das informações, os acessos, a dependência do serviço e as consequências de um incidente.

## 7. Questionário de avaliação de segurança

As perguntas abaixo constituem uma base de avaliação. Devem ser adaptadas à natureza do serviço e ao nível de risco.

### 7.1 Governança e responsabilidades

- O fornecedor possui responsabilidades formalmente definidas para Segurança da Informação?
- Existem políticas ou diretrizes de segurança aplicáveis ao serviço contratado?
- Há responsáveis identificados para tratar incidentes e solicitações relacionadas à segurança?
- O fornecedor realiza avaliações de risco pertinentes ao serviço?
- Há processo para comunicar mudanças relevantes na operação ou na arquitetura do serviço?

### 7.2 Gestão de acessos

- O acesso aos ambientes e às informações é concedido conforme a necessidade de uso?
- Existem processos para conceder, alterar, revisar e revogar acessos?
- Os acessos privilegiados são controlados e monitorados de forma compatível com o risco?
- Há autenticação reforçada para acessos sensíveis, quando apropriado?
- Os acessos de colaboradores desligados ou terceiros cujo contrato terminou são revogados tempestivamente?

### 7.3 Proteção das informações

- Existem medidas para proteger a confidencialidade, a integridade e a disponibilidade das informações?
- As informações são protegidas durante armazenamento e transmissão, conforme os riscos?
- A classificação e o tratamento das informações são compatíveis com os requisitos acordados?
- Existem controles para prevenir divulgação, alteração ou acesso não autorizado?
- Os dados são segregados de forma apropriada quando o serviço é compartilhado entre clientes?

### 7.4 Vulnerabilidades e atualizações

- Existe processo para identificar e tratar vulnerabilidades relevantes?
- As atualizações de segurança são priorizadas segundo critérios de risco?
- O fornecedor comunica vulnerabilidades que possam afetar o serviço contratado?
- Há procedimentos para tratar falhas críticas e medidas temporárias de mitigação?
- São realizados testes de segurança adequados à natureza do serviço, quando pertinentes?

### 7.5 Incidentes de segurança

- Existe processo formal para identificar, registrar, classificar e tratar incidentes?
- O fornecedor comunica incidentes que possam afetar a organização?
- Os prazos, os canais e os critérios de comunicação estão definidos contratualmente ou em procedimento aplicável?
- Há processo para preservar evidências e investigar incidentes?
- São realizadas análises posteriores e ações corretivas, conforme a necessidade?

### 7.6 Continuidade e recuperação

- O fornecedor possui planos de continuidade ou recuperação compatíveis com a criticidade do serviço?
- Existem cópias de segurança quando necessárias?
- Os procedimentos de restauração são testados de acordo com o risco?
- As dependências críticas são conhecidas e avaliadas?
- Existem alternativas ou medidas de contingência para interrupções relevantes?

### 7.7 Pessoas e subcontratação

- Os profissionais que acessam informações ou ambientes estão sujeitos a requisitos de confidencialidade?
- Existem processos de integração, capacitação e desligamento compatíveis com o serviço?
- O uso de subcontratados é controlado e informado conforme os requisitos aplicáveis?
- Os requisitos de segurança são estendidos aos subcontratados pertinentes?
- O fornecedor comunica mudanças relevantes na equipe ou nos terceiros envolvidos?

### 7.8 Privacidade e requisitos legais

- O tratamento de dados pessoais, quando existente, está documentado?
- Os papéis e as responsabilidades relativos ao tratamento foram definidos conforme as circunstâncias reais?
- Existem instruções e acordos aplicáveis ao tratamento de dados?
- Há procedimentos para apoiar a resposta a solicitações de titulares ou autoridades, quando pertinentes?
- Existem critérios para retenção, devolução e eliminação dos dados ao término do serviço?

### 7.9 Evidências e auditoria

- O fornecedor consegue apresentar evidências proporcionais aos requisitos acordados?
- Existem relatórios independentes, certificações ou avaliações relevantes para o serviço?
- O escopo e a validade dessas evidências podem ser verificados?
- Há mecanismos contratuais para avaliação, auditoria ou solicitação de informações, conforme o risco e os limites acordados?
- As limitações, exceções e pendências são documentadas?

**Orientação:** uma resposta afirmativa não comprova, por si só, a eficácia do controle. Sempre que necessário, a organização deve verificar documentos, evidências, relatórios, demonstrações ou outras fontes apropriadas.

## 8. Registro das respostas e evidências

Cada pergunta aplicável deve ter um registro rastreável.

| Campo | Descrição ou orientação |
|---|---|
| Identificador da pergunta | Código único da questão avaliada. |
| Domínio | Área de avaliação, como acessos, incidentes ou continuidade. |
| Pergunta | Questão submetida à avaliação. |
| Aplicabilidade | Aplicável, não aplicável ou pendente de análise. |
| Resposta do fornecedor | Resposta documentada recebida. |
| Avaliação interna | Análise da resposta e de sua adequação. |
| Evidência solicitada | Documento ou comprovação necessária. |
| Evidência recebida | Referência ao material recebido. |
| Validação da evidência | Validada, parcialmente validada, não validada ou pendente. |
| Lacuna identificada | Descrição objetiva da insuficiência ou divergência. |
| Risco associado | Referência ao risco identificado. |
| Ação requerida | Correção, esclarecimento, controle compensatório ou outra medida. |
| Responsável | Pessoa ou papel responsável pelo acompanhamento. |
| Prazo | Data acordada para resposta ou tratamento. |
| Situação | Aberta, em tratamento, concluída, aceita conforme alçada ou outra situação definida. |

As evidências devem ser armazenadas em local autorizado, com acesso controlado e prazo de retenção definido.

## 9. Avaliação de riscos do fornecedor

A avaliação deve considerar cenários de risco relacionados ao serviço, e não apenas a existência de políticas ou certificações.

Exemplos de cenários:

- Indisponibilidade prolongada de um serviço crítico.
- Acesso indevido a informações organizacionais.
- Comprometimento de credenciais administrativas.
- Exploração de vulnerabilidade em componente fornecido.
- Exposição de dados pessoais.
- Falha na execução de cópias de segurança ou na recuperação.
- Incidente em subcontratado com impacto sobre o serviço.
- Encerramento inesperado do fornecedor ou perda de capacidade operacional.
- Falha no cumprimento de requisitos legais ou contratuais.
- Impossibilidade de obter evidências necessárias para demonstrar conformidade.

Para cada cenário pertinente, registrar:

- Evento de risco.
- Ativo, processo ou informação afetada.
- Causas e vulnerabilidades relevantes.
- Consequências potenciais.
- Controles existentes e evidências.
- Probabilidade e impacto conforme a metodologia organizacional.
- Nível de risco inerente.
- Medidas adicionais necessárias.
- Responsável pelo tratamento.
- Risco residual e decisão de tratamento, quando aplicável.

A análise deve seguir a metodologia de gestão de riscos adotada no SGSI. Não se deve inventar pontuações ou declarar risco residual aceitável sem critérios e aprovação apropriados.

## 10. Critérios de decisão

A organização deve definir os critérios para aprovação e contratação considerando o risco e a criticidade do serviço.

Resultados possíveis:

- **Aprovado:** avaliação concluída, sem impedimentos identificados segundo os critérios estabelecidos.
- **Aprovado com condições:** existem pendências ou medidas adicionais formalmente aceitas, com responsáveis, prazos e acompanhamento.
- **Pendente:** faltam informações ou evidências necessárias para a decisão.
- **Reprovado:** os riscos ou as lacunas excedem os critérios de aceitação definidos.
- **Suspenso:** o relacionamento ou serviço está temporariamente interrompido por decisão autorizada.
- **Encerrado:** o relacionamento contratual foi finalizado, permanecendo aplicáveis as obrigações posteriores pertinentes.

A decisão deve ser registrada com justificativa, data, responsável e alçada de aprovação.

Uma certificação apresentada pelo fornecedor pode contribuir para a avaliação, mas não elimina a necessidade de verificar o escopo, a validade, as exclusões e a pertinência da certificação ao serviço contratado.

## 11. Requisitos contratuais e planos de ação

Quando aplicável, os requisitos de segurança devem ser formalizados no contrato, em anexos, em acordos de nível de serviço ou em documentos complementares autorizados.

Podem incluir:

- Requisitos de confidencialidade e uso autorizado.
- Controle de acesso e proteção de credenciais.
- Notificação e cooperação na resposta a incidentes.
- Requisitos de proteção e tratamento de dados.
- Gestão de vulnerabilidades e atualizações.
- Continuidade e recuperação de serviços.
- Uso e controle de subcontratados.
- Retenção, devolução e eliminação de informações.
- Disponibilização de evidências e relatórios.
- Direito de auditoria ou mecanismos alternativos de garantia.
- Comunicação de mudanças relevantes.
- Responsabilidades no encerramento do contrato.

As cláusulas devem ser definidas e aprovadas pelas áreas competentes, incluindo Jurídico, Compras, Segurança da Informação, Privacidade e área contratante, conforme a estrutura da organização.

As pendências identificadas devem gerar plano de ação quando necessário, contendo:

| Campo | Descrição ou orientação |
|---|---|
| Identificador da ação | Código único. |
| Lacuna ou risco relacionado | Referência ao achado ou risco. |
| Medida necessária | Ação esperada para reduzir ou tratar a exposição. |
| Responsável interno | Papel ou pessoa responsável pelo acompanhamento. |
| Responsável do fornecedor | Contato responsável pela execução, quando aplicável. |
| Prazo acordado | Data definida para conclusão. |
| Evidência de conclusão | Registro necessário para demonstrar a execução. |
| Validação | Resultado da verificação da ação. |
| Situação | Aberta, em andamento, concluída, vencida ou outra situação definida. |
| Aprovação de exceção | Referência à decisão formal, quando aplicável. |

A conclusão de uma ação deve ser confirmada por evidência apropriada, e não apenas pela declaração de que foi realizada.

## 12. Monitoramento contínuo

A avaliação inicial não substitui o acompanhamento durante o relacionamento com o fornecedor.

O monitoramento deve ser proporcional à criticidade e pode incluir:

- Revisão periódica de riscos e evidências.
- Acompanhamento de incidentes e indisponibilidades.
- Verificação de mudanças relevantes no serviço.
- Monitoramento de indicadores e níveis de serviço.
- Revisão de acessos concedidos a terceiros.
- Acompanhamento de planos de ação e exceções.
- Reavaliação de subcontratados relevantes.
- Revisão de certificações ou relatórios apresentados.
- Reavaliação em renovações contratuais ou mudanças de escopo.

A organização deve definir a periodicidade e os gatilhos de reavaliação. Fornecedores críticos podem exigir acompanhamento mais frequente, conforme os riscos identificados.

## 13. Encerramento do relacionamento

O encerramento deve considerar a revogação de acessos, a devolução ou eliminação de informações, a transferência de conhecimento, a continuidade operacional e as obrigações contratuais que permanecem vigentes.

Conforme aplicável, verificar:

- Revogação dos acessos físicos e lógicos.
- Desativação de credenciais, integrações e contas de serviço.
- Devolução de equipamentos e ativos organizacionais.
- Devolução, transferência ou eliminação de informações.
- Confirmação de descarte, quando exigida e disponível.
- Preservação de registros necessários para obrigações legais ou contratuais.
- Transferência de serviços e responsabilidades.
- Tratamento de riscos residuais e pendências.
- Registro da data e da aprovação do encerramento.

A eliminação de informações deve respeitar obrigações legais, regulatórias, contratuais e de preservação de evidências.

## 14. Indicadores possíveis

Os indicadores devem ter definição, fonte de dados, responsável, periodicidade e critérios de interpretação.

Exemplos:

- Percentual de fornecedores críticos avaliados dentro do prazo.
- Percentual de avaliações com evidências validadas.
- Quantidade de riscos altos ou críticos em aberto.
- Percentual de planos de ação concluídos no prazo.
- Quantidade de exceções de segurança vigentes.
- Percentual de contratos críticos com requisitos de segurança formalizados.
- Quantidade de reavaliações vencidas.
- Percentual de terceiros com acessos revisados conforme o cronograma.

Os resultados devem ser calculados a partir de dados verificáveis. Não devem ser apresentados valores fictícios como indicadores reais da organização.

## 15. Proteção dos registros

Os registros de avaliação podem conter informações contratuais, técnicas e de segurança sensíveis.

A organização deve definir:

- Perfis autorizados para consulta e alteração.
- Local de armazenamento e mecanismos de proteção.
- Regras de compartilhamento com áreas internas e fornecedores.
- Prazo de retenção e critérios de descarte.
- Rastreabilidade das decisões e alterações relevantes.
- Tratamento de dados pessoais eventualmente presentes nos registros.

A documentação deve observar os princípios de necessidade, confidencialidade e acesso autorizado.

## 16. Checklist de validação

- [ ] O fornecedor e o serviço foram identificados.
- [ ] A criticidade e o escopo da avaliação foram definidos.
- [ ] Os acessos e as informações tratados foram identificados.
- [ ] Os requisitos legais e contratuais pertinentes foram considerados.
- [ ] O questionário foi adaptado ao contexto do serviço.
- [ ] As respostas relevantes foram verificadas por evidências apropriadas.
- [ ] Os riscos e as lacunas foram registrados.
- [ ] A decisão de aprovação possui justificativa e responsável autorizado.
- [ ] Os requisitos contratuais necessários foram encaminhados para formalização.
- [ ] Os planos de ação possuem responsáveis e prazos.
- [ ] O monitoramento e os gatilhos de reavaliação foram definidos.
- [ ] O encerramento contempla acessos, informações e obrigações remanescentes.
- [ ] Os registros estão protegidos e sujeitos a retenção definida.

O checklist deve refletir verificações efetivamente realizadas. A existência deste documento não comprova que qualquer fornecedor tenha sido avaliado.

## 17. Limitações e adaptação

Este modelo não substitui a análise jurídica de contratos, a avaliação técnica de segurança, a análise de privacidade ou a metodologia de gestão de riscos da organização.

Os questionários, critérios de criticidade, exigências de evidência, decisões e periodicidades devem ser adaptados ao contexto e aprovados pelos responsáveis competentes.

A avaliação deve ser proporcional ao risco e evitar exigências genéricas que não sejam pertinentes ao serviço.

## 18. Histórico de revisão

| Versão | Data | Descrição | Responsável |
|---|---|---|---|
| 1.0 | A preencher | Criação do modelo de referência. | A definir |

---

**Projeto:** Guia Técnico de Implementação do SGSI — ISO/IEC 27001:2022  
**Autor:** José Eduardo Moura Cardozo  
**Tipo de documento:** Modelo de referência  
**Status:** Modelo conceitual para adaptação e validação organizacional
