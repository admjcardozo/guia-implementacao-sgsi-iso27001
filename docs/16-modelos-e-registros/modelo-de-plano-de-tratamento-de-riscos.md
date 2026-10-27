# Modelo de Plano de Tratamento de Riscos de Segurança da Informação

## 1. Objetivo

Este documento apresenta um modelo de referência para planejar, executar, acompanhar e avaliar ações de tratamento de riscos de segurança da informação no contexto de um Sistema de Gestão de Segurança da Informação (SGSI).

O plano de tratamento transforma as decisões de tratamento de riscos em ações organizadas, com responsáveis, prazos, recursos, critérios de conclusão e evidências de acompanhamento.

Este arquivo é um modelo reutilizável. Seu conteúdo não representa um plano aprovado ou executado em uma organização real.

## 2. Referências normativas

A principal referência é a ISO/IEC 27001:2022, especialmente:

- **Cláusula 6.1.3 — Tratamento de riscos de segurança da informação:** estabelece requisitos para definir e aplicar o processo de tratamento de riscos.
- **Cláusula 8.3 — Tratamento de riscos de segurança da informação:** trata da implementação do plano de tratamento e da retenção de informação documentada sobre os resultados.
- **Cláusula 7.5 — Informação documentada:** relaciona-se ao controle da documentação pertinente ao SGSI.

O plano deve estar alinhado à metodologia de gestão de riscos aprovada pela organização e manter rastreabilidade com o registro de riscos e a Declaração de Aplicabilidade.

## 3. Relação com o registro de riscos

O registro de riscos identifica e avalia os riscos. O plano de tratamento documenta as ações escolhidas para modificar esses riscos.

Cada ação deve possuir um identificador único e uma referência ao risco que pretende tratar.

Exemplo de identificação:

- `RSI-001`: identificador de um risco no registro de riscos;
- `PTR-001`: identificador de uma ação no plano de tratamento;
- `EV-001`: identificador ou referência de uma evidência associada.

Os identificadores são ilustrativos e podem ser substituídos pelo padrão de codificação adotado pela organização.

Um risco pode exigir várias ações de tratamento. Da mesma forma, uma ação pode contribuir para o tratamento de mais de um risco, desde que essa relação seja documentada e justificável.

## 4. Estrutura do plano de tratamento

A tabela abaixo apresenta os campos recomendados para organizar as ações.

| Campo | Orientação de preenchimento |
|---|---|
| ID da ação | Identificador único da ação de tratamento |
| ID do risco | Referência ao risco relacionado |
| Descrição do risco | Resumo do risco que será tratado |
| Decisão de tratamento | Opção selecionada e justificativa |
| Ação planejada | Descrição objetiva do que será realizado |
| Resultado esperado | Resultado que a ação pretende alcançar |
| Controle relacionado | Controle ou conjunto de controles relacionado, quando aplicável |
| Responsável pela ação | Pessoa ou função responsável pela execução |
| Responsável pela aprovação | Autoridade responsável pela aprovação, quando necessária |
| Prioridade | Prioridade conforme os critérios organizacionais |
| Data de início | Data planejada para início |
| Prazo | Data prevista para conclusão |
| Recursos necessários | Recursos humanos, financeiros, técnicos ou operacionais |
| Dependências | Atividades ou decisões necessárias para execução |
| Critério de conclusão | Condição objetiva para considerar a ação concluída |
| Evidência esperada | Registro que deverá demonstrar a execução |
| Situação | Estado real da ação |
| Data de conclusão | Data efetiva de conclusão, quando aplicável |
| Resultado obtido | Resultado observado após a execução |
| Reavaliação do risco | Referência à avaliação atualizada, quando aplicável |
| Verificação de eficácia | Método e resultado da avaliação de eficácia |
| Decisão sobre o risco residual | Decisão documentada após a reavaliação |
| Histórico de alterações | Registro das mudanças relevantes |

A organização pode distribuir esses campos em mais de um documento ou sistema, desde que mantenha a rastreabilidade necessária.

## 5. Opções de tratamento

A escolha da opção de tratamento deve ser consistente com a avaliação de riscos, os critérios de aceitação e os requisitos aplicáveis.

### 5.1 Modificar o risco

Adotar medidas para reduzir a probabilidade, o impacto ou ambos.

Exemplos ilustrativos:

- Implementar autenticação multifator;
- Aprimorar o monitoramento;
- Restringir privilégios;
- Melhorar procedimentos de recuperação;
- Implementar medidas de proteção física;
- Aprimorar controles de fornecedores.

