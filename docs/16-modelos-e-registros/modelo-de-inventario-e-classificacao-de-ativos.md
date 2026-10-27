# Modelo de Inventário e Classificação de Ativos de Informação

## 1. Objetivo

Este documento apresenta um modelo de referência para inventariar, identificar, classificar e acompanhar ativos de informação relevantes para o Sistema de Gestão de Segurança da Informação (SGSI).

O modelo busca apoiar a identificação dos ativos, de seus responsáveis, de sua localização, de sua importância para o negócio e dos requisitos de proteção aplicáveis.

O conteúdo deve ser adaptado ao contexto organizacional, ao escopo do SGSI, aos riscos identificados, aos requisitos legais e contratuais e aos critérios internos de governança.

**Importante:** este arquivo é um modelo conceitual. Seu conteúdo não comprova a existência de um inventário efetivamente preenchido ou de ativos avaliados em uma organização real.

## 2. Referências e alinhamento

A aplicação deste modelo deve considerar, conforme a pertinência:

- ISO/IEC 27001:2022 — requisitos do SGSI, especialmente contexto, avaliação e tratamento de riscos, recursos, controle operacional e informação documentada.
- ISO/IEC 27002:2022 — orientações relacionadas à responsabilidade pelos ativos, uso aceitável, classificação e tratamento da informação.
- ISO/IEC 27005 — orientações para gestão de riscos de Segurança da Informação.
- Lei nº 13.709/2018 (LGPD), quando houver tratamento de dados pessoais.
- Requisitos legais, regulatórios, contratuais e internos aplicáveis.

A organização deve consultar as normas oficiais e determinar os requisitos pertinentes ao seu contexto. Este modelo não substitui a consulta às normas.

## 3. Conceitos básicos

### 3.1 Ativo de informação

Informação ou recurso associado que possui valor para a organização e requer proteção. Conforme o contexto, pode incluir informações, sistemas, serviços, infraestrutura, equipamentos, mídias, processos e recursos humanos.

### 3.2 Proprietário do ativo

Papel ou pessoa formalmente responsável por definir requisitos de proteção, classificação, uso autorizado e decisões relacionadas ao ativo. A propriedade do ativo não significa necessariamente propriedade jurídica ou posse física.

### 3.3 Custodiante do ativo

Pessoa, equipe ou terceiro responsável pela guarda, operação ou administração técnica do ativo, conforme as atribuições definidas pela organização.

### 3.4 Classificação da informação

Processo de atribuição de uma categoria à informação, de acordo com sua sensibilidade, criticidade, valor, requisitos legais e consequências de divulgação, alteração, perda ou indisponibilidade.

### 3.5 Ciclo de vida do ativo

Conjunto de etapas pelas quais o ativo passa, como criação ou aquisição, registro, utilização, manutenção, transferência, arquivamento, desativação e descarte.

## 4. Orientações para utilização

O inventário deve ser construído de forma compatível com o escopo do SGSI e com a metodologia de gestão de riscos definida pela organização.

O nível de detalhamento deve permitir identificar os ativos relevantes e estabelecer relações com processos, informações, sistemas, fornecedores e riscos.

A organização deve definir:

- Critérios para determinar quais ativos serão inventariados.
- Responsáveis pela inclusão, atualização e validação dos registros.
- Critérios de classificação e tratamento da informação.
- Frequência de revisão e eventos que exigem atualização.
- Requisitos para acesso, armazenamento, retenção e descarte do inventário.
- Relação entre ativos, riscos, controles e planos de tratamento.

O inventário não deve ser tratado como uma lista estática. Mudanças tecnológicas, organizacionais, contratuais ou operacionais podem exigir revisão dos registros.

## 5. Modelo de registro do ativo

Os campos abaixo podem ser implementados em planilha, ferramenta de gestão de ativos, CMDB ou outro sistema autorizado.

### 5.1 Identificação e descrição

| Campo | Descrição ou orientação |
|---|---|
| Identificador do ativo | Código único para rastreabilidade. |
| Nome do ativo | Nome pelo qual o ativo é conhecido. |
| Descrição | Finalidade, conteúdo ou função do ativo. |
| Categoria | Informação, sistema, aplicação, equipamento, serviço, infraestrutura, mídia, processo ou outra categoria definida. |
| Processo de negócio relacionado | Processo que utiliza ou depende do ativo. |
| Unidade ou área responsável | Área organizacional relacionada ao ativo. |
| Localização | Local físico, ambiente lógico, região de hospedagem ou repositório autorizado. |
| Data de inclusão | Data de registro no inventário. |
| Situação | Proposto, ativo, em manutenção, suspenso, desativado ou outra situação definida. |

### 5.2 Responsabilidade e dependências

| Campo | Descrição ou orientação |
|---|---|
| Proprietário do ativo | Papel ou pessoa responsável por decisões relativas ao ativo. |
| Custodiante técnico | Equipe, pessoa ou terceiro responsável pela administração técnica. |
| Fornecedor relacionado | Terceiro que fornece, hospeda, mantém ou suporta o ativo, quando aplicável. |
| Ativos dependentes | Outros ativos necessários ao funcionamento ou à utilização do ativo registrado. |
| Processos dependentes | Processos cuja execução depende do ativo. |
| Responsável pela atualização | Papel encarregado de manter o registro atualizado. |

