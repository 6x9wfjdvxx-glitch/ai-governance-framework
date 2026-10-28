# Catálogo de KPIs de Governança de IA

Metas são valores de referência e devem ser calibradas e aprovadas pelo Comitê de Governança de IA conforme a maturidade da organização.

## 1. Governança e inventário

| ID | KPI | Fórmula | Frequência | Meta de referência | Responsável |
|---|---|---|---|---|---|
| GOV-01 | Cobertura do inventário de IA | Sistemas de IA registrados / sistemas de IA identificados | Trimestral | 100% | Proprietário do inventário |
| GOV-02 | Sistemas com risco classificado | Sistemas classificados / sistemas inventariados | Trimestral | 100% | Gestão de riscos de IA |
| GOV-03 | Políticas revisadas no prazo | Políticas revisadas no prazo / políticas com revisão prevista | Semestral | 95% ou mais | Governança de IA |

## 2. Risco e avaliação

| ID | KPI | Fórmula | Frequência | Meta de referência | Responsável |
|---|---|---|---|---|---|
| RSK-01 | Sistemas de risco alto com avaliação válida | Avaliações vigentes / sistemas de risco alto | Trimestral | 100% | Gestão de riscos de IA |
| RSK-02 | Riscos críticos com plano de tratamento | Riscos críticos com plano / riscos críticos | Mensal | 100% | Gestão de riscos de IA |
| RSK-03 | Modelos com validação independente vigente | Modelos validados dentro do prazo / modelos que exigem validação | Trimestral | 100% (alto e crítico) | Validação de modelos |

## 3. Desempenho e estabilidade de modelos

| ID | KPI | Fórmula | Frequência | Meta de referência | Responsável |
|---|---|---|---|---|---|
| MOD-01 | Modelos dentro dos limiares de desempenho | Modelos dentro do limiar / modelos monitorados | Mensal | 90% ou mais | Proprietário do modelo |
| MOD-02 | Modelos com deriva acima do limiar | Modelos com PSI acima do limiar / modelos monitorados | Mensal | Menos de 5% | Proprietário do modelo |
| MOD-03 | Achados de validação críticos vencidos | Achados críticos vencidos | Mensal | 0 | Validação de modelos |

## 4. Supervisão humana

| ID | KPI | Fórmula | Frequência | Meta de referência | Responsável |
|---|---|---|---|---|---|
| SUP-01 | Decisões de alto impacto com validação humana registrada | Decisões validadas / decisões de alto impacto | Mensal | 100% | Proprietário do processo |
| SUP-02 | Taxa de intervenção humana | Intervenções / decisões supervisionadas | Mensal | Acompanhar tendência | Proprietário do processo |

## 5. Incidentes

| ID | KPI | Fórmula | Frequência | Meta de referência | Responsável |
|---|---|---|---|---|---|
| INC-01 | Incidentes de IA por severidade | Quantidade por severidade no período | Mensal | Tendência decrescente | Gestão de incidentes |
| INC-02 | Tempo médio de resposta (MTTR) | Média de tempo entre detecção e contenção | Mensal | Conforme SLA por severidade | Gestão de incidentes |
| INC-03 | Incidentes com lições aprendidas aplicadas | Incidentes com melhoria implementada / incidentes encerrados | Trimestral | 90% ou mais | Gestão de incidentes |

## 6. Privacidade e dados

| ID | KPI | Fórmula | Frequência | Meta de referência | Responsável |
|---|---|---|---|---|---|
| PRV-01 | Sistemas de IA com RIPD/DPIA quando aplicável | Sistemas com RIPD / sistemas que exigem RIPD | Trimestral | 100% | Privacidade |
| PRV-02 | Conjuntos de dados com proveniência documentada | Conjuntos documentados / conjuntos utilizados | Trimestral | 95% ou mais | Governança de dados |

## 7. Fornecedores

| ID | KPI | Fórmula | Frequência | Meta de referência | Responsável |
|---|---|---|---|---|---|
| FOR-01 | Fornecedores de IA críticos avaliados | Fornecedores avaliados / fornecedores críticos | Semestral | 100% | Gestão de fornecedores |
| FOR-02 | Contratos com cláusulas de IA | Contratos com cláusulas / contratos de IA | Semestral | 100% | Jurídico |

## 8. Treinamento e cultura

| ID | KPI | Fórmula | Frequência | Meta de referência | Responsável |
|---|---|---|---|---|---|
| TRE-01 | Colaboradores treinados em uso responsável de IA | Treinados / público-alvo | Trimestral | 95% ou mais | Treinamento |
| TRE-02 | Aprovação em avaliação de conscientização | Aprovados / participantes | Trimestral | 85% ou mais | Treinamento |

## 9. Auditoria e conformidade

| ID | KPI | Fórmula | Frequência | Meta de referência | Responsável |
|---|---|---|---|---|---|
| AUD-01 | Achados de auditoria encerrados no prazo | Encerrados no prazo / achados com prazo vencido ou previsto | Trimestral | 90% ou mais | Auditoria Interna |
| AUD-02 | Controles de IA implementados | Controles implementados / controles aplicáveis | Trimestral | Conforme roadmap | Governança de IA |

## Referências

- ISO/IEC 42001:2023, cláusula 9.1 e Anexo A
- NIST AI 100-1, função Measure
- ISO/IEC 27004:2016
- Pasta 11-ai-metrics-monitoring deste repositório
