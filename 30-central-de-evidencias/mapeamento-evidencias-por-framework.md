# Mapeamento de Evidências por Framework e Regulação

Mapeamento de referência que mostra como cada evidência do catálogo atende a mais de um framework ("coletar uma vez, reutilizar muitas vezes"). Deve ser validado pelo Jurídico e pelo Responsável pelo AIMS antes do uso em auditoria.

## 1. Mapeamento

| Evidência | ISO/IEC 42001:2023 | EU AI Act | NIST AI RMF 1.0 | LGPD | ISO/IEC 27001:2022 |
|---|---|---|---|---|---|
| EVD-GOV-001 Políticas de IA | 5.2 e A.2 | Art. 17 (sistema de gestão da qualidade) | GOVERN | Art. 50 (governança em privacidade) | 5.2 e A.5.1 |
| EVD-GOV-002 Atas do Comitê | 5.1 e 9.3 | Art. 17 | GOVERN | Art. 6º, X | 9.3 |
| EVD-GOV-003 Papéis e responsabilidades | 5.3 e A.3 | Art. 17 | GOVERN | Art. 41 (encarregado) | 5.3 |
| EVD-INV-001 Inventário de IA | 4.3 e A.4 | Arts. 49 e 71 (registro e base de dados da UE, quando aplicável) | GOVERN 1.6 | Art. 37 (registro das operações) | A.5.9 |
| EVD-RSK-001 Avaliações de risco | 6.1.2, 6.1.3 e 8.2 | Art. 9 (gestão de riscos) | MAP e MEASURE | Art. 6º, VIII (prevenção) | 6.1.2 e 8.2 |
| EVD-IMP-001 Avaliações de impacto e RIPD | 6.1.4, 8.4 e A.5 | Art. 27 (avaliação de impacto sobre direitos fundamentais, para certos implantadores) | MAP | Art. 38 (RIPD) | Não aplicável diretamente |
| EVD-REG-001 Classificação regulatória | 4.2 e 6.1 | Arts. 5, 6 e 50, Anexos I e III | MAP | Art. 6º | 4.2 |
| EVD-MOD-001 Validação de modelos | 8.1 e A.6 | Arts. 9 e 15 (precisão, robustez) | MEASURE | Art. 6º, V (qualidade dos dados) | 8.1 |
| EVD-MOD-002 Monitoramento e deriva | 9.1 e A.6 | Art. 72 (monitoramento pós-comercialização) | MEASURE e MANAGE | Art. 6º, VII | 9.1 |
| EVD-HUM-001 Supervisão humana | A.9 | Art. 14 (supervisão humana) e Art. 26 | GOVERN e MANAGE | Art. 20 (revisão de decisões automatizadas) | Não aplicável diretamente |
| EVD-SEC-001 Testes adversariais | 8.1 e A.6 | Art. 15 (cibersegurança) | MEASURE | Art. 46 (segurança) | 8.1 e A.8.29 |
| EVD-LOG-001 Logs de operação | A.6 | Arts. 12 e 19 (registro de eventos e guarda de logs) | MEASURE | Art. 37 | A.8.15 |
| EVD-DAD-001 Proveniência e qualidade de dados | A.7 | Art. 10 (governança de dados) | MAP | Art. 6º, V | A.5.12 (classificação da informação) |
| EVD-FOR-001 Fornecedores | A.10 | Arts. 25 e 26 (responsabilidades ao longo da cadeia) | GOVERN | Art. 39 (operador) | A.5.19 a A.5.22 |
| EVD-TRE-001 Treinamento | 7.2, 7.3 | Art. 4 (alfabetização em IA) | GOVERN | Art. 50 | 7.2 e 7.3 |
| EVD-INC-001 Incidentes | 10.2 e A.8 | Art. 73 (relato de incidentes graves) | MANAGE | Art. 48 (comunicação de incidente) | 10.2 e A.5.24 |
| EVD-AUD-001 Auditoria interna | 9.2 | Art. 17 | GOVERN | Art. 6º, X | 9.2 |
| EVD-KPI-001 KPIs e OKRs | 6.2 e 9.1 | Art. 72 | MEASURE | Art. 6º, X | 9.1 |
| EVD-DOC-001 Documentação técnica | 7.5 e A.6 | Art. 11 e Anexo IV | MAP | Art. 37 | 7.5 |
| EVD-TRA-001 Transparência | A.8 e A.9 | Arts. 13 e 50 | MAP | Arts. 9º e 20 | Não aplicável diretamente |

## 2. Cobertura por framework

| Framework | Requisitos aplicáveis | Requisitos com evidência | Cobertura | Lacunas |
|---|---|---|---|---|
| ISO/IEC 42001:2023 | | | | |
| EU AI Act | | | | |
| NIST AI RMF 1.0 | | | | |
| LGPD | | | | |
| ISO/IEC 27001:2022 | | | | |

Cobertura = requisitos com evidência vigente / requisitos aplicáveis.

## 3. Regras de manutenção

- O mapeamento é revisado a cada mudança de versão dos frameworks e da regulação
- Cada evidência deve estar ligada a ao menos um requisito; evidências sem requisito são revisadas
- Requisitos sem evidência são registrados como lacunas e recebem plano de ação
- Interpretações regulatórias devem ser validadas pelo Jurídico

## Referências

- ISO/IEC 42001:2023, cláusulas 4 a 10 e Anexo A
- Regulamento (UE) 2024/1689 (EU AI Act): Arts. 4, 9 a 15, 17, 19, 25, 26, 27, 50, 72 e 73; Anexo IV
- NIST AI 100-1: funções Govern, Map, Measure e Manage
- Lei nº 13.709/2018 (LGPD)
- ISO/IEC 27001:2022
