# Índice da Documentação Técnica do SGSI

## 1. Finalidade

Este diretório reúne a documentação técnica do projeto autoral **Guia Técnico de Implementação do SGSI — ISO/IEC 27001:2022**, de autoria de José Eduardo Moura Cardozo.

O objetivo é oferecer uma referência estruturada para profissionais que precisam compreender, planejar, implementar, operar, avaliar e melhorar um Sistema de Gestão de Segurança da Informação (SGSI).

A documentação reúne fundamentos, metodologias, orientações de implementação, referências técnicas e modelos reutilizáveis. Os materiais devem ser adaptados ao contexto, aos riscos, às obrigações e às necessidades de cada organização.

**Importante:** a conclusão de um documento neste repositório significa que o conteúdo foi publicado no projeto. Não comprova a implementação de um SGSI em uma organização real, a eficácia dos controles ou a obtenção de certificação.

## 2. Como utilizar a documentação

Recomenda-se utilizar os documentos de forma integrada, considerando as dependências entre processos e a sequência de implementação do SGSI.

A estrutura contempla:

- Fundamentos e requisitos aplicáveis.
- Governança, contexto organizacional e escopo.
- Liderança, responsabilidades e autoridades.
- Gestão e tratamento de riscos.
- Declaração de Aplicabilidade (SoA).
- Controles, políticas e procedimentos de segurança.
- Gestão de pessoas, competências e conscientização.
- Planejamento e controle operacional.
- Monitoramento, indicadores e avaliação de desempenho.
- Auditoria interna, análise crítica e melhoria contínua.
- Preparação para auditorias externas e certificação.
- Modelos de documentos, formulários e registros.
- Referências técnicas, normativas e glossário.

A documentação deve ser utilizada como apoio à análise e à implementação. A existência de um documento não demonstra, isoladamente, que o requisito correspondente foi implementado ou que um controle funciona eficazmente.

## 3. Estrutura documental

A tabela apresenta a organização do repositório e a situação dos documentos-base.

| Diretório | Finalidade | Situação documental |
|---|---|---|
| `01-fundamentos/` | Fundamentos e conceitos do SGSI. | Documento-base publicado |
| `02-governanca-do-projeto/` | Documento mestre, planejamento e governança. | Documento-base publicado |
| `03-contexto-e-escopo/` | Contexto, partes interessadas, escopo e política de segurança. | Documentos-base publicados |
| `04-lideranca-e-responsabilidades/` | Papéis, responsabilidades e autoridades do SGSI. | Documento-base publicado |
| `05-gestao-de-riscos/` | Metodologia de gestão de riscos de Segurança da Informação. | Documento-base publicado |
| `06-declaracao-de-aplicabilidade/` | Declaração de Aplicabilidade e justificativas pertinentes. | Documento-base publicado |
| `07-plano-de-tratamento/` | Planejamento e tratamento de riscos. | Documento-base publicado |
| `08-controles-de-seguranca/` | Estrutura de gestão dos controles de segurança. | Documento-base publicado |
| `09-politicas-e-procedimentos/` | Estrutura de políticas e procedimentos. | Documento-base publicado |
| `10-pessoas-e-conscientizacao/` | Gestão de pessoas e conscientização. | Documento-base publicado |
| `11-operacao-do-sgsi/` | Planejamento e controle operacional. | Documento-base publicado |
| `12-monitoramento-e-indicadores/` | Monitoramento, medição, análise e avaliação. | Documento-base publicado |
| `13-auditoria-interna/` | Metodologia de auditoria interna. | Documento-base publicado |
| `14-analise-critica-e-melhoria/` | Análise crítica pela direção e melhoria contínua. | Documento-base publicado |
| `15-certificacao/` | Orientações para preparação e processo de certificação. | Documento-base publicado |
| `16-modelos-e-registros/` | Modelos reutilizáveis para apoiar os processos do SGSI. | Biblioteca de modelos publicada; sujeita a evolução |
| `17-referencias-e-glossario/` | Referências técnicas, normativas e glossário. | Documentos-base publicados |

A indicação de documento-base publicado significa que existe conteúdo orientador no repositório. Não significa que todos os procedimentos, registros, controles ou evidências necessários para implementar um SGSI estejam completos.

## 4. Documento mestre

O documento mestre organiza a abordagem de implementação, as fases de trabalho, as dependências entre os entregáveis e os critérios de governança e rastreabilidade.

Consulte:

- [Documento Mestre de Implementação do SGSI](02-governanca-do-projeto/documento-mestre-implementacao-sgsi.md)

