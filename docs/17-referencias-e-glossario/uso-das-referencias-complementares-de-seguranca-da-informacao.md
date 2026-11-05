# Uso das Referências Complementares de Segurança da Informação

## 1. Objetivo

Neste documento organizei como as referências complementares podem apoiar a aplicação do Guia Técnico de Implementação do SGSI. A intenção é ampliar a utilidade do projeto sem misturar requisitos normativos, orientações técnicas, modelos de implementação e estruturas de priorização.

A ISO/IEC 27001:2022 continua sendo a referência central de requisitos do SGSI. As demais fontes apoiam atividades específicas, mas não substituem a avaliação de riscos, as decisões da organização nem os requisitos da norma principal.

Este documento é metodológico. Não representa uma avaliação de conformidade nem determina antecipadamente quais controles devem ser adotados por uma organização.

## 2. Hierarquia e finalidade das referências

| Referência | Papel no projeto | Como utilizar |
|---|---|---|
| ISO/IEC 27001:2022 + Emenda 1:2024 | Requisitos do SGSI | Determinar os requisitos aplicáveis, estruturar o sistema de gestão e orientar a avaliação de conformidade. |
| ISO/IEC 27002:2022 | Orientação para controles | Apoiar a interpretação, o desenho, a implementação e a avaliação dos controles necessários. |
| ISO/IEC 27003:2020 | Orientação para implementação do SGSI | Apoiar o planejamento e a organização do trabalho relacionado às cláusulas da ISO/IEC 27001. |
| ISO/IEC 27005:2022 | Orientação para gestão de riscos de SI | Apoiar o estabelecimento do contexto, critérios, avaliação, tratamento, comunicação e monitoramento dos riscos. |
| ISO/IEC 27007:2021 | Orientação para auditoria de SGSI | Complementar o programa e os métodos de auditoria interna, considerando as particularidades do SGSI. |
| ISO/IEC 27017:2015 / ABNT NBR ISO/IEC 27017:2016 | Orientação para controles em serviços de nuvem | Apoiar a análise de responsabilidades e controles em relações entre clientes e provedores de serviços em nuvem. Confirmar a edição vigente antes de aplicação formal. |
| ISO/IEC 27018 | Orientação para proteção de dados pessoais em nuvens públicas | Considerar quando o cenário envolver provedores de nuvem pública que processem dados pessoais. Confirmar a edição oficial e o papel da organização no tratamento. |
| ISO/IEC 27701 | Gestão da privacidade da informação | Considerar quando houver necessidade de estruturar um sistema de gestão de privacidade articulado à segurança da informação. Confirmar a edição publicada e vigente antes de utilizá-la como referência normativa. |
| CIS Controls v8.1.2 | Salvaguardas técnicas priorizadas | Apoiar a seleção e a priorização de medidas práticas de defesa cibernética, sem substituir a determinação de controles da ISO/IEC 27001. |
| CIS Controls Roadmap (novembro de 2024) | Orientação de adoção dos CIS Controls | Apoiar a compreensão dos grupos de implementação, recursos de avaliação e planejamento progressivo. |

A natureza de cada fonte precisa permanecer clara. Uma norma de requisitos, uma norma de orientação, um guia técnico e um material de curso não possuem a mesma função.

## 3. Como relacionar ISO/IEC 27001, ISO/IEC 27002 e ISO/IEC 27005

A relação entre essas referências deve seguir uma sequência lógica:

1. A ISO/IEC 27001 estabelece os requisitos do sistema de gestão e do processo de tratamento de riscos.
2. A ISO/IEC 27005 oferece orientação para estruturar a gestão dos riscos de segurança da informação.
3. A ISO/IEC 27002 oferece orientação para compreender e implementar controles.
4. A organização determina quais controles são necessários a partir dos riscos, obrigações e demais requisitos aplicáveis.
5. Os controles necessários são comparados com o Anexo A da ISO/IEC 27001 e registrados na SoA, incluindo as justificativas exigidas.
6. A implementação e a operação dos controles são acompanhadas por evidências, monitoramento e avaliação.

Um mapeamento entre controles de referências diferentes pode ajudar a localizar temas relacionados. Entretanto, correspondência temática não significa equivalência, cobertura integral ou atendimento automático de requisitos.

## 4. Atributos dos controles e organização do acervo

A ISO/IEC 27002:2022 apresenta atributos que permitem visualizar os controles por diferentes perspectivas. No acervo de estudo dos 93 controles do Anexo A, essas perspectivas estão organizadas em blocos como:

- identificação e tema do controle;
- tipo de controle;
- propriedades de segurança da informação;
- conceitos de segurança cibernética;
- capacidades operacionais;
- domínios de segurança;
- entendimento, propósito e orientação de implementação.

Essa organização permite consultar um controle não apenas pelo seu tema, mas também pela função que desempenha no tratamento de riscos.