### 5.3 Classificação e requisitos de proteção

| Campo | Descrição ou orientação |
|---|---|
| Classificação da informação | Categoria definida conforme a política de classificação da organização. |
| Confidencialidade | Consequência da divulgação não autorizada. |
| Integridade | Consequência da alteração, corrupção ou destruição não autorizada. |
| Disponibilidade | Consequência da indisponibilidade ou interrupção do acesso. |
| Criticidade para o negócio | Importância do ativo para os processos e objetivos organizacionais. |
| Dados pessoais envolvidos | Indicação de tratamento de dados pessoais, quando aplicável. |
| Requisitos legais ou contratuais | Obrigações específicas associadas ao ativo. |
| Requisitos de retenção | Prazo e critérios de retenção, quando aplicáveis. |
| Requisitos de descarte | Condições para eliminação segura ou desativação. |

### 5.4 Riscos e controles relacionados

| Campo | Descrição ou orientação |
|---|---|
| Identificadores de riscos | Referências aos riscos associados no registro de riscos. |
| Ameaças relevantes | Eventos ou agentes que podem afetar o ativo. |
| Vulnerabilidades conhecidas | Fragilidades identificadas e pertinentes ao ativo. |
| Controles existentes | Medidas de proteção já implementadas, quando comprovadas. |
| Controles planejados | Medidas aprovadas ou propostas ainda não implementadas. |
| Referência à SoA | Relação com os controles considerados na Declaração de Aplicabilidade, quando pertinente. |
| Ações de tratamento | Referência ao plano de tratamento de riscos, quando aplicável. |
| Evidências associadas | Referências a registros ou documentos que sustentem as informações. |

### 5.5 Revisão e ciclo de vida

| Campo | Descrição ou orientação |
|---|---|
| Data da última revisão | Data da revisão mais recente do registro. |
| Responsável pela revisão | Papel ou pessoa que realizou a revisão. |
| Motivo da revisão | Inclusão, alteração, incidente, mudança, auditoria ou revisão periódica. |
| Data prevista para nova revisão | Data definida conforme os critérios organizacionais. |
| Situação do ciclo de vida | Em aquisição, em uso, em manutenção, em transição, arquivado ou desativado. |
| Data de desativação | Quando aplicável. |
| Destino ou método de descarte | Destino final ou método de eliminação autorizado. |
| Observações | Informações complementares necessárias à rastreabilidade. |

## 6. Critérios de classificação da informação

A organização deve aprovar uma taxonomia de classificação compatível com sua realidade. O exemplo abaixo é ilustrativo e não representa uma classificação universal ou obrigatória.

| Classe ilustrativa | Descrição geral | Exemplo de tratamento esperado |
|---|---|---|
| Pública | Informação autorizada para divulgação pública. | Validar a autorização de divulgação e preservar a integridade. |
| Interna | Informação destinada ao uso interno, sem autorização automática para divulgação externa. | Restringir o acesso conforme a necessidade de uso. |
| Confidencial | Informação cuja divulgação indevida pode causar impactos relevantes. | Aplicar acesso restrito, proteção durante armazenamento e transmissão e rastreabilidade apropriada. |
| Restrita | Informação de alta sensibilidade, sujeita a requisitos reforçados. | Aplicar controles adicionais definidos pela organização, como acesso estritamente autorizado e monitoramento apropriado. |

Os nomes, as definições e os controles associados às classes devem ser aprovados pela organização. Informações pessoais, financeiras, contratuais, estratégicas ou reguladas podem exigir tratamento específico, independentemente do nome atribuído à classe.

## 7. Avaliação de confidencialidade, integridade e disponibilidade

A organização pode estabelecer escalas qualitativas ou quantitativas para avaliar o impacto da perda de confidencialidade, integridade e disponibilidade.

Exemplo de escala qualitativa:

- **Baixo:** impacto limitado, com recuperação simples e sem consequências relevantes identificadas.
- **Moderado:** impacto que exige atuação coordenada, pode interromper atividades ou gerar consequências administráveis.
- **Alto:** impacto significativo sobre processos, clientes, obrigações ou objetivos organizacionais.
- **Crítico:** impacto muito grave, potencialmente sistêmico ou incompatível com a continuidade aceitável das atividades.

Essas definições são ilustrativas. Devem ser ajustadas e aprovadas de acordo com os critérios de risco da organização.

A avaliação deve considerar cenários realistas, incluindo divulgação indevida, alteração não autorizada, perda, destruição, indisponibilidade e comprometimento do ativo.

Não se deve atribuir automaticamente uma classe de informação a um ativo apenas por sua categoria técnica. A classificação deve considerar o conteúdo tratado, a finalidade, o contexto e as consequências de um comprometimento.

## 8. Regras de preenchimento e validação