Ele deve ser utilizado como referência para manter a coerência entre os documentos, as metodologias e os modelos desenvolvidos.

## 5. Modelos e registros

O diretório `16-modelos-e-registros/` reúne modelos destinados à adaptação e à utilização pelas organizações.

Os modelos são instrumentos de apoio. Sua aplicação em uma organização exige preenchimento, análise, aprovação e manutenção conforme as responsabilidades e os processos estabelecidos.

### 5.1. Gestão de riscos e aplicabilidade

- [Modelo de Registro de Riscos](16-modelos-e-registros/modelo-de-registro-de-riscos.md)
- [Modelo de Plano de Tratamento de Riscos](16-modelos-e-registros/modelo-de-plano-de-tratamento-de-riscos.md)
- [Modelo de Declaração de Aplicabilidade (SoA)](16-modelos-e-registros/modelo-de-declaracao-de-aplicabilidade-soa.md)

### 5.2. Auditoria, governança e melhoria

- [Modelo de Plano de Auditoria Interna do SGSI](16-modelos-e-registros/modelo-de-plano-de-auditoria-interna-do-sgsi.md)
- [Modelo de Ata de Análise Crítica pela Direção](16-modelos-e-registros/modelo-de-ata-de-analise-critica-pela-direcao.md)
- [Modelo de Registro de Não Conformidades e Ações Corretivas](16-modelos-e-registros/modelo-de-registro-de-nao-conformidades-e-acoes-corretivas.md)

### 5.3. Incidentes, continuidade e recuperação

- [Modelo de Registro de Incidentes de Segurança da Informação](16-modelos-e-registros/modelo-de-registro-de-incidentes-de-seguranca-da-informacao.md)
- [Modelo de Plano de Resposta a Incidentes](16-modelos-e-registros/modelo-de-plano-de-resposta-a-incidentes.md)
- [Modelo de Plano de Continuidade de Negócios](16-modelos-e-registros/modelo-de-plano-de-continuidade-de-negocios.md)
- [Modelo de Registro de Testes de Recuperação e Continuidade](16-modelos-e-registros/modelo-de-registro-de-testes-de-recuperacao-e-continuidade.md)
- [Modelo de Registro de Backup e Restauração](16-modelos-e-registros/modelo-de-registro-de-backup-e-restauracao.md)

### 5.4. Operação e proteção dos ativos

- [Modelo de Registro de Gestão de Acessos e Revisão de Permissões](16-modelos-e-registros/modelo-de-registro-de-gestao-de-acessos-e-revisao-de-permissoes.md)
- [Modelo de Registro de Gestão de Mudanças](16-modelos-e-registros/modelo-de-registro-de-gestao-de-mudancas.md)
- [Modelo de Registro de Vulnerabilidades e Gestão de Correções](16-modelos-e-registros/modelo-de-registro-de-vulnerabilidades-e-gestao-de-correcoes.md)

### 5.5. Ativos, fornecedores e conscientização

- [Modelo de Inventário e Classificação de Ativos](16-modelos-e-registros/modelo-de-inventario-e-classificacao-de-ativos.md)
- [Modelo de Avaliação de Fornecedores e Terceiros](16-modelos-e-registros/modelo-de-avaliacao-de-fornecedores-e-terceiros.md)
- [Modelo de Registro de Treinamentos e Conscientização](16-modelos-e-registros/modelo-de-registro-de-treinamentos-e-conscientizacao.md)

### 5.6. Outros modelos da biblioteca

- [Modelo de Registro de Gestão de Acessos e Revisão de Permissões](16-modelos-e-registros/modelo-de-registro-de-gestao-de-acessos-e-revisao-de-permissoes.md)
- [Modelo de Registro de Gestão de Mudanças](16-modelos-e-registros/modelo-de-registro-de-gestao-de-mudancas.md)
- [Modelo de Registro de Vulnerabilidades e Gestão de Correções](16-modelos-e-registros/modelo-de-registro-de-vulnerabilidades-e-gestao-de-correcoes.md)

A biblioteca deve ser ampliada e revisada conforme a identificação de lacunas documentais, novas necessidades e resultados da revisão técnica.

## 6. Referências técnicas, normativas e glossário

O diretório `17-referencias-e-glossario/` reúne documentos de apoio à terminologia e às fontes utilizadas no projeto.

### 6.1. Referências técnicas e normativas

Consulte [Referências Técnicas e Normativas do SGSI](17-referencias-e-glossario/referencias-tecnicas-e-normativas.md).

O documento apresenta as principais referências utilizadas no guia, suas finalidades, fontes oficiais e critérios de atualização.

