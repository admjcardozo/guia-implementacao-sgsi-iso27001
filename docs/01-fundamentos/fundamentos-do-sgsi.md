# Fundamentos do Sistema de Gestão de Segurança da Informação

**Projeto:** Guia Técnico de Implementação do SGSI — ISO/IEC 27001:2022  
**Autor:** José Eduardo Moura Cardozo  
**Categoria:** Fundamentos e referências normativas  
**Situação:** Em desenvolvimento  
**Versão:** 1.0

---

## 1. Finalidade

Este documento apresenta os fundamentos conceituais e normativos necessários para compreender um Sistema de Gestão de Segurança da Informação (SGSI) e sua relação com a ISO/IEC 27001:2022.

Seu objetivo é estabelecer uma base comum para os documentos técnicos posteriores, esclarecendo os conceitos centrais, os objetivos do sistema de gestão, a relação entre riscos e controles e as responsabilidades envolvidas na implementação.

O documento também delimita a diferença entre os requisitos normativos, as orientações técnicas, as decisões organizacionais e as evidências necessárias para demonstrar a execução e a eficácia dos processos.

## 2. O que é um SGSI

Um Sistema de Gestão de Segurança da Informação é um conjunto integrado de políticas, processos, responsabilidades, recursos, controles e mecanismos de avaliação destinado a gerenciar os riscos de segurança da informação de uma organização.

O SGSI não se limita à implantação de ferramentas tecnológicas ou à elaboração de políticas. Ele estabelece uma estrutura de gestão que permite definir objetivos, compreender o contexto, avaliar riscos, selecionar medidas de tratamento, acompanhar resultados e promover melhorias.

Sua implementação deve considerar as características da organização, incluindo:

- Natureza das atividades e dos serviços prestados.
- Informações utilizadas, armazenadas, processadas ou transmitidas.
- Processos de negócio e serviços críticos.
- Infraestrutura tecnológica e ambientes operacionais.
- Pessoas, competências e responsabilidades.
- Fornecedores e dependências externas.
- Obrigações legais, regulatórias e contratuais.
- Ameaças e vulnerabilidades relevantes.
- Consequências potenciais de incidentes de segurança.

O SGSI deve ser adequado ao contexto e ao escopo definidos. Não existe uma estrutura documental única que seja automaticamente apropriada para todas as organizações.

## 3. Objetivos da segurança da informação

A segurança da informação busca preservar características que permitam utilizar as informações de maneira confiável e apropriada.

### 3.1. Confidencialidade

Propriedade segundo a qual a informação não é disponibilizada nem divulgada a indivíduos, entidades ou processos não autorizados.

Exemplos de medidas relacionadas:

- Controle de acesso baseado em necessidade.
- Autenticação apropriada.
- Criptografia quando necessária.
- Classificação e tratamento de informações.
- Proteção de dados pessoais e informações confidenciais.

### 3.2. Integridade

Propriedade de exatidão e completude da informação, incluindo a proteção contra alterações indevidas.

Exemplos de medidas relacionadas:

- Controle de alterações.
- Validação de dados.
- Registros de auditoria.
- Proteção contra modificações não autorizadas.
- Procedimentos de conciliação e verificação.

### 3.3. Disponibilidade

Propriedade de estar acessível e utilizável quando necessário por uma entidade autorizada.

Exemplos de medidas relacionadas:

- Backup e restauração.
- Redundância e resiliência.
- Gestão de capacidade.
- Monitoramento de serviços.
- Planejamento de continuidade.
- Testes de recuperação.

A seleção das medidas deve considerar os riscos identificados e as necessidades operacionais da organização.

### 3.4. Outras propriedades relevantes

Dependendo do contexto, também podem ser importantes:

- **Autenticidade:** confiança de que uma entidade ou informação corresponde à identidade alegada.
- **Rastreabilidade:** capacidade de acompanhar ações, eventos ou alterações relevantes.
- **Responsabilização:** possibilidade de atribuir ações e decisões a responsáveis identificáveis, conforme os registros disponíveis.
- **Confiabilidade:** capacidade de produzir resultados consistentes e adequados à finalidade pretendida.

Essas propriedades complementam a análise de segurança quando pertinentes. Não devem ser tratadas como substitutas dos requisitos normativos aplicáveis.

## 4. Segurança da informação como sistema de gestão

A segurança da informação depende da interação entre pessoas, processos, tecnologia, governança e ambiente organizacional.

Uma ferramenta pode reduzir determinado risco, mas não substitui necessariamente a definição de responsabilidades, a manutenção de processos, o treinamento dos usuários ou a avaliação de resultados.

Da mesma forma, uma política documentada não demonstra, isoladamente, que os comportamentos e os processos correspondentes estejam sendo praticados.

A abordagem de sistema de gestão permite organizar esses elementos de forma integrada, com objetivos, responsabilidades, critérios de avaliação e mecanismos de melhoria.

### 4.1. Componentes de um SGSI

Conforme o contexto e o escopo, um SGSI poderá incluir:

- Diretrizes e objetivos de segurança da informação.
- Definição do contexto e do escopo.
- Governança e responsabilidades.
- Metodologia de gestão de riscos.
- Plano de tratamento de riscos.
- Declaração de Aplicabilidade.
- Políticas e procedimentos.
- Controles organizacionais, humanos, físicos e tecnológicos.
- Processos operacionais.
- Competência e conscientização.
- Monitoramento e medição.
- Auditoria interna.
- Análise crítica pela direção.
- Tratamento de não conformidades.
- Ações corretivas e melhoria contínua.

A composição efetiva dependerá dos requisitos aplicáveis e das decisões fundamentadas da organização.

## 5. ISO/IEC 27001:2022

A ISO/IEC 27001:2022 estabelece requisitos para sistemas de gestão de segurança da informação.

Sua aplicação envolve a definição do contexto e do escopo, a liderança, o planejamento, o suporte, a operação, a avaliação de desempenho e a melhoria.

### 5.1. Estrutura das cláusulas

A organização do SGSI deverá considerar as cláusulas 4 a 10 da norma.

| Cláusula | Tema | Finalidade geral |
|---|---|---|
| 4 | Contexto da organização | Compreender o contexto, as partes interessadas e o escopo do SGSI. |
| 5 | Liderança | Estabelecer responsabilidades, direção e comprometimento da liderança. |
| 6 | Planejamento | Tratar riscos e oportunidades e estabelecer objetivos pertinentes. |
| 7 | Apoio | Prover recursos, competência, conscientização, comunicação e informação documentada. |
| 8 | Operação | Planejar e controlar os processos operacionais, incluindo a avaliação e o tratamento de riscos. |
| 9 | Avaliação de desempenho | Monitorar, medir, analisar, avaliar e realizar auditorias internas e análise crítica pela direção. |
| 10 | Melhoria | Tratar não conformidades, ações corretivas e melhoria contínua. |

A tabela apresenta uma visão resumida dos temas. A identificação das obrigações específicas deverá ser realizada mediante consulta à edição oficial aplicável da norma.

### 5.2. Requisitos obrigatórios e métodos de implementação

A norma estabelece requisitos que precisam ser atendidos quando a organização declara conformidade com a ISO/IEC 27001:2022.

Entretanto, diferentes organizações podem utilizar métodos, ferramentas e estruturas documentais distintos para atender a um mesmo requisito, desde que a abordagem adotada seja adequada e permita demonstrar o atendimento aos requisitos aplicáveis.

Por exemplo, a norma exige que a organização estabeleça critérios para avaliação de riscos de segurança da informação. A escolha de uma escala numérica, uma matriz qualitativa ou outra forma de análise depende da metodologia adotada, desde que os critérios sejam adequados aos requisitos normativos e ao contexto.

O guia deverá distinguir sempre:

- O que a norma exige.
- Quais métodos podem ser utilizados para atender ao requisito.
- Quais decisões precisam ser tomadas pela organização.
- Quais registros e evidências são necessários para demonstrar a execução.

## 6. ISO/IEC 27002:2022

A ISO/IEC 27002:2022 fornece orientação para os controles de segurança da informação.

Ela complementa a aplicação da ISO/IEC 27001 ao apresentar orientações sobre controles que podem ser considerados conforme as necessidades da organização.

A ISO/IEC 27002 não substitui os requisitos do sistema de gestão estabelecidos pela ISO/IEC 27001.

### 6.1. Categorias de controles

O conjunto de controles da ISO/IEC 27002:2022 é organizado em quatro temas:

- **Organizacionais:** relacionados à governança, aos processos e às responsabilidades.
- **Pessoas:** relacionados aos aspectos humanos da segurança da informação.
- **Físicos:** relacionados à proteção física de instalações, equipamentos e informações.
- **Tecnológicos:** relacionados às medidas técnicas e aos ambientes de tecnologia.

Essa classificação auxilia a organização dos controles, mas não elimina a necessidade de avaliar riscos, responsabilidades, dependências e requisitos aplicáveis.

### 6.2. Seleção e aplicação de controles

A seleção dos controles deverá ser fundamentada no processo de gestão de riscos, nas necessidades da organização e nos requisitos legais, regulatórios e contratuais pertinentes.

O Anexo A da ISO/IEC 27001:2022 contém controles de referência que deverão ser considerados no processo previsto pela norma.

A organização deverá determinar os controles necessários, considerando o tratamento dos riscos e outras obrigações aplicáveis, e documentar as decisões pertinentes na Declaração de Aplicabilidade.

A ausência de um controle de referência na Declaração de Aplicabilidade não deve ser presumida nem justificada sem análise. As decisões deverão observar os requisitos normativos aplicáveis e ser devidamente fundamentadas.

## 7. Gestão de riscos de segurança da informação

A gestão de riscos constitui um componente central do SGSI.

Seu objetivo é identificar e avaliar riscos relevantes, apoiar decisões de tratamento e estabelecer critérios para acompanhar a exposição residual da organização.

O processo deverá considerar as informações, os processos, os ativos, as dependências e os cenários que possam afetar a segurança da informação.

### 7.1. Etapas gerais

Uma abordagem de referência poderá contemplar:

1. Estabelecimento dos critérios de risco.
2. Identificação dos riscos.
3. Análise dos riscos.
4. Avaliação dos riscos em relação aos critérios definidos.
5. Seleção das opções de tratamento.
6. Identificação dos controles necessários.
7. Planejamento das ações de tratamento.
8. Avaliação dos riscos residuais.
9. Registro e aprovação das decisões pertinentes.
10. Monitoramento e revisão dos riscos.

Essa lista apresenta uma estrutura metodológica geral. A abordagem efetiva deverá atender aos requisitos da ISO/IEC 27001:2022 e ser adequada ao contexto organizacional.

### 7.2. Risco inerente e risco residual

O risco inerente é utilizado em determinadas metodologias para representar o risco antes da consideração de medidas de tratamento específicas.

O risco residual representa o risco que permanece após a aplicação ou consideração das medidas de tratamento.

Esses termos deverão ser definidos de maneira consistente na metodologia adotada. A organização não deverá atribuir valores ou classificações sem critérios estabelecidos.

A existência de um plano de tratamento não significa que o risco já tenha sido reduzido. A avaliação do risco residual deverá considerar a situação efetiva das medidas implementadas e as evidências disponíveis.

## 8. Declaração de Aplicabilidade

A Declaração de Aplicabilidade, também conhecida como Statement of Applicability (SoA), é um artefato relevante do SGSI.

Ela registra os controles necessários, as justificativas pertinentes para sua inclusão, a situação de implementação e as justificativas para a exclusão de controles de referência, conforme os requisitos da ISO/IEC 27001:2022.