A adequação de cada medida deve ser avaliada em relação ao risco específico.

### 5.2 Evitar o risco

Interromper ou não iniciar a atividade que origina o risco, quando essa alternativa for adequada e viável.

A decisão deve considerar as consequências operacionais, contratuais e estratégicas.

### 5.3 Compartilhar o risco

Distribuir determinadas consequências ou responsabilidades por meio de mecanismos apropriados, como contratos ou seguros.

O compartilhamento não elimina automaticamente o risco de segurança da informação nem as responsabilidades que permanecem com a organização.

### 5.4 Reter o risco

Manter o risco mediante decisão documentada, observando os critérios de aceitação e as autoridades definidas pela organização.

A aceitação deve considerar o risco residual, os requisitos aplicáveis e a justificativa para a decisão.

## 6. Priorização das ações

A organização deve estabelecer critérios para priorizar as ações de tratamento.

Podem ser considerados:

- Nível de risco;
- Consequências potenciais;
- Obrigações legais, regulatórias e contratuais;
- Criticidade do processo ou ativo;
- Exposição a ameaças;
- Dependências técnicas;
- Prazo para atendimento de requisitos;
- Recursos necessários;
- Complexidade de implementação;
- Benefício esperado;
- Risco residual previsto.

A prioridade deve ser justificada quando houver decisões que contrariem a ordem sugerida pela avaliação de riscos.

Uma ação classificada como prioritária não deve ser considerada executada ou eficaz apenas por ter recebido essa classificação.

## 7. Modelo de plano de tratamento

A tabela a seguir é um modelo para preenchimento. Os campos não preenchidos não representam ações aprovadas ou em andamento.

| ID da ação | ID do risco | Ação planejada | Responsável | Prazo | Prioridade | Situação |
|---|---|---|---|---|---|---|
| PTR-001 | RSI-001 | Preencher após avaliação e aprovação do tratamento | A designar | A definir | A definir | Não iniciado |
| PTR-002 | RSI-002 | Preencher após avaliação e aprovação do tratamento | A designar | A definir | A definir | Não iniciado |

Os identificadores `RSI-001` e `RSI-002` são exemplos de estrutura de identificação. Não indicam que existam riscos reais cadastrados com esses códigos.

A organização deve substituir os exemplos pelos riscos e pelas ações efetivamente identificados e aprovados.

## 8. Exemplo hipotético de ação de tratamento

O exemplo abaixo demonstra como estruturar uma ação. Ele não representa um risco real nem uma implementação executada.

| Campo | Exemplo ilustrativo |
|---|---|
| ID da ação | PTR-EX-001 |
| ID do risco | RSI-EX-001 |
| Descrição do risco | Indisponibilidade de um serviço corporativo de armazenamento de arquivos |
| Ação planejada | Avaliar e, se aprovado, implementar medidas de recuperação e testar o procedimento correspondente |
| Resultado esperado | Melhorar a capacidade de recuperação do serviço conforme os objetivos definidos |
| Responsável | A designar |
| Prazo | A definir |
| Prioridade | A definir após avaliação |
| Critério de conclusão | Medidas aprovadas e implementadas, com teste executado e resultado documentado |
| Evidência esperada | Procedimento aprovado, registros de implementação e resultados do teste |
| Situação | Não iniciado |
| Verificação de eficácia | A definir com base nos objetivos de recuperação e nos resultados obtidos |

A execução deve ser comprovada por evidências apropriadas. A elaboração de um plano ou procedimento não demonstra que a medida foi implementada ou que o resultado esperado foi alcançado.

## 9. Critérios de conclusão das ações

Cada ação deve possuir um critério de conclusão claro e verificável.

Exemplos de critérios:

- Procedimento aprovado e publicado;
- Configuração implementada e validada;
- Revisão de acessos realizada e registrada;
- Teste executado com resultado documentado;
- Treinamento realizado com registros pertinentes;
- Contrato revisado e formalizado;
- Controle implementado e evidenciado.

Os critérios devem ser proporcionais à natureza da ação e ao risco tratado.

A conclusão administrativa de uma tarefa deve ser diferenciada da avaliação de sua eficácia.

## 10. Evidências de implementação

As evidências devem demonstrar que a ação foi executada conforme o planejamento aprovado.

Podem incluir:

- Registros de configuração;
- Resultados de testes;
- Procedimentos aprovados;
- Registros de treinamento;
- Atas de aprovação;
- Evidências de revisão de acessos;
- Registros de monitoramento;
- Relatórios técnicos;
- Registros de implantação;
- Evidências de validação.