### 6.2. Glossário

Consulte [Glossário de Segurança da Informação e SGSI](17-referencias-e-glossario/glossario-de-seguranca-da-informacao.md).

O glossário padroniza conceitos relacionados a SGSI, gestão de riscos, controles, documentação, operação, auditoria e certificação. Também diferencia termos frequentemente confundidos, como ameaça e vulnerabilidade, evento e incidente, documento e registro, correção e ação corretiva.

### 6.3. Referências principais

Entre as referências utilizadas no projeto estão:

- ISO/IEC 27001:2022 — requisitos para Sistemas de Gestão de Segurança da Informação.
- ISO/IEC 27002:2022 — orientações para controles de Segurança da Informação.
- ISO/IEC 27005 — orientações para gestão de riscos de Segurança da Informação.
- ISO 31000 — diretrizes gerais para gestão de riscos.
- ISO 19011 — diretrizes para auditoria de sistemas de gestão.
- ISO/IEC 17021-1 — requisitos para organismos que auditam e certificam sistemas de gestão.
- Lei nº 13.709/2018 — Lei Geral de Proteção de Dados Pessoais (LGPD), quando aplicável.

A edição vigente, a aplicabilidade e os requisitos específicos devem ser confirmados nas fontes oficiais antes da utilização. O documento de referências deve ser consultado para informações complementares e critérios de revisão.

## 7. Rastreabilidade e consistência

A documentação deve manter coerência entre:

- Requisitos aplicáveis e objetivos do SGSI.
- Contexto, escopo e partes interessadas.
- Riscos identificados, critérios de avaliação e decisões de tratamento.
- Controles selecionados e justificativas registradas na SoA.
- Políticas, procedimentos e responsabilidades.
- Planos de tratamento, ações e respectivos responsáveis.
- Monitoramento, indicadores, auditorias e análise crítica.
- Registros e evidências que sustentem as conclusões.

Quando pertinente, os documentos devem apresentar referências cruzadas para os artefatos relacionados.

A existência de uma política, um procedimento ou um modelo não deve ser interpretada isoladamente como prova de implementação, conformidade ou eficácia.

## 8. Situação dos documentos

As situações documentais devem ser interpretadas da seguinte maneira:

- **Planejado:** entrega prevista, ainda não publicada.
- **Em elaboração:** conteúdo em construção.
- **Em revisão:** conteúdo submetido a análise de consistência e qualidade.
- **Revisado no projeto:** conteúdo examinado no âmbito do desenvolvimento documental.
- **Validado no projeto:** conteúdo revisado e formalmente aceito como parte do guia conceitual.
- **Publicado:** arquivo disponível no repositório.

Esses estados se referem exclusivamente ao desenvolvimento documental do projeto autoral. Não representam aprovação corporativa, implementação em uma organização ou certificação de um SGSI.

## 9. Natureza e limitações do projeto

Este guia é um projeto autoral e conceitual destinado a apoiar profissionais na compreensão e na organização do trabalho de implementação de um SGSI.

Os exemplos e modelos devem ser adaptados ao contexto organizacional, aos riscos, aos requisitos legais e contratuais e aos critérios de governança aplicáveis.

O material:

- Não garante a obtenção de certificação.
- Não substitui as normas oficiais.
- Não substitui a análise dos requisitos aplicáveis.
- Não comprova a implementação de controles em uma organização.
- Não substitui auditoria independente ou avaliação profissional especializada.

A conclusão documental do projeto significa que os materiais previstos foram desenvolvidos e revisados dentro do escopo definido. Ela não equivale à implementação ou certificação de um SGSI.

## 10. Próximas atividades de desenvolvimento

As atividades de continuidade e encerramento documental incluem:

1. Verificar os links internos e a correspondência entre links e arquivos publicados.
2. Revisar a coerência entre os documentos e as referências normativas.
3. Verificar a consistência dos termos técnicos e dos nomes dos arquivos.
4. Avaliar lacunas documentais relevantes nos domínios do SGSI.
5. Revisar o README principal e os índices após alterações estruturais.
6. Registrar a situação final do projeto sem confundir conclusão documental com implementação real.

A conclusão dessas atividades deverá ser registrada de acordo com as verificações efetivamente realizadas. A inclusão de uma atividade nesta lista não significa que ela já tenha sido executada.

---

**Projeto:** Guia Técnico de Implementação do SGSI — ISO/IEC 27001:2022  
**Autor:** José Eduardo Moura Cardozo  
**Situação:** Em desenvolvimento
