# Matriz de Rastreabilidade entre Referências e Documentos do SGSI

## 1. Objetivo

Esta matriz relaciona as referências normativas, legais e técnicas utilizadas no Guia Técnico de Implementação do SGSI aos documentos e domínios em que sua contribuição é mais relevante.

A matriz facilita a localização das fontes, a revisão de impacto quando uma referência é atualizada e a identificação de documentos que precisam ser reavaliados. Ela registra relações de apoio metodológico; não declara equivalência entre normas, atendimento automático de requisitos ou conformidade de uma organização.

## 2. Critérios de leitura

- **Base de requisitos:** referência que estabelece requisitos diretamente aplicáveis ao SGSI.
- **Orientação principal:** referência que orienta o desenvolvimento de determinado processo ou artefato.
- **Apoio complementar:** referência que aprofunda um tema ou oferece práticas adicionais.
- **Aplicabilidade condicionada:** referência utilizada quando o contexto, o escopo, os serviços ou as operações da organização justificarem sua adoção.

A indicação de um documento na matriz não significa que todo o seu conteúdo seja derivado exclusivamente daquela referência. Um mesmo artefato pode combinar requisitos, orientações e decisões metodológicas.

## 3. Matriz de rastreabilidade

| Referência | Natureza e papel | Documentos/domínios relacionados | Tipo de relação |
|---|---|---|---|
| ISO/IEC 27001:2022 + Emenda 1:2024 | Requisitos do SGSI; base para avaliação de conformidade e certificação do SGSI. | Todos os domínios 01 a 17; especialmente Documento Mestre, contexto e escopo, liderança, riscos, SoA, tratamento, operação, monitoramento, auditoria e melhoria. | Base de requisitos |
| ISO/IEC 27002:2022 | Orientação para seleção, interpretação e implementação de controles. | 06 — SoA; 08 — Controles de Segurança; 09 — Políticas e Procedimentos; 10 — Pessoas e Conscientização; 11 — Operação do SGSI; modelos do domínio 16. | Orientação principal |
| ISO/IEC 27003:2020 | Orientação para implementação do SGSI. | 02 — Governança do Projeto; 03 — Contexto e Escopo; 04 — Liderança e Responsabilidades; 05 — Gestão de Riscos; 11 — Operação; 12 — Monitoramento; 14 — Melhoria. | Orientação principal |
| ISO/IEC 27005:2022 | Orientação para gestão de riscos de Segurança da Informação. | 05 — Gestão de Riscos; 06 — SoA; 07 — Plano de Tratamento; modelos de registro de riscos e tratamento no domínio 16. | Orientação principal |
| ISO 31000:2018 | Diretrizes gerais para gestão de riscos e integração com a governança. | 02 — Governança do Projeto; 03 — Contexto e Escopo; 05 — Gestão de Riscos; 14 — Análise Crítica e Melhoria. | Apoio complementar |
| ISO/IEC 27007:2021 | Orientação específica para auditoria de SGSI. | 13 — Auditoria Interna; 12 — Monitoramento e Indicadores; 14 — Análise Crítica e Melhoria; modelos de auditoria no domínio 16. | Orientação principal |
| ISO 19011:2026 | Diretrizes gerais para auditoria de sistemas de gestão. | 13 — Auditoria Interna; 12 — Monitoramento e Indicadores; 14 — Análise Crítica e Melhoria. | Apoio complementar |
| ISO/IEC 17021-1:2015 | Requisitos destinados a organismos de auditoria e certificação. | 15 — Certificação; 13 — Auditoria Interna, apenas para distinguir auditoria interna de certificação externa. | Referência contextual |
| ISO/IEC 27017:2026 | Orientação e controles específicos para serviços em nuvem. | 08 — Controles de Segurança; 09 — Políticas e Procedimentos; 11 — Operação do SGSI; modelo de avaliação de fornecedores e terceiros no domínio 16. | Aplicabilidade condicionada |
| ISO/IEC 27018:2025 | Orientação para proteção de dados pessoais em serviços de nuvem pública, conforme os papéis das partes. | 08 — Controles de Segurança; 09 — Políticas e Procedimentos; 11 — Operação; modelo de avaliação de fornecedores e terceiros no domínio 16. | Aplicabilidade condicionada |
| ISO/IEC 27701:2025 | Requisitos e orientação para sistema de gestão de informações de privacidade (PIMS). | 03 — Contexto e Escopo; 05 — Gestão de Riscos; 08 — Controles; 09 — Políticas; 11 — Operação; referências e glossário no domínio 17. | Aplicabilidade condicionada |
| CIS Critical Security Controls v8.1.2 | Salvaguardas práticas priorizadas para defesa cibernética. | 08 — Controles de Segurança; 09 — Políticas e Procedimentos; 11 — Operação; 12 — Monitoramento; modelos de ativos, acessos, vulnerabilidades, incidentes e fornecedores no domínio 16. | Apoio complementar |
| A Roadmap to the CIS Critical Security Controls (novembro de 2024) | Orientação para adoção progressiva e planejamento de uso dos CIS Controls. | 02 — Governança do Projeto; 08 — Controles de Segurança; 11 — Operação; 12 — Monitoramento e Indicadores. | Apoio complementar |
| Lei nº 13.709/2018 — LGPD | Legislação brasileira sobre tratamento de dados pessoais. | 03 — Contexto e Escopo; 05 — Gestão de Riscos; 08 — Controles; 09 — Políticas e Procedimentos; 11 — Operação; 16 — modelos de fornecedores e incidentes, quando aplicável. | Aplicabilidade condicionada |