### 8.1. Relação com a gestão de riscos

A Declaração de Aplicabilidade deverá manter coerência com as decisões de tratamento de riscos e com os controles necessários à organização.

Quando pertinente, deverá permitir relacionar:

- Riscos identificados.
- Decisões de tratamento.
- Controles necessários.
- Justificativas de inclusão.
- Situação de implementação.
- Justificativas para exclusão de controles de referência.
- Procedimentos e registros relacionados.
- Evidências de implementação e eficácia.

A estrutura exata do modelo poderá variar, desde que contemple os requisitos aplicáveis.

### 8.2. Situação de implementação

A situação de um controle deverá refletir a condição efetiva identificada pela organização.

O guia poderá propor classificações operacionais, como planejado, em implementação, implementado ou parcialmente implementado, desde que sejam claramente definidas e não confundidas com categorias normativas obrigatórias.

A classificação deverá ser sustentada por informações verificáveis. Um controle descrito em uma política não deve ser automaticamente classificado como implementado se sua execução ainda não foi estabelecida.

## 9. Informação documentada e evidências

A informação documentada apoia a operação, a rastreabilidade e a demonstração do funcionamento do SGSI.

Sua finalidade não é apenas armazenar arquivos, mas assegurar que as informações necessárias estejam disponíveis, protegidas e controladas de forma adequada.

### 9.1. Tipos de documentação

Conforme os requisitos e as necessidades organizacionais, poderão existir:

- Políticas.
- Procedimentos.
- Planos.
- Metodologias.
- Inventários.
- Matrizes de avaliação.
- Registros operacionais.
- Relatórios.
- Resultados de testes.
- Evidências de monitoramento.
- Atas e decisões.
- Registros de auditoria.
- Evidências de ações corretivas.

A necessidade de cada documento deverá ser avaliada conforme os requisitos aplicáveis e as necessidades de operação e controle.

### 9.2. Documento, registro e evidência

Para fins didáticos, o guia utilizará as seguintes distinções:

- **Documento orientador:** define diretrizes, critérios ou instruções.
- **Registro:** documenta uma atividade executada, uma decisão ou um resultado.
- **Evidência:** informação utilizada para sustentar uma conclusão sobre execução, atendimento a critérios ou eficácia.

Um mesmo artefato poderá desempenhar mais de uma função, dependendo de seu conteúdo e de sua utilização. Essas categorias são convenções explicativas do guia e não substituem as definições normativas aplicáveis.

A força de uma evidência depende de sua pertinência, confiabilidade, integridade e adequação à conclusão pretendida.

## 10. Ciclo de melhoria contínua

O SGSI deverá ser gerenciado como um sistema sujeito a avaliação e melhoria contínuas.

O ciclo Plan-Do-Check-Act (PDCA) pode ser utilizado como recurso didático para explicar essa dinâmica:

- **Plan — Planejar:** compreender o contexto, estabelecer objetivos, avaliar riscos e definir ações.
- **Do — Executar:** implementar e operar os processos e controles planejados.
- **Check — Verificar:** monitorar resultados, avaliar desempenho e realizar auditorias.
- **Act — Agir:** tratar não conformidades, corrigir problemas e promover melhorias.

O PDCA é uma representação metodológica útil, mas não deverá ser apresentado como substituto da estrutura ou dos requisitos específicos da ISO/IEC 27001:2022.

### 10.1. Avaliação e melhoria

A melhoria deverá considerar resultados de monitoramento, auditorias internas, análise crítica pela direção, incidentes, mudanças no contexto, não conformidades e outras informações pertinentes.

As ações deverão ser proporcionais às questões identificadas e acompanhadas para verificar se produziram os resultados esperados.

## 11. Papéis e responsabilidades

A implementação e a manutenção do SGSI exigem responsabilidades definidas e coordenação entre as áreas pertinentes.