Os atributos devem ser utilizados como recursos de classificação e análise. Não representam uma pontuação de eficácia, uma ordem obrigatória de implantação ou uma declaração de que o controle atende isoladamente a determinado risco.

O acervo também apresenta uma matriz de atributos, visões consolidadas, dependências e um modelo de SoA. A lógica dessas ferramentas pode orientar a organização dos artefatos do projeto, mas os dados e exemplos do material de curso não devem ser tratados como decisões de uma organização real.

## 5. Priorização complementar com CIS Controls v8.1

Os CIS Controls v8.1 organizam as recomendações em 18 controles e salvaguardas associadas. A documentação v8.1.2 disponibilizada no acervo apresenta salvaguardas, classes de ativos e funções de segurança.

Os grupos de implementação são:

- **IG1:** conjunto inicial de higiene cibernética essencial, voltado a organizações com recursos e especialização limitados.
- **IG2:** amplia o conjunto anterior e considera ambientes com múltiplos departamentos, perfis de risco e maior complexidade operacional.
- **IG3:** inclui os grupos anteriores e acrescenta salvaguardas para contextos com dados sensíveis e maior capacidade técnica de segurança.

Os grupos são referências de priorização. A classificação de uma organização deve considerar seu perfil, sua exposição, os ativos, os dados, as obrigações, os recursos e a tolerância ao risco. Não se deve atribuir um grupo apenas pelo porte da organização.

No contexto deste guia, os CIS Controls podem apoiar:

- a identificação de medidas técnicas que contribuam para tratar riscos;
- a organização de iniciativas de segurança por prioridade;
- a avaliação de lacunas em ativos, software, dados, identidades, redes e serviços;
- a discussão de requisitos mínimos e evolução progressiva;
- a definição de métricas e evidências para salvaguardas selecionadas.

A seleção das salvaguardas deve ser justificada no contexto da organização. O uso dos CIS Controls não substitui a avaliação de riscos nem a SoA da ISO/IEC 27001.

### 5.1. Cuidados com mapeamentos

Um mapeamento entre CIS Controls e controles do Anexo A pode ser útil como índice de navegação, mas deve ser tratado como correspondência indicativa.

Antes de utilizar um mapeamento, é necessário verificar:

- o objetivo e o escopo de cada controle;
- os ativos e processos abrangidos;
- as condições de aplicação;
- as responsabilidades envolvidas;
- a cobertura efetiva das medidas;
- as evidências disponíveis;
- as lacunas que permanecem sem tratamento.

Não se deve concluir que uma salvaguarda CIS atende integralmente a um controle ISO apenas porque os títulos ou assuntos são semelhantes.

### 5.2. Licença e utilização do conteúdo CIS

O material CIS v8.1.2 informa licença Creative Commons Atribuição–NãoComercial–SemDerivações 4.0 Internacional (CC BY-NC-ND 4.0). Por esse motivo, este projeto utiliza os CIS Controls como referência e descreve sua aplicação de forma autoral, sem republicar ou distribuir versões modificadas das descrições e salvaguardas do CIS.

Para consulta e atualização, deve-se utilizar a publicação oficial do CIS: https://www.cisecurity.org/controls/v8-1/

## 6. Serviços em nuvem e responsabilidades compartilhadas

A ISO/IEC 27017 aborda controles e orientações específicos para serviços em nuvem. Seu uso exige que a organização compreenda a relação entre cliente, provedor e eventuais parceiros do serviço.

A análise deve considerar, conforme o serviço contratado:

- responsabilidades de segurança atribuídas ao cliente;
- responsabilidades assumidas pelo provedor;
- atividades compartilhadas;
- responsabilidades de parceiros e subcontratados;
- limites de acesso e administração;
- proteção e segregação de ambientes;
- gestão de incidentes;
- continuidade e recuperação;
- localização, transferência e tratamento de informações;
- evidências e informações disponibilizadas pelo provedor.

Não se deve presumir que a contratação de um serviço em nuvem transfira ao provedor todas as responsabilidades de segurança. A distribuição depende do modelo de serviço, da arquitetura, do contrato e das atividades efetivamente executadas por cada parte.

A organização deve registrar as responsabilidades relevantes, avaliar os riscos associados ao fornecedor e acompanhar as condições do serviço durante sua utilização.

O PDF de ISO/IEC 27017 anexado corresponde à ABNT NBR ISO/IEC 27017:2016. O acervo Excel apresenta uma aba com quatro controles adicionais identificados como CLD da edição 2026. Como os arquivos representam edições diferentes, não combine esses conteúdos sem confirmar a publicação oficial, a edição e o status de cada controle.

## 7. Proteção de dados pessoais e gestão da privacidade

A ISO/IEC 27018 anexada está identificada como edição 2025 e trata da proteção de dados pessoais em nuvens públicas quando o provedor atua como processador. O próprio arquivo informa que foi disponibilizado para estudo e que a tradução automática pode conter inadequações.

