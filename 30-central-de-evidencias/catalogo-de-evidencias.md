# Catálogo de Evidências de Governança de IA

Catálogo-base de evidências. Cada linha deve ser ajustada à realidade da organização e aprovada pelo Proprietário da Central de Evidências.

## 1. Campos do catálogo

| Campo | Descrição |
|---|---|
| ID | Identificador único (EVD-área-número) |
| Evidência | Nome da evidência |
| Tipo | Documento, registro, relatório, log ou atestação |
| Fonte | Sistema ou área que gera a evidência |
| Proprietário | Responsável pela geração e atualização |
| Frequência | Periodicidade de atualização |
| Retenção | Prazo de guarda |
| Classificação | Pública, interna, confidencial ou restrita |
| Pasta de referência | Pasta do repositório que descreve o controle |

## 2. Catálogo-base

| ID | Evidência | Tipo | Fonte | Proprietário | Frequência | Classificação | Pasta |
|---|---|---|---|---|---|---|---|
| EVD-GOV-001 | Política de IA e políticas complementares aprovadas | Documento | Gestão de políticas | Governança de IA | Anual | Interna | 03 |
| EVD-GOV-002 | Atas e deliberações do Comitê de Governança de IA | Registro | Comitê | Secretaria do Comitê | Por reunião | Confidencial | 20 |
| EVD-GOV-003 | Organograma de papéis e responsabilidades de IA | Documento | Governança de IA | Governança de IA | Anual | Interna | 14 |
| EVD-INV-001 | Inventário de sistemas de IA com classificação de risco | Registro | Inventário de IA | Proprietário do inventário | Mensal | Confidencial | 04 |
| EVD-RSK-001 | Avaliações de risco de sistemas de IA | Relatório | Gestão de riscos | Gestão de riscos de IA | Por sistema e anual | Confidencial | 02, 05 |
| EVD-IMP-001 | Avaliações de impacto e RIPD/DPIA | Relatório | Privacidade | Privacidade | Por sistema | Restrita | 05, 06 |
| EVD-REG-001 | Classificação regulatória de sistemas (EU AI Act) | Relatório | Conformidade | Conformidade | Por sistema | Confidencial | 29 |
| EVD-MOD-001 | Relatórios de validação independente de modelos | Relatório | Validação de modelos | Validação de modelos | Por modelo e periódica | Confidencial | 23 |
| EVD-MOD-002 | Relatórios de monitoramento, desempenho e deriva | Relatório | Plataforma de ML | Proprietário do modelo | Mensal | Confidencial | 11, 23 |
| EVD-HUM-001 | Registros de supervisão e intervenção humana | Registro | Sistemas operacionais | Proprietário do processo | Mensal | Confidencial | 21 |
| EVD-SEC-001 | Resultados de testes adversariais e de segurança | Relatório | Segurança | Segurança da informação | Por sistema de risco alto | Restrita | 08, 22 |
| EVD-LOG-001 | Logs de operação de sistemas de IA de risco alto | Log | Plataformas e aplicações | Equipe de tecnologia | Contínua | Restrita | 29 |
| EVD-DAD-001 | Documentação de proveniência e qualidade de dados | Documento | Governança de dados | Governança de dados | Por conjunto de dados | Confidencial | 19 |
| EVD-FOR-001 | Avaliações e contratos de fornecedores de IA | Relatório | Gestão de fornecedores | Gestão de fornecedores | Anual | Confidencial | 17 |
| EVD-TRE-001 | Registros de treinamento e conscientização | Registro | Plataforma de treinamento | Treinamento | Trimestral | Interna | 16 |
| EVD-INC-001 | Registros de incidentes de IA e ações corretivas | Registro | Gestão de incidentes | Gestão de incidentes | Por evento | Restrita | 18 |
| EVD-AUD-001 | Programa e relatórios de auditoria interna | Relatório | Auditoria Interna | Auditoria Interna | Anual | Confidencial | 13 |
| EVD-KPI-001 | Relatórios de KPIs e OKRs de IA | Relatório | Painel de indicadores | Governança de IA | Trimestral | Interna | 24 |
| EVD-MAT-001 | Avaliações de maturidade e planos de evolução | Relatório | Governança de IA | Governança de IA | Anual | Interna | 25 |
| EVD-DOC-001 | Documentação técnica de sistemas de IA de risco alto | Documento | Equipe de desenvolvimento | Proprietário do sistema | Por versão | Restrita | 29 |
| EVD-TRA-001 | Avisos de transparência e instruções de uso | Documento | Produto e Jurídico | Proprietário do sistema | Por versão | Pública ou interna | 29 |
| EVD-ATE-001 | Atestações de proprietários de controle | Atestação | Central de Evidências | Proprietários de controle | Trimestral | Interna | 30 |

## 3. Regras de manutenção

- Novas evidências recebem ID sequencial por área
- Evidências retiradas são arquivadas com justificativa, e não apagadas do histórico
- O catálogo é revisado trimestralmente e após qualquer mudança de framework ou de processo
- Toda evidência crítica deve ter proprietário titular e substituto

## Referências

- ISO/IEC 42001:2023, cláusula 7.5
- EU AI Act, Arts. 11, 12, 13 e 17
- NIST AI 100-1, funções Govern e Measure
- LGPD, Arts. 37 e 38