Para assegurar consistência, recomenda-se:

1. Atribuir identificador único a cada registro.
2. Descrever o ativo de forma suficientemente clara para diferenciá-lo de outros ativos.
3. Identificar proprietário e custodiante, quando aplicável.
4. Relacionar o ativo aos processos e serviços relevantes.
5. Aplicar os critérios de classificação aprovados.
6. Registrar dependências e fornecedores relevantes.
7. Relacionar riscos, controles e planos de tratamento existentes.
8. Identificar lacunas de informação e atribuir responsáveis por sua resolução.
9. Validar os registros com os responsáveis pertinentes.
10. Registrar alterações relevantes para manter a rastreabilidade.

Quando uma informação não estiver disponível, registrar a pendência e seu responsável, em vez de presumir que o requisito foi atendido.

## 9. Revisão do inventário

A frequência de revisão deve ser definida pela organização com base na criticidade, na velocidade de mudança e nos riscos associados aos ativos.

Além da revisão periódica, o inventário deve ser reavaliado quando ocorrerem eventos como:

- Aquisição, criação ou desativação de sistemas e serviços.
- Alterações relevantes na infraestrutura ou na arquitetura tecnológica.
- Mudanças de fornecedor, contrato ou local de hospedagem.
- Mudanças nos processos de negócio ou no escopo do SGSI.
- Identificação de novos requisitos legais ou contratuais.
- Incidentes, auditorias ou avaliações que revelem divergências.
- Alterações relevantes na classificação ou nos requisitos de proteção.

A revisão deve verificar a existência do ativo, a precisão dos dados, a validade dos responsáveis, a classificação e a coerência das relações com riscos e controles.

## 10. Indicadores possíveis

Os indicadores devem ser definidos considerando a finalidade do inventário, a disponibilidade dos dados e a capacidade de produzir informações confiáveis.

Exemplos:

- Percentual de ativos relevantes registrados em relação ao universo identificado.
- Percentual de ativos com proprietário definido.
- Percentual de ativos com classificação revisada.
- Percentual de registros revisados dentro do prazo.
- Quantidade de divergências entre inventário e ambiente observado.
- Quantidade de ativos sem responsável identificado.
- Quantidade de registros pendentes de validação.

Quando forem utilizados percentuais, a organização deve definir numerador, denominador, fonte, periodicidade, responsável e critérios de interpretação. Os indicadores não devem ser apresentados como resultados reais sem dados verificáveis.

## 11. Proteção do inventário

O inventário pode conter informações sensíveis sobre a arquitetura, os sistemas, os responsáveis, as dependências e a localização de ativos.

Por isso, a organização deve avaliar a necessidade de:

- Restringir o acesso por função e necessidade de uso.
- Registrar alterações e acessos relevantes, quando apropriado.
- Manter cópias de segurança e mecanismos de recuperação.
- Controlar exportações, compartilhamentos e cópias locais.
- Definir retenção e descarte seguro.
- Evitar a exposição pública de detalhes que aumentem riscos operacionais ou de segurança.

O próprio inventário deve ser tratado como um ativo de informação sujeito a classificação e proteção.

## 12. Checklist de validação

- [ ] O escopo e os critérios de inventário foram definidos.
- [ ] Os ativos relevantes foram identificados.
- [ ] Cada registro possui identificador único.
- [ ] Os proprietários e custodiante(s) estão identificados, quando aplicável.
- [ ] Os processos e as dependências relevantes foram registrados.
- [ ] A classificação foi aplicada segundo critérios aprovados.
- [ ] Os requisitos legais e contratuais pertinentes foram considerados.
- [ ] Os riscos e controles relacionados possuem referências rastreáveis.
- [ ] As pendências de informação possuem responsáveis.
- [ ] A revisão periódica e os gatilhos de atualização foram definidos.
- [ ] O acesso e a proteção do inventário foram estabelecidos.
- [ ] Os indicadores possuem critérios de cálculo e fontes identificadas.

O checklist deve ser preenchido com base em verificações efetivamente realizadas. A existência deste modelo, isoladamente, não significa que os itens foram atendidos.

## 13. Limitações e adaptação

Este modelo não define uma taxonomia universal, não determina sozinho quais ativos devem integrar o inventário e não substitui a avaliação de riscos.

A organização deve adaptar os campos, critérios, responsabilidades, níveis de classificação e regras de revisão ao seu contexto, ao escopo do SGSI e às obrigações aplicáveis.

A presença de um controle, uma evidência ou uma classificação neste modelo não comprova sua implementação ou eficácia. Essas condições devem ser verificadas por registros e evidências apropriados.

## 14. Histórico de revisão

| Versão | Data | Descrição | Responsável |
|---|---|---|---|
| 1.0 | A preencher | Criação do modelo de referência. | A definir |

---

**Projeto:** Guia Técnico de Implementação do SGSI — ISO/IEC 27001:2022  
**Autor:** José Eduardo Moura Cardozo  
**Tipo de documento:** Modelo de referência  
**Status:** Modelo conceitual para adaptação e validação organizacional