As evidências devem possuir identificação, origem e contexto suficientes para permitir sua análise posterior.

Informações confidenciais, dados pessoais e detalhes técnicos sensíveis devem ser protegidos. O plano deve referenciar as evidências sem necessariamente reproduzir seu conteúdo integral.

## 11. Reavaliação do risco residual

Após a implementação das ações pertinentes, o risco deve ser reavaliado conforme a metodologia aprovada.

A reavaliação deve considerar:

- Se a ação foi efetivamente implementada;
- Se o controle funciona conforme esperado;
- Se houve alteração na probabilidade;
- Se houve alteração no impacto;
- Se surgiram novos riscos;
- Se o risco residual atende aos critérios de aceitação;
- Se são necessárias ações adicionais.

A classificação do risco residual não deve ser reduzida automaticamente apenas porque uma ação foi concluída.

Quando o risco permanecer acima dos critérios de aceitação, a organização deve avaliar opções adicionais de tratamento ou uma decisão de aceitação devidamente autorizada, conforme os requisitos aplicáveis.

## 12. Verificação da eficácia

A verificação da eficácia avalia se as ações produziram os resultados pretendidos.

O método deve ser definido considerando a natureza do risco e da medida implementada.

Exemplos:

- Testes de recuperação;
- Revisões de acessos;
- Testes de controles;
- Análise de indicadores;
- Inspeção de registros;
- Reexecução de procedimentos;
- Avaliação de incidentes posteriores;
- Verificação independente, quando pertinente.

A evidência de execução não é necessariamente evidência de eficácia. Uma configuração pode ter sido aplicada sem produzir a proteção esperada; um treinamento pode ter ocorrido sem demonstrar que seus objetivos foram alcançados.

Os resultados da verificação devem ser documentados e utilizados na atualização do registro de riscos.

## 13. Acompanhamento e governança

O acompanhamento deve permitir identificar ações atrasadas, impedimentos, dependências e riscos que permaneçam sem tratamento adequado.

Recomenda-se estabelecer:

- Responsável pela consolidação do plano;
- Frequência de acompanhamento;
- Critérios para escalonamento de atrasos;
- Processo de aprovação de alterações;
- Regras para replanejamento;
- Forma de comunicação à direção;
- Integração com a análise crítica do SGSI.

Alterações de escopo, prazo, prioridade ou abordagem de tratamento devem ser justificadas e registradas conforme a governança definida.

A aprovação de uma alteração não deve apagar o histórico das decisões anteriores.

## 14. Relação com a Declaração de Aplicabilidade

Quando uma ação estiver relacionada à implementação ou à alteração de controles de segurança, deve existir rastreabilidade com a Declaração de Aplicabilidade, quando pertinente.

Essa relação pode incluir:

- Identificação do controle;
- Justificativa de aplicabilidade;
- Situação de implementação declarada;
- Evidência relacionada;
- Risco tratado;
- Ação correspondente.

A implementação de um controle não deve ser declarada apenas porque uma ação foi incluída no plano. A situação deve refletir a condição real e as evidências disponíveis.

## 15. Critérios de qualidade do plano

Antes de considerar o plano adequadamente estruturado, recomenda-se verificar se:

- Cada ação está relacionada a um risco identificado;
- A decisão de tratamento está justificada;
- Os responsáveis estão definidos;
- Os prazos são viáveis e documentados;
- Os recursos e as dependências foram avaliados;
- Os critérios de conclusão são verificáveis;
- As evidências esperadas estão identificadas;
- A situação das ações reflete a realidade;
- A reavaliação do risco está prevista;
- A eficácia será avaliada quando pertinente;
- As decisões sobre risco residual possuem rastreabilidade;
- As alterações são registradas.

Esta lista é uma ferramenta metodológica e não constitui declaração de conformidade do SGSI.

## 16. Limitações de aplicação

Este modelo deve ser adaptado à metodologia de gestão de riscos, à governança e ao contexto da organização.

Os exemplos não representam riscos avaliados, ações aprovadas, controles implementados ou resultados obtidos em uma organização real.

A existência de um plano não comprova que o tratamento tenha sido executado nem que os riscos estejam dentro dos critérios de aceitação.

## 17. Histórico de alterações

| Versão | Descrição | Situação |
|---|---|---|
| 1.0 | Criação do modelo de referência para plano de tratamento de riscos | Modelo para adaptação |

A situação indicada descreve o estado documental deste arquivo no projeto e não comprova aprovação, implementação ou validação em uma organização real.
