# Modelo de Registro de Riscos de Segurança da Informação

## 1. Objetivo

Este documento apresenta um modelo de referência para registrar, avaliar, tratar e acompanhar riscos de segurança da informação no contexto de um Sistema de Gestão de Segurança da Informação (SGSI).

O registro de riscos deve manter rastreabilidade entre os ativos ou processos relevantes, os eventos de risco, as consequências potenciais, os critérios de avaliação, as decisões de tratamento e as evidências de acompanhamento.

Este arquivo é um modelo reutilizável. Seu conteúdo não representa uma avaliação de riscos executada em uma organização real.

## 2. Referências e integração com o SGSI

O modelo apoia a aplicação dos processos de gestão de riscos relacionados à ISO/IEC 27001:2022, especialmente:

- Cláusula 6.1.2 — Avaliação de riscos de segurança da informação;
- Cláusula 6.1.3 — Tratamento de riscos de segurança da informação;
- Cláusula 8.2 — Avaliação de riscos de segurança da informação;
- Cláusula 8.3 — Tratamento de riscos de segurança da informação.

O modelo deve ser adaptado à metodologia de gestão de riscos definida e aprovada pela organização.

A ISO/IEC 27001:2022 não determina uma única escala universal de probabilidade e impacto. Os critérios, escalas, regras de cálculo e critérios de aceitação devem ser definidos pela organização de maneira consistente com seus objetivos e contexto.

## 3. Orientações de preenchimento

Cada risco deve possuir um identificador único que permita relacioná-lo aos documentos e registros pertinentes.

O registro deve diferenciar:

- **Risco inerente:** risco avaliado antes de considerar os efeitos dos controles existentes, conforme a metodologia adotada.
- **Controles existentes:** medidas que já estão implementadas e cuja existência e operação podem ser demonstradas.
- **Risco residual:** risco remanescente após considerar os controles existentes e seu efeito demonstrável.
- **Tratamento planejado:** ações aprovadas ou propostas para modificar o risco.
- **Risco residual previsto:** resultado esperado após a implementação das ações planejadas, ainda sujeito a verificação.
- **Risco residual reavaliado:** resultado obtido após a implementação e avaliação dos controles e ações pertinentes.

A organização deve definir os conceitos utilizados em sua metodologia e aplicá-los consistentemente. Uma ação planejada não deve ser registrada como controle implementado sem evidências apropriadas.

## 4. Estrutura do registro de riscos

A tabela abaixo apresenta os campos recomendados. Para facilitar a leitura, o registro pode ser mantido em planilha, sistema de gestão de riscos ou outro repositório controlado.

| Campo | Orientação de preenchimento |
|---|---|
| ID do risco | Identificador único, por exemplo, `RSI-001` |
| Data de identificação | Data em que o risco foi registrado |
| Responsável pelo risco | Pessoa ou função responsável por acompanhar o risco |
| Processo ou ativo | Processo, serviço, sistema ou ativo de informação relacionado |
| Descrição do risco | Descrição objetiva do evento de risco e de suas possíveis consequências |
| Fonte ou causa | Condição, vulnerabilidade, ameaça ou circunstância relevante |
| Consequência potencial | Efeitos possíveis sobre confidencialidade, integridade, disponibilidade ou outros objetivos pertinentes |
| Requisitos relacionados | Requisitos legais, regulatórios, contratuais ou internos pertinentes |
| Controles existentes | Controles implementados e evidências disponíveis |
| Probabilidade inerente | Classificação conforme a escala aprovada |
| Impacto inerente | Classificação conforme a escala aprovada |
| Nível de risco inerente | Resultado conforme a metodologia definida |
| Critério de aceitação | Critério utilizado para determinar se o risco pode ser aceito |
| Opção de tratamento | Modificar, evitar, compartilhar ou reter o risco, conforme a metodologia adotada |
| Ações de tratamento | Medidas planejadas para modificar o risco |
| Responsável pela ação | Pessoa ou função responsável pela execução |
| Prazo | Data prevista para conclusão |
| Situação da ação | Situação real de execução |
| Evidência de implementação | Referência aos registros que demonstram a execução |
| Probabilidade residual | Classificação após considerar os controles aplicáveis |
| Impacto residual | Classificação após considerar os controles aplicáveis |
| Nível de risco residual | Resultado conforme a metodologia definida |
| Decisão sobre o risco | Decisão documentada de tratamento ou aceitação |
| Autoridade aprovadora | Pessoa ou função com autoridade para aprovar a decisão |
| Data da decisão | Data em que a decisão foi formalizada |
| Próxima revisão | Data prevista para reavaliação |
| Histórico de alterações | Registro de mudanças relevantes na avaliação ou no tratamento |