A utilização dessa referência depende da natureza do serviço, dos papéis exercidos pelas partes e das operações de tratamento de dados pessoais. Ela não deve ser aplicada indiscriminadamente a qualquer organização ou serviço em nuvem.

Quando houver tratamento de dados pessoais, a análise deve considerar, conforme aplicável:

- finalidade e instruções de tratamento;
- responsabilidades do controlador e do operador;
- obrigações contratuais;
- atendimento aos direitos dos titulares;
- retenção, devolução e eliminação de dados;
- compartilhamento e transferência;
- incidentes envolvendo dados pessoais;
- medidas de segurança e evidências;
- requisitos legais e regulatórios pertinentes.

A ISO/IEC 27701 pode complementar essa análise com uma abordagem de sistema de gestão de privacidade. O arquivo anexado, porém, é um projeto ABNT de consulta de 2019 e não deve ser citado como se fosse uma edição normativa publicada e vigente. A edição aplicável precisa ser confirmada no catálogo oficial antes de qualquer uso normativo.

A LGPD e os regulamentos aplicáveis devem ser avaliados conforme as operações de tratamento e os papéis efetivamente exercidos. A adoção de controles de segurança não comprova, isoladamente, conformidade com a legislação de proteção de dados.

## 8. Auditoria de Sistemas de Gestão da Segurança da Informação

A ISO/IEC 27007:2021 complementa as orientações gerais de auditoria ao tratar de particularidades de auditorias de SGSI.

Sua aplicação pode apoiar:

- definição dos objetivos do programa de auditoria;
- análise dos riscos do próprio programa;
- determinação de escopo e critérios;
- seleção de métodos e equipes;
- competência dos auditores;
- análise de evidências técnicas e documentais;
- avaliação de controles e processos de segurança;
- comunicação dos resultados e acompanhamento das constatações.

A ISO/IEC 27007 deve ser lida em conjunto com os requisitos de auditoria interna da ISO/IEC 27001 e com as diretrizes gerais de auditoria aplicáveis. Não substitui os requisitos da norma principal nem transforma a auditoria interna em auditoria de certificação.

O arquivo anexado é a ABNT NBR ISO/IEC 27007:2021. A referência à ISO 19011 deve considerar a edição vigente e eventuais transições aplicáveis.

## 9. Critérios para incorporar referências complementares ao projeto

Antes de incluir uma nova referência ou alterar um documento, aplico os seguintes critérios:

1. Confirmar o título, a edição, a natureza e o status da publicação.
2. Identificar se a fonte estabelece requisitos, fornece orientação ou apresenta exemplos.
3. Determinar quais documentos do projeto são afetados.
4. Verificar se a orientação já está contemplada em outro artefato.
5. Evitar duplicação de conteúdo e divergência de terminologia.
6. Registrar limitações de edição, tradução, consulta pública ou licença.
7. Distinguir requisito normativo, recomendação técnica e decisão metodológica do autor.
8. Atualizar os links internos e o índice documental.
9. Preservar a rastreabilidade das alterações.
10. Não declarar conformidade ou eficácia sem evidências apropriadas.

## 10. Limites desta documentação

As referências complementares ampliam a análise técnica do guia, mas não substituem as publicações oficiais nem dispensam a avaliação do contexto organizacional.

Os materiais anexados incluem normas publicadas, projeto de norma em consulta, documentos de estudo, traduções e materiais didáticos. Cada fonte deve ser utilizada conforme sua natureza e seus limites.

Os exemplos e as relações descritas neste documento são orientações metodológicas. A aplicação em uma organização real exige análise, seleção, aprovação, implementação e avaliação pelos responsáveis competentes.

## 11. Referências utilizadas

- ISO/IEC 27001:2022, incluindo Emenda 1:2024.
- ISO/IEC 27002:2022.
- ABNT NBR ISO/IEC 27003:2020.
- ISO/IEC 27005:2022 — considerada por meio do Projeto de Revisão ABNT de abril de 2023 anexado, identificado como documento sem valor normativo.
- ABNT NBR ISO/IEC 27007:2021.
- ABNT NBR ISO/IEC 27017:2016.
- ISO/IEC 27018:2025 — cópia de estudo com tradução automática.
- Projeto ABNT NBR ISO/IEC 27701 de outubro de 2019 — documento de consulta sem valor normativo.
- CIS Critical Security Controls v8.1.2, março de 2025.
- A Roadmap to the CIS Critical Security Controls, novembro de 2024.
- Ebook ISO/IEC 27001 Lead Implementer, edição 2026, utilizado como material didático complementar.

---

**Projeto:** Guia Técnico de Implementação do SGSI — ISO/IEC 27001:2022  
**Autor:** José Eduardo Moura Cardozo  
**Documento:** Uso das Referências Complementares de Segurança da Informação  
**Status:** Em desenvolvimento  