## 4. Relação com os modelos e registros

Além dos documentos metodológicos, as referências podem orientar a adaptação dos modelos do domínio 16. A relação abaixo indica os principais pontos de consulta:

| Modelo | Referências de apoio mais relevantes |
|---|---|
| Registro de riscos | ISO/IEC 27001; ISO/IEC 27005; ISO 31000 |
| Plano de tratamento de riscos | ISO/IEC 27001; ISO/IEC 27005; ISO/IEC 27002 |
| Declaração de Aplicabilidade (SoA) | ISO/IEC 27001; ISO/IEC 27002 |
| Plano de auditoria interna | ISO/IEC 27001; ISO/IEC 27007; ISO 19011 |
| Registro de não conformidades e ações corretivas | ISO/IEC 27001; ISO 19011 como orientação de auditoria |
| Registro e plano de resposta a incidentes | ISO/IEC 27001; ISO/IEC 27002; CIS Controls; LGPD, quando aplicável |
| Plano de continuidade de negócios e testes de recuperação | ISO/IEC 27001; ISO/IEC 27002; CIS Controls, conforme os riscos |
| Registro de backup e restauração | ISO/IEC 27001; ISO/IEC 27002; CIS Controls |
| Gestão de acessos e revisão de permissões | ISO/IEC 27001; ISO/IEC 27002; CIS Controls |
| Gestão de mudanças | ISO/IEC 27001; ISO/IEC 27002 |
| Vulnerabilidades e gestão de correções | ISO/IEC 27001; ISO/IEC 27002; CIS Controls |
| Inventário e classificação de ativos | ISO/IEC 27001; ISO/IEC 27002; CIS Controls |
| Avaliação de fornecedores e terceiros | ISO/IEC 27001; ISO/IEC 27002; ISO/IEC 27017 e 27018, quando houver serviços em nuvem e dados pessoais |
| Treinamentos e conscientização | ISO/IEC 27001; ISO/IEC 27002; ISO/IEC 27003 |

## 5. Uso da matriz na manutenção do projeto

Quando uma norma, legislação ou framework for atualizado:

1. Identificar a referência e a edição afetada.
2. Localizar nesta matriz os domínios e artefatos relacionados.
3. Consultar os documentos indicados e avaliar o impacto real da atualização.
4. Verificar se modelos, procedimentos, termos, exemplos ou orientações precisam ser revistos.
5. Atualizar as referências cruzadas e o histórico de revisão dos documentos alterados.
6. Registrar a decisão, inclusive quando a análise concluir que não há impacto documental.

A matriz deve ser atualizada sempre que novos documentos forem incluídos, removidos ou alterados de forma que modifique a relação com as referências.

## 6. Limites da rastreabilidade

Esta matriz é um instrumento de navegação e controle documental do projeto autoral. Não substitui a leitura das publicações aplicáveis, a análise de requisitos, a avaliação de riscos ou a validação técnica no contexto de uma organização.

A presença de uma referência associada a um documento não comprova que o documento atenda integralmente à publicação. Da mesma forma, a presença de um modelo não comprova que o processo correspondente tenha sido implementado ou executado.

---

**Projeto:** Guia Técnico de Implementação do SGSI — ISO/IEC 27001:2022  
**Autor:** José Eduardo Moura Cardozo  
**Documento:** Matriz de Rastreabilidade entre Referências e Documentos do SGSI  
**Status:** Documento-base publicado — sujeito a revisão