A estrutura de governança deverá considerar, conforme o contexto:

- Alta direção.
- Responsáveis pela gestão do SGSI.
- Gestores de processos.
- Responsáveis pelos riscos.
- Responsáveis pelos controles.
- Equipes de tecnologia e segurança da informação.
- Recursos humanos.
- Jurídico e privacidade, quando aplicável.
- Compras e gestão de fornecedores.
- Auditoria interna.
- Usuários e demais colaboradores.

A lista é ilustrativa. As responsabilidades reais deverão ser definidas de acordo com a estrutura e as necessidades da organização.

Atribuir uma responsabilidade não significa transferir automaticamente toda a responsabilidade gerencial de segurança da informação para uma única área. O SGSI depende do envolvimento das funções pertinentes e do comprometimento da liderança.

## 12. Erros conceituais a evitar

Durante o desenvolvimento e a aplicação do guia, deverão ser evitadas as seguintes interpretações:

1. Considerar que instalar ferramentas de segurança equivale a implementar um SGSI.
2. Tratar a elaboração de políticas como comprovação suficiente de execução.
3. Presumir que todos os controles de referência são obrigatórios para qualquer organização.
4. Escolher controles sem considerar os riscos e os requisitos aplicáveis.
5. Confundir avaliação de riscos com inventário de ativos.
6. Considerar que um plano aprovado comprova que as ações foram executadas.
7. Tratar uma Declaração de Aplicabilidade preenchida como prova isolada de eficácia.
8. Confundir auditoria interna com auditoria externa de certificação.
9. Declarar conformidade sem avaliação adequada dos requisitos.
10. Presumir que a certificação está garantida porque existe documentação.
11. Utilizar classificações e escalas de risco sem critérios definidos.
12. Apresentar exemplos hipotéticos como registros de uma organização real.

## 13. Como utilizar este documento no projeto

Este documento constitui a base conceitual para os demais módulos do repositório.

Ele deverá ser consultado durante a elaboração de documentos relacionados a:

- Contexto e escopo.
- Liderança e responsabilidades.
- Gestão de riscos.
- Declaração de Aplicabilidade.
- Plano de tratamento de riscos.
- Controles de segurança.
- Informação documentada.
- Monitoramento e indicadores.
- Auditoria interna.
- Análise crítica e melhoria.
- Preparação para certificação.

Quando um documento posterior detalhar um assunto específico, deverá apresentar as referências pertinentes e evitar reproduzir desnecessariamente todo o conteúdo deste documento.

Alterações nos conceitos fundamentais deverão ser avaliadas quanto aos impactos nos documentos relacionados.

## 14. Referências técnicas

- ISO/IEC 27001:2022 — *Information security, cybersecurity and privacy protection — Information security management systems — Requirements*.
- ISO/IEC 27002:2022 — *Information security, cybersecurity and privacy protection — Information security controls*.
- ISO/IEC 27005 — *Information security, cybersecurity and privacy protection — Guidance on managing information security risks*, considerando a edição aplicável.
- ISO 31000 — *Risk management — Guidelines*, considerando a edição aplicável.
- ISO 19011 — *Guidelines for auditing management systems*, considerando a edição aplicável.
- Lei nº 13.709/2018 — Lei Geral de Proteção de Dados Pessoais (LGPD), quando aplicável.

As referências deverão ser verificadas antes de sua utilização em uma implementação real, considerando edições, emendas e requisitos adicionais pertinentes.

## 15. Identificação do projeto

**Projeto:** Guia Técnico de Implementação do SGSI — ISO/IEC 27001:2022  
**Autor:** José Eduardo Moura Cardozo  
**Natureza:** Autoral, conceitual, educacional e profissional  
**Situação:** Em desenvolvimento

---

*Este documento fornece fundamentos para o desenvolvimento do guia. Não substitui a consulta às normas oficiais nem representa comprovação de implementação ou conformidade de uma organização real.*