Nem todos os campos precisam aparecer em uma única tabela. A organização pode distribuir as informações em registros relacionados, desde que mantenha a rastreabilidade e a informação documentada necessária.

## 5. Modelo de escalas de avaliação

As escalas a seguir são **exemplos ilustrativos**, não escalas obrigatórias estabelecidas pela ISO/IEC 27001:2022.

### 5.1 Probabilidade

| Nível | Classificação ilustrativa | Descrição orientativa |
|---|---|---|
| 1 | Rara | Evento considerado pouco provável nas condições avaliadas |
| 2 | Improvável | Evento possível, mas com baixa expectativa de ocorrência |
| 3 | Possível | Evento com possibilidade plausível de ocorrência |
| 4 | Provável | Evento com expectativa elevada de ocorrência |
| 5 | Quase certa | Evento esperado com frequência elevada nas condições avaliadas |

A organização deve definir critérios observáveis para cada nível, considerando, conforme pertinente, histórico de incidentes, exposição, ameaças, vulnerabilidades, efetividade dos controles e condições operacionais.

### 5.2 Impacto

| Nível | Classificação ilustrativa | Descrição orientativa |
|---|---|---|
| 1 | Insignificante | Consequências limitadas e de baixa relevância para a organização |
| 2 | Menor | Consequências restritas, com impacto operacional reduzido |
| 3 | Moderado | Consequências que exigem resposta e recursos relevantes |
| 4 | Maior | Consequências graves para processos, informações ou obrigações |
| 5 | Crítico | Consequências potencialmente severas para objetivos essenciais da organização |

A avaliação deve considerar as dimensões de impacto pertinentes, que podem incluir interrupção operacional, exposição de informações, integridade dos dados, consequências financeiras, obrigações legais e danos à reputação.

A organização deve documentar como os impactos de diferentes dimensões serão consolidados em uma classificação única, quando esse método for adotado.

### 5.3 Exemplo de cálculo

Uma metodologia pode utilizar a multiplicação da probabilidade pelo impacto:

**Nível de risco = Probabilidade × Impacto**

Nesse exemplo, os valores variam de 1 a 25.

A multiplicação é apenas uma alternativa metodológica. A organização deve verificar se o método escolhido representa adequadamente seus riscos e estabelecer os limites de classificação e aceitação.

Não se deve adotar automaticamente a escala ou os limites deste exemplo sem aprovação e adequação ao contexto organizacional.

## 6. Exemplo hipotético de registro

O exemplo a seguir demonstra como descrever um risco. Os dados são fictícios e não representam avaliação, controle ou incidente de uma organização real.

| Campo | Exemplo ilustrativo |
|---|---|
| ID do risco | RSI-EX-001 |
| Processo ou ativo | Serviço corporativo de armazenamento de arquivos |
| Descrição do risco | A indisponibilidade do serviço pode impedir o acesso a documentos necessários às operações |
| Fonte ou causa | Falha técnica, erro operacional ou indisponibilidade do fornecedor |
| Consequência potencial | Interrupção de atividades e atraso em processos dependentes dos documentos |
| Controles existentes | A verificar na organização; nenhum controle real é presumido neste exemplo |
| Probabilidade inerente | Não avaliada |
| Impacto inerente | Não avaliado |
| Nível de risco inerente | Não calculado |
| Opção de tratamento | A definir após avaliação |
| Ações de tratamento | A definir conforme os resultados da avaliação |
| Responsável pelo risco | A designar |
| Risco residual | Não avaliado |
| Decisão de aceitação | Não realizada |

Este exemplo propositalmente não atribui notas ou declara controles existentes sem evidências. A avaliação real deve ser realizada por pessoas competentes, conforme os critérios aprovados pela organização.

## 7. Opções de tratamento

