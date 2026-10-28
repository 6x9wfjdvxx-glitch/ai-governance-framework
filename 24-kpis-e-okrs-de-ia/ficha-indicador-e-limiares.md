# Ficha de Indicador e Limiares de Desempenho

Preencher uma ficha para cada KPI antes de sua adoção.

## 1. Ficha de Indicador

| Campo | Preenchimento |
|---|---|
| ID do indicador | |
| Nome | |
| Objetivo de governança ou controle associado | |
| Requisito regulatório associado | |
| Definição | |
| Fórmula de cálculo | |
| Fonte dos dados | |
| Método de coleta (manual ou automatizado) | |
| Unidade de medida | |
| Frequência de medição | |
| Meta | |
| Limiar amarelo (atenção) | |
| Limiar vermelho (crítico) | |
| Proprietário do indicador | |
| Destinatários do reporte | |
| Data de aprovação | |
| Próxima revisão | |

## 2. Critérios de qualidade do indicador

- [ ] Específico: mede um único aspecto claramente definido
- [ ] Mensurável: fórmula e fonte de dados definidas
- [ ] Atingível: meta realista para o nível de maturidade
- [ ] Relevante: vinculado a objetivo, controle ou requisito
- [ ] Temporal: frequência e prazo estabelecidos
- [ ] Rastreável: dados reproduzíveis e auditáveis
- [ ] Não induz comportamento indesejado (subnotificação ou manipulação)

## 3. Modelo de limiares (semáforo)

| Cor | Significado | Ação exigida |
|---|---|---|
| Verde | Dentro da meta | Manter monitoramento |
| Amarelo | Desvio moderado | Análise do responsável e plano de correção em até 30 dias |
| Vermelho | Desvio crítico | Escalonamento ao Comitê, análise de causa e plano de ação em até 10 dias úteis |

## 4. Exemplo preenchido

| Campo | Preenchimento |
|---|---|
| ID do indicador | RSK-03 |
| Nome | Modelos com validação independente vigente |
| Objetivo associado | Garantir validação de modelos de risco alto e crítico |
| Requisito regulatório associado | EU AI Act, Art. 9; boas práticas SR 11-7 |
| Definição | Percentual de modelos que exigem validação com parecer vigente |
| Fórmula | Modelos validados dentro do prazo / modelos que exigem validação |
| Fonte dos dados | Registro de validações (pasta 23) |
| Método de coleta | Extração do registro, mensal |
| Unidade | Percentual |
| Frequência | Trimestral |
| Meta | 100% |
| Limiar amarelo | Abaixo de 95% |
| Limiar vermelho | Abaixo de 85% |
| Proprietário | Validação de modelos |
| Destinatários | Comitê de Governança de IA |

## Referências

- ISO/IEC 27004:2016, modelo de medição e atributos de qualidade de medidas
- ISO/IEC 42001:2023, cláusula 9.1
- NIST AI 100-1, função Measure