A metodologia deve definir como as opções de tratamento serão avaliadas e registradas.

### 7.1 Modificar o risco

Implementar ou aprimorar medidas para reduzir a probabilidade, o impacto ou ambos.

### 7.2 Evitar o risco

Interromper ou não iniciar a atividade que origina o risco, quando essa decisão for apropriada e viável.

### 7.3 Compartilhar o risco

Distribuir determinadas consequências ou responsabilidades por meio de mecanismos apropriados, como contratos ou seguros, sem presumir que a responsabilidade organizacional ou o risco de segurança da informação desapareça.

### 7.4 Reter o risco

Manter o risco mediante decisão documentada e de acordo com os critérios e as autoridades de aceitação definidos pela organização.

A opção de tratamento deve ser coerente com a avaliação, os requisitos aplicáveis e os objetivos do SGSI.

## 8. Relação com o plano de tratamento de riscos

O registro de riscos identifica e acompanha os riscos. O plano de tratamento detalha as ações selecionadas para tratá-los.

Quando forem utilizados documentos separados, cada ação deve manter uma referência ao risco correspondente.

Exemplo de relacionamento:

| Identificador | Finalidade |
|---|---|
| `RSI-001` | Identifica o risco |
| `PTR-001` | Identifica uma ação no plano de tratamento |
| `EV-001` | Identifica ou referencia uma evidência relacionada |

Esses identificadores são exemplos e podem ser substituídos pelo padrão de codificação aprovado pela organização.

## 9. Revisão e atualização dos riscos

Os riscos devem ser reavaliados conforme a metodologia aprovada e sempre que mudanças relevantes justificarem uma revisão.

Podem motivar uma reavaliação:

- Mudanças nos processos ou serviços;
- Alterações nos ativos de informação;
- Incidentes relevantes;
- Mudanças nas ameaças ou vulnerabilidades;
- Alterações nos controles;
- Mudanças legais, regulatórias ou contratuais;
- Resultados de auditorias;
- Alterações no contexto organizacional;
- Mudanças significativas em fornecedores;
- Verificação de que um tratamento não alcançou o resultado esperado.

A organização deve definir responsáveis, critérios e periodicidade de revisão. Uma revisão não deve ser registrada como realizada antes de sua execução.

## 10. Evidências e controle documental

O registro deve ser controlado como informação documentada do SGSI.

Recomenda-se estabelecer:

- Identificação e versão;
- Responsável pela manutenção;
- Regras de acesso;
- Histórico de alterações;
- Referências às evidências;
- Critérios de retenção;
- Proteção contra alterações não autorizadas;
- Mecanismos de aprovação pertinentes.

Informações sobre riscos podem revelar fragilidades, ativos críticos ou dependências operacionais. O acesso deve ser limitado conforme a classificação da informação e as necessidades legítimas de trabalho.

## 11. Critérios de qualidade do registro

Antes de considerar um registro suficientemente documentado, recomenda-se verificar se:

- O risco está descrito de forma clara;
- As causas e consequências estão identificadas;
- Os critérios de avaliação são conhecidos;
- As classificações possuem justificativa;
- Os controles existentes estão sustentados por evidências;
- O tratamento está relacionado ao risco identificado;
- As ações possuem responsáveis e prazos;
- As decisões de aceitação possuem autoridade apropriada;
- Os riscos residuais foram avaliados conforme a metodologia;
- A próxima revisão está definida;
- As alterações são rastreáveis.

A conclusão desta verificação não equivale a uma declaração de conformidade do SGSI.

## 12. Limitações de aplicação

Este modelo deve ser adaptado à metodologia, à estrutura de governança e ao contexto da organização.

As escalas, os exemplos e os campos sugeridos não substituem a definição formal dos critérios de avaliação, aceitação e tratamento de riscos.

O preenchimento de um registro não comprova, isoladamente, que os riscos foram tratados eficazmente ou que os requisitos da ISO/IEC 27001:2022 foram atendidos.

## 13. Histórico de alterações

| Versão | Descrição | Situação |
|---|---|---|
| 1.0 | Criação do modelo de referência para registro de riscos de segurança da informação | Modelo para adaptação |

A situação indicada descreve o estado documental deste arquivo no projeto. Não representa aprovação, aplicação ou validação em uma organização real.
